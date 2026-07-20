The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](References.md)). Relevant information on anthropometric and physiological parameters in adults was gathered from the literature and incorporated into PK-Sim as default values for adult simulations ([Willmann 2007](References.md)).

The applied activity and variability of plasma proteins and active processes integrated into PK-Sim are described in the publicly available PK-Sim Ontogeny Database or otherwise referenced for the specific process.

The desipramine model was developed as a parent-metabolite PBPK model with desipramine and 2-hydroxydesipramine. It was included in the comprehensive CYP2D6 drug-drug-gene interaction network by [Rüdesheim 2025](References.md). The model was built using intravenous and oral desipramine data to inform distribution, absorption, CYP2D6-mediated metabolism, and residual elimination.

Clinical studies used for model building covered intravenous and oral desipramine administration in CYP2D6 poor-, extensive-, and fast-metabolizer groups. Verification simulations included independent oral studies, activity-score groups, and CYP2D6 inhibitor interaction scenarios. The model therefore separates parent desipramine performance from 2-hydroxydesipramine performance where metabolite data are available.

The intravenous data support distribution and systemic clearance assumptions without confounding by oral absorption. Oral studies then support absorption and first-pass metabolism. This split is important for desipramine because the same model must describe both parent exposure and metabolite formation across CYP2D6 function groups.

The structural model contains CYP2D6-mediated 2-hydroxylation, residual hepatic clearance, passive renal filtration, and oral absorption. CYP2D6 poor-metabolizer activity is represented by zero CYP2D6 k<sub>cat</sub>, while normal and higher activity-score groups use optimized CYP2D6 k<sub>cat</sub> values.

The evaluated applications include intravenous infusion or bolus dosing and oral dosing. The major proteins and processes represented explicitly are CYP2D6, plasma protein binding, residual hepatic clearance, and passive renal filtration. Inhibition simulations are interpreted through the CYP2D6 pathway because desipramine is a sensitive CYP2D6 substrate.

The evaluation therefore uses parent concentration-time profiles as the primary readout and metabolite profiles where available as supporting evidence for the CYP2D6 formation pathway. Model-building and verification profiles are separated to preserve the logic of fitting structural parameters first and then evaluating independent clinical scenarios.

Details about input data are provided in [Section 2.2](Section2.2_Data.md). Details about the structural model and assumptions are provided in [Section 2.3](Section2.3_Model_Parameters_and_Assumptions.md).
