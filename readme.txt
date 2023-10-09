************FSU EFFECTIVE NUCLEAR SHELL MODEL INTERACTION***********
This effective nucleon-nucleon interaction is distributed under the terms of the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license, 
https://creativecommons.org/licenses/by-nc-sa/4.0/

Please refer to publications: 
R. S. Lubna, et al.  Phys. Rev. Research 2, 043342 (2020)
R. S. Lubna, et al. Phys. Rev. C 100, 034308 (2019)
R. S. Lubna, Ph.D. thesis, Florida State University (Summer 2019)

This material is based upon work supported by the U.S. Department of Energy Office of Science, Office of Nuclear Physics under Grant No. DE-SC0009883

This data is presented in *.int format, see Nuclear Structure Shell Model Code OXBASH https://arxiv.org/abs/nucl-th/9406020 and OXBASH manual. 

As discussed in the above references full implementation requires additional components see E. K. Warburton and B. A. Brown, Phys. Rev. C 46 (1992) 923. 
-spsdpfpb.int
-0s0f1p0.int
-spsdpfcm.int (center-of-mass term as needed)


Benchmark calculation
The following example of 27Ne calculation is provided for benchmarking.
 
------------HAMILTONIAN--------
Reading Interactions from: spsdpfpb.int
Single-particle levels    :10 scale: 1 
Lines in interaction file :140 scale: 1 
Reading Interactions from: spsdfp-fsu9.int
Single-particle levels    :10 scale: 1 
Lines in interaction file :768 scale: 0.885467 
Reading Interactions from: 0p1sd.int
Single-particle levels    :10 scale: 1 
Lines in interaction file :12 scale: 1 
Reading Interactions from: 0p3sd.int
Single-particle levels    :10 scale: 1 
Lines in interaction file :20 scale: 1 
Reading Interactions from: 0s0f1p0.int
Single-particle levels    :10 scale: 1 
Lines in interaction file :1400 scale: 1 
Reading Interactions from: spsdpfcm.int
Single-particle levels    :10 scale: 10 
Lines in interaction file :452 scale: 10 

----------BASIS STATES---------
0hw Jz=1/2 parity + 1935
1hw Jz=1/2 parity - 116736

----------Energies--------------
3/2+(1) T=7/2 0 -227.544
3/2-(1) T=7/2 0.863 -226.681
1/2+(1) T=7/2 1.385 -226.159
7/2-(1) T=7/2 1.639 -225.905
1/2-(1) T=7/2 1.888 -225.656
7/2+(1) T=7/2 1.9 -225.644
5/2+(1) T=7/2 2.045 -225.499
1/2+(2) T=7/2 2.813 -224.731
3/2+(2) T=7/2 2.887 -224.657
5/2+(2) T=7/2 2.917 -224.627
5/2-(1) T=7/2 3.184 -224.36
11/2+(1) T=7/2 3.222 -224.322
5/2+(3) T=7/2 3.235 -224.309
11/2-(1) T=7/2 3.405 -224.139

Excitation energies of 0hw states should agree with USDB interaction, see Phys. Rev. C74, 034315 (2006). 
