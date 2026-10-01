# rqmc-mean-median
A collection of experimental results on using median vs average in RQMC estimation

This repository contains experimental results on the distribution of quasi-Monte Carlo (QMC) and randomized QMC (RQMC) estimators of an integral, for various integrands and various QMC and RQMC methods, in different numbers of dimensions. We provide large samples of independent realizations of these estimators, show histograms of their distributions, and give their moments. We also examine and compare the distributions of $A_r$ and $M_r$, defined as the average and the median of a sample of $r$ i.i.d. replicates of the QMC or RQMC estimator. We show histograms of their distributions, their tail probabilities, their absolute error, and their mean square error, and show how they converge as a function of the number of QMC points and as a function of $r$.

This material is related to the paper ``Using the Median vs the Average when Estimating an Expectation by Randomized Quasi-Monte Carlo'', by Seljak, Lemieux, and L'Ecuyer, 2026, which discusses the relevant theory and setting, and part of the results. The original extended version of that paper is given here in the file `rqmc-mean-median-long.pdf`. A shortened version has been submitted to a journal. 

The file `rqmc-aver-med-collection.pdf` given here explains what experiments were made and how they were made, gives links to the Java code and tools that was used, and provides a large collection of results and plots. There are other explanations in the paper. 

The folder `histograms` contains .pdf files with the histograms of all empirical QMC and RQMC distributions, one file per integrand, `datapl` contains the 3865 data files used to make these histograms, and `mse` contains all the files to make the MSE plots and comparisons.

The code Java used to make the experiments is in the `https://github.com/pierrelecuyer/ssj/tree/develop/src/main/docs/examples/rqmcexperiments` folder of the [SSJ library](https://github.com/pierrelecuyer/ssj). This is in the 'develop' branch of the repository. To run this code, one must first install SSJ by following the instructions given in the README of the GitHub site of SSJ. 


