**ABC for Alpha-Stable Models**

This repository contains the code and analysis for the project "ABC for Alpha-Stable Models", developed as part of the Simulation and Monte Carlo course at ENSAE Paris.

The goal of this project is to implement and study Approximate Bayesian Computation (ABC) methods to infer the parameters of alpha-stable distributions, a family of heavy-tailed distributions for which the probability density function is generally intractable (except for specific cases like the Gaussian or Cauchy distributions).

🔍 Project Objectives
Implement a generator for alpha-stable distributions using the Chambers-Mallows-Stuck algorithm.

Incorporate Randomized Quasi-Monte Carlo (RQMC) sequences to estimate expectations under alpha-stable models and compare variance with standard Monte Carlo estimates.

Apply and compare several ABC algorithms (ABC-Reject, MCMC-ABC, and SMC-ABC) to perform parameter inference.

(Bonus) Extend the approach to multivariate alpha-stable models.

📄 Reference
This work is based on the paper:

Sisson, S. A. (2011). Likelihood-free Bayesian inference for α-stable models. Computational Statistics & Data Analysis, 55(1), 275–287.
DOI: 10.1016/j.csda.2010.10.004
