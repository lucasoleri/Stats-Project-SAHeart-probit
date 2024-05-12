# Stats-Project-SAHeart-probit
Final Project for the course Statistics and Probability

Probit Regression Implementation and Analysis
This project implements Probit regression, an alternative Generalized Linear Model for binary data, using two different approaches: Fisher scoring algorithm and Markov Chain Monte Carlo (MCMC) method. The implementation is applied to the "SAheart" dataset, which contains retrospective samples of males in a heart-disease high-risk region of the Western Cape, South Africa.

Dataset Description

The "SAheart" dataset includes a binary response variable "chd" indicating whether the individual suffered from coronary heart disease and nine covariates of interest. The goal of the analysis is to assess the impact of these covariates, such as cholesterol, on the occurrence of coronary heart disease.

Fisher Scoring Algorithm

The Fisher scoring algorithm is implemented in Python to perform Probit regression. It involves computing the likelihood function and iteratively updating the parameters to maximize the likelihood.

Bayesian Probit Regression

A Python script is created to implement a Markov Chain Monte Carlo method, specifically the random walk Metropolis-Hastings algorithm, for Bayesian Probit regression. This method allows for Bayesian inference by sampling from the posterior distribution of the parameters.

Made in collaboration with: Emanuele Sala and Daniel Mitoiu
