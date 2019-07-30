fcScan
======

fcScan is a Bioconductor package aiming at clustering genomic features based on a defined window size and combination of sites.

Dependencies
-----------

The below R packages are required for installation:

+ stats
+ utils
+ VariantAnnotation
+ SummarizedExperiment
+ rtracklayer
+ GenomicRanges
+ IRanges

Installation
------------

1. Git clone the project directory `git clone https://github.com/pkhoueiry/fcScan.git`
2. From the terminal run `R CMD build fcScan`
<<<<<<< HEAD
3. Run `R CMD check fcScan_0.99.3.tar.gz`
4. Run  `R CMD BiocCheck fcScan_0.99.3.tar.gz`
5. Install package by `R CMD INSTALL fcScan_0.99.3.tar.gz`
=======
3. Run `R CMD check fcScan_0.99.2.tar.gz`
4. Run  `R CMD BiocCheck fcScan_0.99.2.tar.gz`
5. Install package by `R CMD INSTALL fcScan_0.99.2.tar.gz`
>>>>>>> 7e9d876e3e2b2783540c15cb83dd738723ffac31
6. Start R and load library using `library(fcScan)`



