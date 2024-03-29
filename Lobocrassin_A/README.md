# Lobocrassin A

The [automated structure elucidation of Lobocrassin A](https://www.acdlabs.com/comm/elucidation/2022_03.php)
was presented in April 2022 by the [ACD/Labs](https://www.acdlabs.com) company.
Original data may be found from Marine Drugs 2011, 9, 1319-1331; doi:10.3390/md9081319.

A try was given to [PyLSD](https://nuzillard.github.io/PyLSD) using the data that were made publicly available by ACD/Labs.

The structure elucidation problem is coded in the lobocrassinA.lsd file.

The resolution is almost instantaneous and produces 120 solutions.
The production of the only structures that fit with the cembrane substructure leads to 81 solutions.

The result of the automatic drawing of solution structures by pyLSD being a bit messy,
the SDF file of the solutions was converted to SMILES (one per line, in file lobocrassinA.smi)
using the [Open Babel GUI](https://openbabel.org/docs/current/GUI/GUI.html)
and then depicted again using [CDK Depict](https://www.simolecule.com/cdkdepict/depict.html).

The correct structure of Lobocrassin A, in file lobocrassinA.png, was ranked at the first place,
but without any defined configuration at double bonds and asymmetric centers.
Ranking is carried out using [nmrshiftdb2](https://nmrshiftdb.nmr.uni-koeln.de/nmrshiftdb/).
The average <sup>13</sup>C NMR chemical shift prediction error for the correct solution is 2.24 ppm.

Another structure of a cembrane diterpene was reported using the LSD software 
([free download](http://bbp4b.litbang.kkp.go.id/squalen-bulletin/index.php/squalen/article/view/177/pdf)).
