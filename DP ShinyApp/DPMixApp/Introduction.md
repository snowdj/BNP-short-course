## About
Dirichlet Process (DP) models are a flexible class of Bayesian nonparametric (BNP) models with broad applicability. DP models can be used for unsupervised clustering, nonparametric density estimation, and nonparametric regressions. 

The Dirichlet Process is a distribution over distributions. Whereas a probability distribution characterizes the uncertainty about realizations of a random variable, the Dirichlet Process characterizes the uncertainty about the distribution itself. 

This is not an immediately intuitive concept. The purpose of this interactive tutorial is to provide some intuition and insight around the Dirichlet Process and its applications in BNP methods. 

Note: this app uses `MathJax` to render mathematical equations. Internet access is required for `MathJax` to work.

## Prerequisites
This tutorial assumes you have an advanced undergraduate/graduate level understanding of probability theory and familiarity with parametric Bayesian principles and methods. A working knowledge of Monte Carlo Markov Chain (MCMC) is also helpful.

## Contents
Below is an outline of this tutorial. The numbers correspond to the numbered tabs in the ribbon above.

1. Realizations of a DP. 
      + a. Interactive visualization of draws/realizations from Dirichlet Processes user-specified DP parameters.
      + b. The stick-breaking characterization of the Dirichlet Process.
2. Posterior of a DP.
      + a. Interactive visualization of draws from the posterior of a probability mass function estimation model with DP prior.
3. DP Mixtures.
      + a. Interactive visualization of density estimation using a DP prior.
      + b. Interactive visualization of clustering induced by a DP prior.
      + c. Outline of DP priors for nonparametric regression.
4. References.

## Issues and Contact Information

This application was originally designed to complement a short course on BNP methods for causal inference taught by Dr. Jason Roy and Dr. Michael Daniels at the Joint Statistical Meetings 2018. 

All source code for this application can be found on the short course [GitHub repository](https://github.com/jasonroy0/BNP-short-course).

The application was programmed in R using the `Shiny` package by [Arman Oganisian](https://twitter.com/StableMarkets).

To report bugs, please start an issue on our [GitHub issues page](https://github.com/jasonroy0/BNP-short-course/issues).