![$\mathcal{H}$-Matrices](https://img.shields.io/badge/H-Matrices-green.svg "H-Matrices")

Curated list of [Hierarchical Matrices](http://en.wikipedia.org/wiki/Hierarchical_matrix) ($\mathcal{H}$-Matrices) libraries (by language) and papers (by year). Inspired by the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

***

## C

### [HiCMA](https://github.com/ecrc/hicma) Hatem Ltaief, Kadir Akbudak (King Abdullah University of Science and Technology)
- Open source
- Hierarchical format: $\mathcal{H}$

### [Hlib](http://hlib.org/) Lars Grasedyck and Steffen Börm (Leipzig, Max Planck Institute)
- Source code available through signed license agreement.
- Hierarchical format: $\mathcal{H}$ and $\mathcal{H}^2$

### [H2Lib](http://www.h2lib.org/) Steffen Boerm, Knut Reimer, Dirk Boysen, Sven Christophersen, Nadine Albrecht, and Jens Burmeister.  (University of Kiel)
- Open source
- Hierarchical format: $\mathcal{H}$ and $\mathcal{H}^2$

## C++

### [HLIBpro](http://www.hlibpro.com) Ronald Kriemann (Leipzig, Max Planck Institute)
- Binary files only, distributed memory implementation on MPI, on shared memory based on TBB
- Hierarchical format: $\mathcal{H}$ and $\mathcal{H}^2$

### [AHMED](https://github.com/xantares/ahmed) Mario Bebendorf and Sergej Rjasanow (University of Bonn) 
- Source code available through online license agreement.
- Hierarchical format: $\mathcal{H}$

### [BBFMM3D](https://github.com/ruoxi-wang/BBFMM3D) W. Fong, and E. Darve (Stanford University)
- Black-box fast multipole method for general kernels. The FMM is based on Chebyshev and Fourier interpolation methods.

### [BEM++](https://github.com/bempp/bempp) W. Smigaj, S. Arridge, T. Betcke, J. Phillips, M. Schweiger (University College London)
- Boundary Integral Problems with BEM++, accelerated by $\mathcal{H}$-Matrices

### [DMHM](https://github.com/YingzhouLi/dmhm) Jack Poulson and Ryan Li (Stanford University and Georgia Tech) 
- Open source
- Hierarchical format: $\mathcal{H}$

### [STRUMPACK](http://portal.nersc.gov/project/sparse/strumpack/) X. Sherry Li, Pieter Ghysels, Gustavo Chávez, Yang Liu (Lawrence Berkeley National Laboratory)
- Open source
- Hierarchical format: HSS, HOLDR, BLR 

### [Dense_HODLR](https://github.com/amiraa127/Dense_HODLR) Amirhossein Aminfar (Stanford University)
- Open source
- Hierarchical format: HODLR

### [Structured CHOLMOD](https://github.com/jeffchadwick/rank_structured_cholesky/tree/master/src) David Bindel (Cornell University)
- Open source

### [LoRaSp](https://bitbucket.org/hadip/lorasp) Hadi Pouransari and Eric Darve (Stanford University)
- Hierarchical format: $\mathcal{H}^2$
- A revised version of LORASP with additional options and a more modular software design

### [RLCM](https://github.com/jiechenjiechen/RLCM) Jie Chen (IBM)
- linear complexity assembly
- sub-linear complexity solves: $O(n)$ many solves in $O(n \log(n))$ complexity

## CUDA
### [hmglib](https://github.com/zaspel/hmglib) Peter Zaspel (University of Basel)
- Open source
- Hierarchical format: $\mathcal{H}$

## Matlab
### [Misc](http://amath.colorado.edu/faculty/martinss/2014_CBMS/codes.html) Per-Gunnar Martinsson (University of Colorado Boulder) 
- Various scripts, Randomized SVD, Interpolative decomposition, Multi-frontal solvers.
- Hierarchical format: S, HSS

### [HSS](http://www.math.purdue.edu/~xiaj/) 	Jianlin Xia (Purdue University)
- Hierarchically SemiSeparable package
- Hierarchical format: HSS

### [RSVDPACK](https://github.com/sergeyvoronin/LowRankSVDCodes) Sergey Voronin and Per-Gunnar Martinsson (University of Colorado Boulder) 
- Randomized SVD on GPU
- C and Matlab codes

### [HMat](https://github.com/YingzhouLi/HMat) Haizhao Yang and Yingzhou Li (Duke University and Stanford University)
- Hierarchical Matrices in Julia and Matlab 
- Matlab library for many types of structured matrices


## Fortran
### [SSS_Toeplitz](http://www.math.purdue.edu/~xiaj/frameright.html) Jianlin Xia and J. Zhu (Purdue University) 
- Superfast SSS Toeplitz solver
- Hierarchical format: HSS

### [HACApK](https://github.com/hoshino-UTokyo/hacapk-gpu) Akihiro Ida (The University of Tokyo) 
- Lattice H-matrices
- Hierarchical format: $\mathcal{H}$



## Python
### [H2Tools](https://bitbucket.org/muxas/h2tools) Alexander Mikhalev (KAUST / Russian Academy of Sciences) 
- Open source
- Hierarchical format: $\mathcal{H}^2$

## Julia
### [KernelMatrices.jl](https://bitbucket.org/cgeoga/kernelmatrices.jl.git) Chris Geoga (Argonne National Laboratory)
- HODLR matrices with ACA or Nystrom approximation for off-diagonal blocks
- First and second derivatives of kernel matrices that are continuous with respect to kernel parameters

### [HssMatrices.jl](https://github.com/bonevbs/HssMatrices.jl) Boris Bonev (EPFL)
- library for HSS matrices in Julia
- various compression algorithms, fast solvers and multiplication, as well as visualization tools

### [HMatrices.jl](https://github.com/WaveProp/HMatrices.jl) Luiz M. Faria (INRIA)
- $\mathcal{H}$ hierarchical format with support for $\mathcal{H}$-LU factorization
- Focus on applications to boundary integral equation methods

***
## Woud you like to add a new library or update a link?
Please open a pull request, contributions to this repository are most welcome.

