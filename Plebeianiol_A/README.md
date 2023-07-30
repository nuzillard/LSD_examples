# Plebeianiol A

The [automated structure elucidation of Plebeianiol A](https://www.acdlabs.com/blog/plebeianiol-a)
was presented in June 2023 by Mikhail Elyashberg, [ACD/Labs](https://www.acdlabs.com) company.

Original data may be found [here](https://doi.org/10.3390/molecules200814879).

The proposed structure was later revised [here](https://doi.org/10.1021/acs.orglett.1c03791).

The structure elucidation problem is coded for [pyLSD](https://nuzillard.github.io/PyLSD/) in the
[plebeianiolA.lsd](https://github.com/nuzillard/LSD_examples/blob/master/Plebeianiol_A/plebeianiolA.lsd) file.
Because the <sup>13</sup>C NMR spectrum of plebeianiol A shows 6 aromatic carbons, all being quaternary but one,
a penta-substituted six-membered aromatic ring was imposed to be present in the solutions.

The resolution by [pyLSD](https://nuzillard.github.io/PyLSD/) is almost instantaneous and produces 912 structures, with possible assignment isomers.
Ranking is carried out using [nmrshiftdb2](https://nmrshiftdb.nmr.uni-koeln.de/nmrshiftdb/).

The result of the automatic drawing of solution structures by pyLSD being a bit messy,
they were converted to SMILES (one per line, in file plebeianiolA.smi)
and then depicted using [CDK Depict](https://www.simolecule.com/cdkdepict/depict.html).

The file [First_3_solutions.png](https://github.com/nuzillard/LSD_examples/blob/master/Plebeianiol_A/First_3_solutions.png)
shows the first three structures produced by pyLSD, after ranking.
The first two ones are identical but differ in <sup>13</sup>C NMR spectrum assignment.
The correct structure of plebeianiol A, as determined after revision, was ranked at the *third* place;
the corresponding assignment is shown in file
[Structure_with_assignment.png](https://github.com/nuzillard/LSD_examples/blob/master/Plebeianiol_A/Structure_with_assignment.png).

The average <sup>13</sup>C NMR chemical shift prediction error for the correct solution is 3.480 ppm.
The error for the structures ranked at the first and second places is 3.405 ppm.

The admitted structure of plebeianiol A, proved by chemical synthesis,
has an assignment problem with the possible permutations of the carbons at 126.3 and 131.9 ppm.
In one permutation, the prediction of chemical shifts is hardly compatible with the experimental values
and in the other permutation, one has to consider the existence of very long range HMBC correlations
while shorter range ones are not visible.
The origin of these contradictory observations may arise from unreliably published NMR data.

The difficulty of dealing with NMR data as they are generally reported in journals 
is that there is no way to access the original raw data and spectra.
The importance of preserving and making raw NMR data publicly available is illustrated
[here](https://pubs.rsc.org/en/content/articlelanding/2019/np/c7np00064b).

