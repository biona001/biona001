### Hi there 👋

Here are some of my past and ongoing projects, which I think are pretty cool. Not all projects are being actively developed, but I will certainly respond to issues and pull requests. 

**I am the main developer for** (more recent projects are listed first):

+ [Knockoffs.jl](https://github.com/biona001/Knockoffs.jl): Implements the knockoff filter framework for variable selection, which performs conditional independence testing and controls the FDR (false discovery rate)
+ [GhostKnockoffGWAS.jl](https://github.com/biona001/GhostKnockoffGWAS): Package for performing knockoff-based canalysis for GWAS summary statistics data
+ [EasyLD.jl](https://github.com/biona001/EasyLD.jl): Julia utilities for downloading and reading LD (linkage disequilibrium) matrices stored in Hail's `BlockMatrix` format
+ [knockoffspy](https://github.com/biona001/knockoffspy): A Python package that provides a direct wrapper over [Knockoffs.jl](https://github.com/biona001/Knockoffs.jl)
+ [knockoffsr](https://github.com/biona001/knockoffsr): A R package that provides a direct wrapper over [Knockoffs.jl](https://github.com/biona001/Knockoffs.jl)
+ [MendelIHT.jl](https://github.com/OpenMendel/MendelIHT.jl): Implements iterative hard thresholding (l0 penalized regression solver). It is highly optimized for handling compressed (binary PLINK) genotype data
+ [MendelImpute.jl](https://github.com/OpenMendel/MendelImpute.jl): A package for genotype imputation, phasing, and (global/local) ancestry inference utilizing a reference haplotype panel. It is significantly faster than existing methods but slightly less accurate
+ [Thyrosim.jl](https://github.com/biona001/Thyrosim.jl): An updated version of [THYROSIM](http://biocyb1.cs.ucla.edu/thyrosim/cgi-bin/Thyrosim.cgi), `Thyrosim.jl` produces individualized thyroid hormone predictions (TT4/TT3/TSH) based on a rather complicated ODE model
+ [VCFTools.jl](https://github.com/OpenMendel/VCFTools.jl): Julia utilities for handling VCF (Variant Call Format) files
+ [fastPHASE.jl](https://github.com/biona001/fastPHASE.jl): Julia wrapper for the famous [fastPHASE](https://stephenslab.uchicago.edu/software.html#fastphase) genetics software. The primary use case is to allow the original program to run on binary PLINK data. 


**I am a contributor for** (at least 5 commits):

+ [QuasiCopula.jl](https://github.com/OpenMendel/QuasiCopula.jl): Implements a new class of distribution (Quasi-Copulas) that captures correlation among non-Gaussian random variables efficiently
+ [SnpArrays.jl](https://github.com/OpenMendel/SnpArrays.jl): Julia package for handling binary PLINK formatted data. It has the **fastest** (matrix)-(vector) multiplication routine for compressed PLINK files as far as I know.
+ [MendelKinship.jl](https://github.com/OpenMendel/MendelKinship.jl): Calculates various empirical and theoretical kinship coefficients, based on pedigree or genotype data.
