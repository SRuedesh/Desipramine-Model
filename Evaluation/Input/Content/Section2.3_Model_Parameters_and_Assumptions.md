### 2.3.1 Absorption

The model includes intravenous and oral desipramine applications. Intravenous simulations do not require an absorption process. Oral desipramine simulations are represented with a solution-type formulation and compound-specific intestinal permeability.

The `Specific intestinal permeability` for desipramine was optimized using oral concentration-time data. The 2-hydroxydesipramine intestinal permeability was calculated and is relevant for metabolite simulations where the compound is present as a separate building block.

The intravenous simulations provide information for systemic disposition without absorption. Oral simulations use the same systemic disposition assumptions and add the intestinal permeability term. This allows the oral absorption parameter to be interpreted separately from the CYP2D6 and residual clearance parameters.

No phenotype-specific absorption parameter was introduced. Differences between CYP2D6 groups and inhibitor scenarios are represented through metabolism, while the same oral absorption assumptions are applied across adult simulations.

### 2.3.2 Distribution

Desipramine plasma protein binding was represented by a fraction unbound of 14% as summarized in [Section 2.2.1](Section2.2_Data.md). Lipophilicity was optimized and is an important parameter for the parent volume of distribution.

Partition coefficients were calculated with the Rodgers and Rowland method. Because the model includes both parent and metabolite concentration-time profiles, distribution assumptions affect the interpretation of desipramine and 2-hydroxydesipramine profiles separately.

The model uses compound-specific distribution properties for desipramine and 2-hydroxydesipramine. Parent distribution is particularly important because desipramine is extensively distributed and the concentration-time profile after intravenous administration constrains this part of the model. Metabolite distribution is interpreted more cautiously because metabolite profiles are less comprehensive than parent profiles.

Distribution was kept independent of CYP2D6 status. CYP2D6 poor-, extensive-, and higher-activity groups differ through formation clearance, while the same adult physiological and binding assumptions are applied.

### 2.3.3 Metabolism and Elimination

One explicit metabolic conversion and residual elimination pathways are represented in the model.

* CYP2D6

Desipramine is converted to 2-hydroxydesipramine by CYP2D6. CYP2D6 K<sub>m</sub> is held constant across CYP2D6 groups. Poor-metabolizer k<sub>cat</sub> is set to zero, while normal and higher activity-score k<sub>cat</sub> values were optimized.

This structure assigns CYP2D6 phenotype and activity-score effects to catalytic capacity rather than to affinity. It also makes desipramine suitable for evaluating CYP2D6 inhibitor scenarios because reduced CYP2D6 activity should increase parent exposure and reduce metabolite formation.

* Residual elimination

The model includes residual hepatic clearance for desipramine and unspecific hepatic clearance for 2-hydroxydesipramine. Both parent and metabolite include passive renal filtration with a `GFR fraction` of 1.

Residual hepatic clearance accounts for desipramine elimination not explicitly assigned to CYP2D6 2-hydroxylation. The metabolite unspecific hepatic clearance represents downstream elimination of 2-hydroxydesipramine. Renal filtration is implemented as a passive process using adult renal physiology and the fraction unbound of the respective compound.

### 2.3.4 Automated Parameter Identification

The following parameters were optimized by fitting the model to the data:

| Model Parameter |
| --- |
| `Lipophilicity` |
| `Specific intestinal permeability` |
| CYP2D6 k<sub>cat</sub> values |
| desipramine residual hepatic clearance |
| 2-hydroxydesipramine unspecific CL<sub>hep</sub> |

The optimized parameters were selected to describe distribution, oral absorption, CYP2D6-mediated formation, and residual clearance. Parameters with direct physicochemical or plasma-binding sources were kept fixed. The separation of optimized absorption and clearance terms is necessary because both oral and intravenous studies contribute to the evaluation.
