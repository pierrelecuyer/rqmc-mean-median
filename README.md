# rqmc-mean-median
A collection of experimental results on using median vs average in RQMC estimation

This repository contains experimental results on the distribution of randomized quasi-Monte Carlo (RQMC) estimators for various integrands, and the distribution, tail probabilities, and mean square error of the median vs the average of $r$ i.i.d. replicates of the estimator to estimate the integral. It is related to the paper ``Using the Median vs the Average when Estimating an Expectation by Randomized Quasi-Monte Carlo'', by Seljak, Lemieux, and L'Ecuyer, 2026, which discusses the relevant theory and setting, and part of the results. 


The file `rqmc-aver-med-collection.pdf` explains what experiments were made and how they were made, gives links to the Java code and tools that was used, and provides a large collection of results and plots. 

The folder `histograms` contains .pdf files with the histograms of all empirical QMC and RQMC distributions, one file per integrand, `datapl` contains all the data files used to make these histograms, and `mse` contains all the files to make the MSE plots and comparisons.

The code Java used to make the experiments is in the `https://github.com/pierrelecuyer/ssj/tree/develop/src/main/docs/examples/rqmcexperiments` folder of the [SSJ library](https://github.com/pierrelecuyer/ssj). To run this code, one must first install SSJ by following the instructions given in the README of the GitHub site of SSJ. 


