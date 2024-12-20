Here are some of my past and ongoing projects, which I think are pretty cool. Not all projects are being actively developed, but I will certainly respond to issues and pull requests. 

**I am the main developer for** (more recent projects are listed first):

+ [sweepy](https://github.com/biona001/sweepy): Python package implementing the statistical sweep operation
+ [RootCauseDiscovery](https://github.com/Jinzhou-Li/RootCauseDiscovery): Python and Julia package for detecting disease-causing genes in rare disease patients from gene expression data
+ [GhostKnockoffGWAS](https://github.com/biona001/GhostKnockoffGWAS): Package for performing knockoff-based analysis for GWAS summary statistics data
+ [Ghostbasil.jl](https://github.com/biona001/Ghostbasil.jl): (WIP) Provides Julia wrappers to the C++ code of [ghostbasil](https://github.com/JamesYang007/ghostbasil)
+ [Knockoffs.jl](https://github.com/biona001/Knockoffs.jl): Implements the knockoff filter framework for variable selection, which performs conditional independence testing and controls the FDR (false discovery rate)
+ [groupknockoffs](https://github.com/biona001/groupknockoff): Simple app to solve group knockoff optimization, without Julia installed!
+ [EasyLD.jl](https://github.com/biona001/EasyLD.jl): Julia utilities for downloading and reading LD (linkage disequilibrium) matrices stored in Hail's `BlockMatrix` format
+ [knockoffspy](https://github.com/biona001/knockoffspy): A Python package that provides a direct wrapper over [Knockoffs.jl](https://github.com/biona001/Knockoffs.jl)
+ [knockoffsr](https://github.com/biona001/knockoffsr): A R package that provides a direct wrapper over [Knockoffs.jl](https://github.com/biona001/Knockoffs.jl)
+ [MendelIHT.jl](https://github.com/OpenMendel/MendelIHT.jl): Implements iterative hard thresholding (l0 penalized regression solver). It is highly optimized for handling compressed (binary PLINK) genotype data
+ [MendelImpute.jl](https://github.com/OpenMendel/MendelImpute.jl): A package for genotype imputation, phasing, and (global/local) ancestry inference utilizing a reference haplotype panel. It is significantly faster than existing methods but slightly less accurate
+ [Thyrosim.jl](https://github.com/biona001/Thyrosim.jl): An updated version of [THYROSIM](http://biocyb1.cs.ucla.edu/thyrosim/cgi-bin/Thyrosim.cgi), `Thyrosim.jl` produces individualized thyroid hormone predictions (TT4/TT3/TSH) based on a rather complicated ODE model
+ [VCFTools.jl](https://github.com/OpenMendel/VCFTools.jl): Julia utilities for handling VCF (Variant Call Format) files
+ [fastPHASE.jl](https://github.com/biona001/fastPHASE.jl): Julia wrapper for the famous [fastPHASE](https://stephenslab.uchicago.edu/software.html#fastphase) genetics software. The primary use case is to allow the original program to run on binary PLINK data.

**I am a contributor for** (at least 5 commits):

+ [bge_analysis](https://github.com/atgu/bge_analysis): Python, R, and Julia code for imputation and quality control scripts used for the blended genome-exome (BGE) data. 
+ [QuasiCopula.jl](https://github.com/OpenMendel/QuasiCopula.jl): Implements a new class of distribution (Quasi-Copulas) that captures correlation among non-Gaussian random variables efficiently
+ [SnpArrays.jl](https://github.com/OpenMendel/SnpArrays.jl): Julia package for handling binary PLINK formatted data. It has the **fastest** (matrix)-(vector) multiplication routine for compressed PLINK files as far as I know.
+ [MendelKinship.jl](https://github.com/OpenMendel/MendelKinship.jl): Calculates various empirical and theoretical kinship coefficients, based on pedigree or genotype data.

I enjoy sharing my knowledge with others, so here are a few tutorials I made:

+ [Interfacing Julia with R/Python/C++](https://github.com/biona001/teaching/blob/master/2024_julia_in_pyRCpp/slides.pdf) (as of early 2024)
+ [A general introduction to Julia](https://github.com/biona001/teaching/blob/master/2022_Julia_tutorial/5.12.2022.julia.ipynb) (2022 version)
+ [A tutorial for multithreading and parallel computation in Julia](https://htmlpreview.github.io/?https://github.com/biona001/teaching/blob/master/Julia_multithreading_gotchas/multithreading_tutorial.html).
+ [Some notes on random graph theory](https://github.com/biona001/teaching/blob/master/preceptorship%20-%20biomath%20203%20/random%20graph%20theory/lecture.pdf), presented in Biomath 203 at UCLA (2020)
+ [A tutorial to imputation and phasing using MendelImpute.jl](https://htmlpreview.github.io/?https://github.com/OpenMendel/ASHG-OpenMendelWorkshop-2020-Oct/blob/master/07-Impute-Chu/MendelImpute_Tutorial.html) presented at [2020 ASHG meeting](https://learning.ashg.org/products/workshop-julia-meets-mendel-algorithms-and-software-for-modern-genomic-data-analysis) (see [homepage](https://github.com/OpenMendel/Tutorials)).
+ [A tutorial to iterative hard threhsolding (IHT)](https://openmendel.github.io/LangeSymposium-ProgrammingWorkshop-20202022/05-iht/MendelIHT_tutorial.html) presented in the [2020 Lange Symposium](https://github.com/OpenMendel/LangeSymposium-ProgrammingWorkshop-20202022?tab=readme-ov-file).
