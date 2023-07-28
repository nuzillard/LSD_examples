# Plebeianiol A

The [automated structure elucidation of Plebeianiol A](https://www.acdlabs.com/blog/plebeianiol-a)
was presented in June 2023 by Mikhail Elyashberg, [ACD/Labs](https://www.acdlabs.com) company.

Original data may be found [here](https://doi.org/10.3390/molecules200814879).

The proposed structure was later revised [here](https://doi.org/10.1021/acs.orglett.1c03791).

The structure elucidation problem is coded in the plebeianiolA.lsd file.
Because the <sup>13</sup>C NMR spectrum of plebeianiol A shows 6 aromatic carbons, all being quaternary but one,
a penta-substituted six-membered aromatic ring was imposed to be present in the solutions.

The resolution is almost instantaneous and produces 912 structures, with possible assignment isomers.
Ranking is carried out using [nmrshiftdb2](https://nmrshiftdb.nmr.uni-koeln.de/nmrshiftdb/).

The result of the automatic drawing of solution structures by pyLSD being a bit messy,
they were converted to SMILES (one per line, in file plebeianiolA.smi)
and then depicted using [CDK Depict](https://www.simolecule.com/cdkdepict/depict.html).

The file First_3_solutions.png shows the first three structures, after ranking.
The first two ones are identical but differ in <sup>13</sup>C NMR spectrum assignment.
The correct structure of plebeianiol A was ranked at the *third* place;
the corresponding assignment is shown in file Structure_with_assignment.png.

The average <sup>13</sup>C NMR chemical shift prediction error for the correct solution is 3.480 ppm.
The error for the structures ranked at the first and second places is 3.405 ppm.
