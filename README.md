# 2database

A collection of two-dimensional (2D) halide perovskite structures, used in a variety of works studying the chirality and dynamics of 2D perovskites. Among others, these structures were used to:
1. Explore the structural chirality of 2D halide perovskites at <i>T</i> = 0K and at finite temperatures. [DOI: [`10.1021/acs.jpclett.4c01629`](https://doi.org/10.1021/acs.jpclett.4c01629)]
2. Discover chiral phonons in chiral 2D halide perovskites [DOI: [`10.1021/acs.nanolett.5c01708`](https://doi.org/10.1021/acs.nanolett.5c01708)]
3. Investigate the effect of metal cations on the structural and dynamic chirality of 2D halide perovskites [DOI: [`10.1103/mxyl-tqjb`](https://doi.org/10.1103/mxyl-tqjb)]

## Computational settings

The experimental structures were optimized using density functional theory (DFT) calculations. These DFT calculations were performed in the Vienna Ab-initio Simulation Package (VASP) [1-3]. The electron-electron exchange correlation (XC) interactions were modelled using a variety of XC functionals: PBE [4], PBE+D3 [5], PBE+D3(BJ) [6], PBEsol [7], and SCAN [8]. The projector-augmented wave (PAW) pseudopotentials [9] treated the following electrons: H (1s<sup>1</sup>), C (2s<sup>2</sup>2p<sup>2</sup>), N (2s<sup>2</sup>2p<sup>3</sup>), O (2s<sup>2</sup>2p<sup>4</sup>), Br (4s<sup>2</sup>4p<sup>5</sup>), I (5s<sup>2</sup>5p<sup>5</sup>), Pb (6s<sup>2</sup>6p<sup>2</sup>) as valence electrons. The cutoff energy for the plane wave basis set was set to 500 eV in all calculations, combined with convergence criteria for the energies and forces of 10<sup>-5</sup> eV and 10<sup>-2</sup> eV/Å, respectively. The reciprocal space was sampled using Γ-centered <i>k</i>-meshes [10]. In optimizing the experimental crystal structures all atomic positions, the cell shape and cell volume were allowed to change.

## Experimental structures

Below is a list of the papers from which the experimental structures used as starting point for the structural optimizations are from. For every 2D perovskite, the number behind the structure references the CCDC (Cambridge Crystallographic Data Centre) number from the crystallographic database.

- M.K. Jana *et al.*, *Nat. Commun.*, 11, 4699 (2020), DOI: [`10.1038/s41467-020-18485-7`](https://doi.org/10.1038/s41467-020-18485-7).
	- (<i>S</i>-MBA)<sub>2</sub>PbI<sub>4</sub> [[CCDC:2015617](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2015617)]
	- (<i>R</i>-MBA)<sub>2</sub>PbI<sub>4</sub> [Mirror of (<i>S</i>-MBA)<sub>2</sub>PbI<sub>4</sub>]
	- (<i>S</i>-1NEA)<sub>2</sub>PbBr<sub>4</sub> [[CCDC:2015618](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2015618)]
	- (<i>R</i>-1NEA)<sub>2</sub>PbBr<sub>4</sub> [[CCDC:2015620](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2015620)]
	- (<i>rac</i>-1NEA)<sub>2</sub>PbBr<sub>4</sub> [[CCDC:2015614](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2015614)]
- H. Lu *et al.*, *J. Am. Chem. Soc.*, 142, 13030-13040 (2020), DOI: [`10.1021/jacs.0c03899`](https://doi.org/10.1021/jacs.0c03899).
	- (<i>S</i>-MBA)<sub>2</sub>SnI<sub>4</sub> [[CCDC:1994338](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=1994338)]
	- (<i>R</i>-MBA)<sub>2</sub>SnI<sub>4</sub> [[CCDC:1994337](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=1994337)]
	- (<i>rac</i>-MBA)<sub>2</sub>SnI<sub>4</sub> [[CCDC:1994336](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=1994336)]
- Y. Dang *et al.*, *J. Phys. Chem. Lett.*, 11, 1689–1696 (2020), DOI: [`10.1021/acs.jpclett.9b03718`](https://doi.org/10.1021/acs.jpclett.9b03718).
	- (<i>rac</i>-MBA)<sub>2</sub>PbI<sub>4</sub> [[CCDC:1877052](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=1877052)]
- M.K. Jana *et al.*, *Nat. Commun.*, 12, 4982 (2021), DOI: [`10.1038/s41467-021-25149-7`](https://doi.org/10.1038/s41467-021-25149-7).
	- (<i>R</i>-4-Cl-MBA)<sub>2</sub>PbBr<sub>4</sub> [[CCDC:2095482](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2095482)]
	- (<i>S</i>-1-Me-HA)<sub>2</sub>PbI<sub>4</sub> [[CCDC:2095483](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2095483)]
	- (<i>S</i>-4-NO<sub>2</sub>-MBA)<sub>2</sub>PbBr<sub>4</sub>⋅H<sub>2</sub>O [[CCDC:2095484](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2095484)]
	- (<i>S</i>-2-Me-BuA)<sub>2</sub>PbBr<sub>4</sub> [[CCDC:2095485](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2095485)]
	- (<i>S</i>-4-NH<sub>3</sub>-MBA)<sub>2</sub>PbI<sub>4</sub> [[CCDC:2095486](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2095486)]
- J. Son *et al.*, *Nat. Commun.*, 14, 3124 (2023), DOI: [`10.1038/s41467-023-38927-2`](https://doi.org/10.1038/s41467-023-38927-2).
	- (<i>S</i>-2NEA)<sub>2</sub>PbBr<sub>4</sub> [[CCDC:2178604](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2178604)]
	- (<i>R</i>-2NEA)<sub>2</sub>PbBr<sub>4</sub> [[CCDC:2178605](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2178605)]
	- (<i>rac</i>-2NEA)<sub>2</sub>PbBr<sub>4</sub> [[CCDC:2178606](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2178606)]
- K.Z. Du *et al.*, *Inorg. Chem.*, 56, 9291–9302 (2017), DOI: [`10.1021/acs.inorgchem.7b01094`](https://doi.org/10.1021/acs.inorgchem.7b01094).
	- PEA<sub>2</sub>PbI<sub>4</sub> [[CCDC:1542461](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=1542461)]
- M. Menahem *et al.*, *ACS Nano*, 15, 10153–10162 (2021), DOI: [`10.1021/acsnano.1c02022`](https://doi.org/10.1021/acsnano.1c02022).
	- BA<sub>2</sub>PbI<sub>4</sub> [[CCDC:2018893](https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=2018893)]

## Usage

The structures can be freely used, however, it is greatly encouraged to reference the experimental work these structures were taken from.

## References

1. Kresse *et al.*, *Phys. Rev. B*, 49, 14251 (1994) , DOI: [`10.1103/PhysRevB.49.14251`](https://doi.org/10.1103/PhysRevB.49.14251).
2. Kresse *et al.*, *Comput. Mater. Sci.*, 6, 15-50 (1996) , DOI: [`10.1016/0927-0256(96)00008-0`](https://doi.org/10.1016/0927-0256(96)00008-0).
3. Kresse *et al.*, *Phys. Rev. B*, 54, 11169 (1996) , DOI: [`10.1103/PhysRevB.54.11169`](https://doi.org/10.1103/PhysRevB.54.11169).
4. J.P. Perdew *et al.*, *Phys. Rev. Lett.*, 77, 3865 (1996) , DOI: [`10.1103/PhysRevLett.77.3865`](https://doi.org/10.1103/PhysRevLett.77.3865).
5. S. Grimme *et al.*, *J. Comput. Chem.*, 32, 1456-1465 (2011) , DOI: [`10.1002/jcc.21759`](https://doi.org/10.1002/jcc.21759).
6. S. Grimme *et al.*, *J. Chem. Phys.*, 132, 154104 (2010) , DOI: [`10.1063/1.3382344`](https://doi.org/10.1063/1.3382344).
7. J.P. Perdew *et al.*, *Phys. Rev. Lett.*, 100, 136406 (2008) , DOI: [`10.1103/PhysRevLett.100.136406`](https://doi.org/10.1103/PhysRevLett.100.136406).
8. J. Sun. *et al.*, *Phys. Rev. Lett.*, 115, 036402 (2015) , DOI: [`10.1103/PhysRevLett.115.036402`](https://doi.org/10.1103/PhysRevLett.115.036402).
9. Kresse *et al.*, *Phys. Rev. B*, 59, 1758 (1999) , DOI: [`10.1103/PhysRevLett.115.036402`](https://doi.org/10.1103/PhysRevLett.115.036402).
10. H.J. Monkhorst *et al.*, *Phys. Rev. B*, 13, 5188 (1976) , DOI: [`10.1103/PhysRevB.13.5188`](https://doi.org/10.1103/PhysRevB.13.5188).
