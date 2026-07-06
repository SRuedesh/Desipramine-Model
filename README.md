# Desipramine-Model
Whole-body parent-metabolite PBPK model of desipramine and 2-hydroxydesipramine including CYP2D6 drug-drug-gene interactions.

This repository contains the desipramine model originally published by Rüdesheim et al. [[1](#references)].

The model was developed and evaluated using published clinical plasma pharmacokinetic data after intravenous or oral desipramine administration by Brøsen et al. [[2](#references), [14](#references)], Spina et al. [[3](#references), [15](#references)], Aarnoutse et al. [[4](#references)], Boni et al. [[5](#references)], Harris et al. [[6](#references)], Madani et al. [[7](#references)], Bergstrom et al. [[8](#references)], Bergmann et al. [[9](#references)], Hynes et al. [[10](#references)], Nichols et al. [[11](#references)], Patroneva et al. [[12](#references)] and Skinner et al. [[13](#references)].

Users of the model are expected to cite this study when using the model in scientific work, reports or derivative model development:
- [S Rüdesheim, H L H Loer, D Feick, F Z Marok, L M Fuhr, D Selzer, D Teutonico, A R P Schneider, J Solodenko, S Frechen, M van der Lee, D J A R Moes, J J Swen, M Schwab, T Lehr. A Comprehensive CYP2D6 Drug-Drug-Gene Interaction Network for Application in Precision Dosing and Drug Development. Clin Pharmacol Ther, 2025.](https://pubmed.ncbi.nlm.nih.gov/39953671/)

This desipramine model is intended to describe CYP2D6-mediated desipramine and 2-hydroxydesipramine pharmacokinetics and to support CYP2D6 drug-drug-gene interaction simulations.

The presented model includes the following features:

- metabolism by CYP2D6,
- formation of 2-hydroxydesipramine,
- residual hepatic clearance,
- renal filtration,
- CYP2D6 activity-score-dependent clearance.

## Repository files
This repository contains:

- a [PK-Sim snapshot (*.json) file](https://docs.open-systems-pharmacology.org/working-with-pk-sim/pk-sim-documentation/importing-exporting-project-data-models#exporting-project-to-snapshot-loading-project-from-snapshot) of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation_plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found in the [latest release in this repository](./releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found in the [latest OSP PBPK Model Library release](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases/latest).**

## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References
[1] [S Rüdesheim, H L H Loer, D Feick, F Z Marok, L M Fuhr, D Selzer, D Teutonico, A R P Schneider, J Solodenko, S Frechen, M van der Lee, D J A R Moes, J J Swen, M Schwab, T Lehr. A Comprehensive CYP2D6 Drug-Drug-Gene Interaction Network for Application in Precision Dosing and Drug Development. Clin Pharmacol Ther, 2025.](https://pubmed.ncbi.nlm.nih.gov/39953671/)

[2] [K Brøsen, L F Gram. First-pass metabolism of imipramine and desipramine: impact of the sparteine oxidation phenotype. Clin Pharmacol Ther, 1988;43:400-406.](https://doi.org/10.1038/clpt.1988.50)

[3] [E Spina, E Steiner, Ö Ericsson, F Sjöqvist. Hydroxylation of desmethylimipramine: dependence on the debrisoquin hydroxylation phenotype. Clin Pharmacol Ther, 1987;41:314-319.](https://doi.org/10.1038/clpt.1987.33)

[4] [R E Aarnoutse, J Kleinnijenhuis, P P Koopmans, D J Touw, J Wieling, Y A Hekster, D M Burger. Effect of low-dose ritonavir on CYP2D6 activity in healthy volunteers. Clin Pharmacol Ther, 2005;78:664-674.](https://doi.org/10.1016/j.clpt.2005.09.001)

[5] [J Boni, R Abbas, C Leister, J Burns, R Jordan, M Hoffmann, W DeMaio, B Hug. Disposition of desipramine when coadministered with intravenous temsirolimus. Cancer Chemother Pharmacol, 2009;64:263-270.](https://doi.org/10.1007/s00280-008-0865-9)

[6] [R Z Harris, M Salfi, E Posvar, D Hoelscher, D Padhi. Pharmacokinetics of desipramine HCl when administered with cinacalcet HCl. Eur J Clin Pharmacol, 2007;63:159-163.](https://doi.org/10.1007/s00228-006-0129-8)

[7] [S Madani, D Barilla, J Cramer, Y Wang, C Paul. Effect of terbinafine on desipramine pharmacokinetics and pharmacodynamics. J Clin Pharmacol, 2002;42:1211-1218.](https://doi.org/10.1177/009127002762491299)

[8] [R F Bergstrom, A L Peyton, L Lemberger. Quantification and mechanism of the fluoxetine and tricyclic antidepressant interaction. Clin Pharmacol Ther, 1992;51:239-248.](https://doi.org/10.1038/clpt.1992.18)

[9] [T K Bergmann, L Bathum, K Brøsen. Duplication of CYP2D6 predicts high clearance of desipramine. Eur J Clin Pharmacol, 2001;57:123-127.](https://doi.org/10.1007/s002280100284)

[10] [S M Hynes, E Wickremsinhe, W Zhang, R Decker, J Ott, J Chandler, M Mitchell. Evaluation of LY2603618 to inhibit CYP2D6 with desipramine as probe substrate. Biopharm Drug Dispos, 2015;36:49-63.](https://doi.org/10.1002/bdd.1922)

[11] [A I Nichols, Y Chen, J A Behrle, G Frick, J Paul. Effects of desvenlafaxine on the pharmacokinetics of desipramine in healthy adults. Int Clin Psychopharmacol, 2013;28:99-105.](https://doi.org/10.1097/YIC.0b013e32835c1f49)

[12] [A Patroneva, S M Connolly, P Fatato, R Pedersen, Q Jiang, J Paul, C Guico-Pabia, J A Isler, M E Burczynski, A I Nichols. Effect of desvenlafaxine and duloxetine on desipramine pharmacokinetics. Drug Metab Dispos, 2008;36:2484-2491.](https://doi.org/10.1124/dmd.108.021527)

[13] [M H Skinner, H Y Kuan, A Pan, K Sathirakul, M P Knadler, C R Gonzales, K P Yeo, S Reddy, M Lim, M Ayan-Oshodi, S D Wise. Duloxetine is both an inhibitor and a substrate of CYP2D6. Clin Pharmacol Ther, 2003;73:170-177.](https://doi.org/10.1067/mcp.2003.28)

[14] [K Brøsen, S V Otton, L F Gram. Imipramine demethylation and hydroxylation: impact of the sparteine oxidation phenotype. Clin Pharmacol Ther, 1986;40:543-549.](https://doi.org/10.1038/clpt.1986.221)

[15] [E Spina, A Avenoso, G M Campo, A P Caputi, E Perucca. The effect of carbamazepine on the 2-hydroxylation of desipramine. Psychopharmacology, 1995;117:413-416.](https://doi.org/10.1007/BF02246212)
