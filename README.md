<!-- badges: start -->
[![CRAN Downloads](https://cranlogs.r-pkg.org/badges/grand-total/seq2R)](https://cran.r-project.org/package=seq2R)
[![CRAN status](https://www.r-pkg.org/badges/version/seq2R)](https://cran.r-project.org/package=seq2R)
<!-- badges: end -->

# seq2R
Simple Method to Detect Compositional Changes in Genomic

## Description
This software is useful for loading '.fasta' or '.gbk' files, and for retrieving sequences from 'GenBank' dataset <https://www.ncbi.nlm.nih.gov/genbank/>. This package allows  to detect differences or asymmetries based on nucleotide composition by using local linear kernel smoothers. Also, it is possible to draw inference about critical points (i. e. maximum or minimum points) related with the derivative curves. Additionally, bootstrap methods have been used  for estimating confidence intervals and speed computational techniques (binning techniques) have been implemented in 'seq2R'.

The full methodology of the method to detect changes points in DNA sequences is 
published in the following paper:
> Villanueva, N.M., Sestelo, M., Fonseca, M.M. & Roca-Pardinas, J._seq2R: an R package to detect change points in DNA sequences_. Mathematics 11, pages 2299 (2023). https://doi.org/10.3390/math11102299


## Installation 

```seq2R```` is available through both [CRAN](https://cran.r-project.org/) and Github
If you want to use the release version of the package, you can install the package from CRAN as follows:
```
install.packages(pkgs="seq2R");
```


Or the development version from GitHub:
```
# install.packages("devtools")
devtools::install_github("noramvillanueva/seq2R")
```

## Citation

```
@article{villanueva2023,
author = {Villanueva, Nora M. and Sestelo, Marta, Fonseca, Miguel M. and Roca-Pardinas, Javier},
doi = {10.3390/math11102299},
issn = {2227-7390},
journal = {Mathematics},
number = {10},
pages = {6},
title = {{seq2R: An R Package to Detect Change Points in DNA Sequences}},
url = {https://doi.org/10.3390/math11102299},
volume = {11},
year = {2023}
}
``` 