### In vitro and physicochemical data

The table below summarizes the drug-dependent inputs documented for the desipramine model ([Table 1](#table-1)). Parameter values are listed for desipramine and 2-hydroxydesipramine where they are relevant for interpreting the parent-metabolite simulations.

| Parameter | Unit | Value | Source | Description |
| --- | ---: | ---: | --- | --- |
| **Desipramine** |  |  |  |  |
| MW | g/mol | 266.4 | [Kim 2019](#5) | Molecular weight of desipramine free base. |
| pK<sub>a</sub> | - | 2.84<sup>a</sup> | [Swain 2012](#5) | Acid dissociation constant. |
| pK<sub>a</sub> | - | 10.02<sup>a</sup> | [Wishart 2006](#5) | Acid dissociation constant. |
| Solubility | mg/L | 214.29 | [Swain 2012](#5) | Aqueous solubility at pH 6.5. |
| logP | - | 3.52 | Optimized | Octanol-water partition coefficient of the neutral species. |
| f<sub>u</sub> | % | 14 | [Watanabe 2018](#5) | Fraction unbound in plasma. |
| K<sub>m,CYP2D6</sub> | µmol/L | 0.73 | [Ball 1997](#5); [Austin 2002](#5) | Unbound-incubation-corrected Michaelis constant for 2-hydroxylation. |
| k<sub>cat,CYP2D6</sub>, NM | 1/min | 5.03 | Optimized | Catalytic rate constant for 2-hydroxylation in normal metabolizers. |
| CL<sub>hep</sub> | 1/min | 0.54 | Optimized | Unspecific hepatic clearance. |
| P<sub>int</sub> | cm/min | 1.14E-05 | Optimized | Specific transcellular intestinal permeability. |
| Oral formulation | - | Solution | Assumed | Formulation used for oral predictions. |
| **2-Hydroxydesipramine** |  |  |  |  |
| MW | g/mol | 282.4 | [Kim 2019](#5) | Molecular weight. |
| pK<sub>a</sub> | - | 4.51<sup>a</sup> | [Swain 2012](#5) | Acid dissociation constant. |
| pK<sub>a</sub> | - | 9.90<sup>a</sup> | [Swain 2012](#5) | Acid dissociation constant. |
| pK<sub>a</sub> | - | 10.63<sup>b</sup> | [Swain 2012](#5) | Acid dissociation constant. |
| Solubility | mg/L | 282.39 | [Swain 2012](#5) | Aqueous solubility at pH 6.5. |
| logP | - | 2.33 | Optimized | Octanol-water partition coefficient of the neutral species. |
| f<sub>u</sub> | % | 12 | [Watanabe 2018](#5) | Fraction unbound in plasma. |
| CL<sub>hep</sub> | 1/min | 9.93 | Optimized | Unspecific hepatic clearance. |
| P<sub>int</sub> | cm/min | 3.19E-05 | Calculated | Specific transcellular intestinal permeability. |
| **Shared distribution and elimination parameters** |  |  |  |  |
| GFR fraction | - | 1.00 | Assumed | Fraction used to scale passive glomerular filtration. |
| Partition coefficients | - | Diverse | Calculated | Tissue-to-plasma partition coefficients calculated with the Rodgers and Rowland method. |
| Cellular permeabilities | cm/min | 0.27 / 0.01 | Calculated | Cellular permeabilities for desipramine and 2-hydroxydesipramine calculated with the PK-Sim Standard method. |

**Table 1:**<a name="table-1"></a> Drug-dependent physicochemical, distribution, metabolism, elimination, and formulation parameters used in the final desipramine model.

<sup>a</sup> Basic. <sup>b</sup> Acidic.

The CYP2D6 characterization-specific catalytic rate constants used in the model are listed below.

| CYP2D6 characterization | k<sub>cat</sub> [1/min] | Parameter origin |
| --- | ---: | --- |
| AS = 0 (PM) | 0.00 | Assumed |
| NM baseline | 5.03 | Optimized |
| AS = 2 (NM) | 9.86 | Optimized |
| AS = 2.5 (UM) | 28.88 | Optimized |

**Table 1a:**<a name="table-1a"></a> CYP2D6 characterization-specific k<sub>cat</sub> values for desipramine 2-hydroxylation reported by [Rüdesheim 2025](#5). Parenthetical phenotypes for AS-coded rows use the current CPIC CYP2D6 activity score-to-phenotype mapping ([Moore 2026](#5)). AS: activity score; NM: normal metabolizer; PM: poor metabolizer; UM: ultrarapid metabolizer.

### Clinical data

The evaluation uses desipramine and 2-hydroxydesipramine plasma concentration-time profiles from peripheral venous blood. The profiles used for model building and verification are listed in [Table 2](#table-2).

| Source | Dose [mg] / schedule\* | Age [years] | Weight [kg] | Sex | N | Form. | CYP2D6 characterization |
| --- | --- | --- | --- | --- | ---: | --- | --- |
| [Aarnoutse 2005](#5)<sup>+</sup> | 50 mg, oral, single dose | 26 (20-56) | 84 (69-93) | Male | 13 | NR | EM |
| [Bergmann 2001](#5) | 100 mg, oral, single dose | 26.8 (24-33) | NR | 83% female | 6 | NR | AS = 2 (NM) |
| [Bergmann 2001](#5) | 100 mg, oral, single dose | 36.7 (22-54) | NR | 33% female | 6 | NR | AS = 2.5 (UM) |
| [Bergstrom 1992](#5) | 50 mg, oral, single dose | 44 (35-53) | 78.2 (60.3-92.8) | Male | 6 | NR | EM |
| [Boni 2009](#5)<sup>+</sup> | 50 mg, oral, single dose | 33.6 ± 7.2 | 80.9 ± 11.2 | 4% female | 26 | NR | EM |
| [Brøsen 1986](#5)<sup>+</sup> | 100 mg, oral, single dose | 24.1 (21-30) | NR | 50% female | 6 | NR | Fast EM |
| [Brøsen 1986](#5)<sup>+</sup> | 100 mg, oral, single dose | 28.8 (23-34) | NR | 50% female | 6 | NR | PM |
| [Brøsen 1986](#5)<sup>+</sup> | 100 mg, oral, single dose | 28.3 (21-36) | NR | 50% female | 6 | NR | EM |
| [Brøsen 1988](#5)<sup>+</sup> | 50 mg, intravenous infusion over 60 min | 23.75 (22-27) | NR | 50% female | 4 | Solution | Fast EM |
| [Brøsen 1988](#5)<sup>+</sup> | 50 mg, intravenous infusion over 60 min | 29 (24-35) | NR | 33% female | 3 | Solution | PM |
| [Brøsen 1988](#5)<sup>+</sup> | 50 mg, intravenous infusion over 60 min | 29.75 (22-37) | NR | 75% female | 4 | Solution | EM |
| [Harris 2007](#5)<sup>+</sup> | 50 mg, oral, single dose | 31.5 ± 10.8 | NR | 53% female | 17 | NR | EM |
| [Hynes 2015](#5) | 50 mg, oral, single dose | 58.3 ± 9.9 | 84.3 ± 28.5 | 55% female | 20 | NR | EM |
| [Madani 2002](#5)<sup>+</sup> | 50 mg, oral, single dose | 18-45 | NR | NR | 24 | NR | EM |
| [Nichols 2013](#5) | 50 mg, oral, single dose | 18-45 | >60 | NR | 38 | NR | EM |
| [Patroneva 2008](#5) | 50 mg, oral, single dose | 18-55 | >50 | NR | 20 | NR | EM |
| [Skinner 2003](#5) | 50 mg, oral, single dose | 42 (21-63) | 71.4 | 56% female | 16 | NR | EM |
| [Spina 1987](#5)<sup>+</sup> | 25 mg, oral, single dose | 27-51 | NR | 21% female | 8 | NR | EM |
| [Spina 1987](#5)<sup>+</sup> | 25 mg, oral, single dose | 27-51 | NR | 21% female | 6 | NR | PM |
| [Spina 1995](#5) | 100 mg, oral, single dose | 24-38 | 67-81 | Male | 6 | NR | EM |

**Table 2:**<a name="table-2"></a> Clinical desipramine concentration-time profiles used for model building and verification. \*: Single oral dose unless otherwise specified; AS: activity score; EM: extensive metabolizer; Fast EM: fast extensive metabolizer; IM: intermediate metabolizer; NM: normal metabolizer; NR: not reported; PM: poor metabolizer; PT: predicted phenotype; UM: ultrarapid metabolizer; <sup>+</sup>: data used for model building. Parenthetical PTs for AS-coded rows use the current CPIC CYP2D6 activity score-to-phenotype mapping ([Moore 2026](#5)). EM is the model default when study-specific CYP2D6 information is not available.
