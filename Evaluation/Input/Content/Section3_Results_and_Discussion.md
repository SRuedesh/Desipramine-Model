The PBPK model for desipramine was developed and evaluated with clinical pharmacokinetic data after intravenous and oral administration. The evaluation covers desipramine and 2-hydroxydesipramine plasma concentration-time profiles, CYP2D6 poor-, extensive-, normal-, and higher-activity groups, and interaction settings in which desipramine acts as a sensitive CYP2D6 victim drug.

The model-building data informed systemic disposition, oral absorption, CYP2D6-mediated 2-hydroxylation, residual hepatic clearance, and metabolite elimination. Intravenous and oral phenotype-stratified data from [Brøsen 1988](#5-references), [Brøsen 1986](#5-references), and [Spina 1987](#5-references) supported CYP2D6 phenotype-dependent clearance. Oral studies with parent and metabolite measurements, including [Boni 2009](#5-references), supported the parent-metabolite structure. Additional oral data from [Aarnoutse 2005](#5-references), [Harris 2007](#5-references), and [Madani 2002](#5-references) supported adult oral exposure after 50 mg dosing.

Verification used independent studies across CYP2D6 activity and interaction settings, including [Bergmann 2001](#5-references), [Hynes 2015](#5-references), [Bergstrom 1992](#5-references), [Nichols 2013](#5-references), [Patroneva 2008](#5-references), [Skinner 2003](#5-references), and [Spina 1995](#5-references). These data test whether the same model can describe adult oral desipramine exposure without study-specific refitting.

The model quantifies CYP2D6-mediated 2-hydroxylation, residual hepatic clearance of desipramine, unspecific hepatic clearance of 2-hydroxydesipramine, passive glomerular filtration, and enterohepatic circulation. CYP2D6 k<sub>cat</sub> values represent the major phenotype and activity-score dependency. The metabolite pathway is important because adequate parent prediction alone would not demonstrate correct description of 2-hydroxydesipramine exposure.

The next sections show:

1. the final model input parameters for the building blocks: [Section 3.1](Input_table.md).
2. the overall goodness of fit: [Section 3.2](GOF_diagnostics.md).
3. simulated vs. observed concentration-time profiles for the clinical studies used for model building and for model verification: [Section 3.3](Concentration_time_profiles.md).

The merged GOF diagnostic over the included concentration observations gives GMFE values of 1.28 for desipramine, 1.27 for 2-hydroxydesipramine, and 1.28 for all observations. The close agreement between parent and metabolite GMFE values is important because it indicates that the model is not fitting parent exposure at the expense of metabolite behavior.

The concentration-time profiles should be interpreted by dose route, analyte, and CYP2D6 activity group. Intravenous data mainly test systemic distribution and clearance. Oral data additionally test absorption and first-pass metabolism. Poor-metabolizer profiles are expected to show reduced CYP2D6-mediated 2-hydroxylation, while normal- and higher-activity groups test the activity-score-dependent k<sub>cat</sub> values.

[Rüdesheim 2025](#5-references) used the desipramine model in a broader CYP2D6 DDGI network. In that setting, desipramine served as a sensitive CYP2D6 substrate for inhibition and genotype interaction scenarios. The present evaluation should therefore be read as a compound-level check of desipramine and 2-hydroxydesipramine exposure, while DDGI performance depends additionally on perpetrator models and interaction constants.

The model is adequate for adult desipramine simulations within the represented intravenous and oral dose range and CYP2D6 activity groups. Extrapolation to unrepresented populations, strong P-gp effects, or tissue-specific pharmacodynamic endpoints should remain outside the evidence supported by this report.
