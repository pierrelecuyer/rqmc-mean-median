# rqmc-mean-median
Experimental results on using median vs average in RQMC estimation

This repository is a companion to the paper ``Using the Median vs the Average when Estimating an Expectation by Randomized Quasi-Monte Carlo'', by Seljak, Lemieux, and L'Ecuyer. The aim of that paper is to examine the distribution of randomized quasi-Monte Carlo (RQMC) estimators for various integrands, and compare the tail probabilies and MSE of the median vs the average of $r$ i.i.d. replicates of the estimator to estimate the integral, which is an expectation.

The file `rqmc-aver-med-supplement.pdf` contains an Online Supplement for the paper that explains how we made the experiments, gives links to the Java code and tools that we used, says what this repository contains, and provides additional results and plots. 

The folder `histograms` contains .pdf files with the histograms of all empirical QMC and RQMC distributions, one file per integrand, `datapl` contains all the data files used to make these histograms, and `mse` contains all the files to make the MSE plots and comparisons.

The code Java used to make the experiments is in the `https://github.com/pierrelecuyer/ssj/tree/develop/src/main/docs/examples/rqmcexperiments` folder of the [SSJ library](https://github.com/pierrelecuyer/ssj). To run this code, one must first install SSJ by following the instructions given in the README of the GitHub site of SSJ. 
