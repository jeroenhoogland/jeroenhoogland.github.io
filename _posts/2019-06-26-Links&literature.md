---
layout: post
title: Links and literature
subtitle: Useful places on the web
bigimg: 
tags: [survival, test]
---

Just trying to tidy up my browser and prevent further piling of open tabs of 'things to do'...

## Survival 

Paul Lambert has a nice [website](https://pclambert.net) that includes 
[interactive graphs](https://pclambert.net/interactivegraphs/) on for instance splines 
([number and location of knots](https://pclambert.net/interactivegraphs/spline_eg/spline_eg)) and 
[mixture Weibull distributions](https://pclambert.net/interactivegraphs/mixture_weibull/mixture_weibull).

Some R code for modeling with left truncated and right/interval censored data [link](http://blogs2.datall-analyse.nl/2016/02/19/rcode_left_truncated_censored_data/#more-294) including the likelihood definition and ``optim`` routine. 

Using L_BFGS-B to fit a Weibul model (includes gradient) [link](https://stackoverflow.com/questions/39747569/r-optim-l-bfgs-b-needs-finite-values-of-fn-weibull)

Furthermore
* [Large-Scale Parametric Survival Analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3796130/#APP1) on regularized parametric survival modeling
* [Multilevel mixed effects parametric survival analysis](https://www.stata.com/meeting/uk13/abstracts/materials/uk13_crowther.pdf), a lecture by Michael Crowther
* A review on [Survival analysis with high-dimensional covariates](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4806549/) by Witten and Tibshirani


## Subgroup analysis based on RCT data

A comparison of several approaches to predict most beneficial treatment class (Elastic Net, ridge-regularized Cox proportional hazards model, RandomForest, linear Support Vector Machine (SVM), [Predictive Analysis of Clinical Trials](https://CRAN.R-project.org/package=pact)) [link](https://doi.org/10.1101/338996)


## Regularization

* Trevor Hastie's [website](https://web.stanford.edu/~hastie/index.html) contains an [overview](https://web.stanford.edu/~hastie/swData.htm) of some useful R packages he's worked on including ``gamsel``, ``glinternet``, and ``glmnet``. 
* [Statistics for High-Dimensional Data](https://link.springer.com/book/10.1007%2F978-3-642-20192-9) by Peter BühlmannSara van de Geer
* [grpreg](https://cran.r-project.org/web/packages/grpreg/grpreg.pdf) package by Patrick Breheny
* Solving ridge for a linear model based on just least squares [whuber](https://stats.stackexchange.com/questions/69205/how-to-derive-the-ridge-regression-solution)
* Hand coding of penalized logistic regression in R [link](https://datascienceplus.com/logistic-regression-regularized-with-optimization/) and/or [link](http://pingax.com/logistic-regression-r-step-step-implementation-part-2/?utm_source=rss&utm_medium=rss&utm_campaign=logistic-regression-r-step-step-implementation-part-2)
* [Lecture notes on ridge regression](https://arxiv.org/pdf/1509.09169;Lecture) 


## Generalized additive modeling
Simon Wood's [website](https://people.maths.bris.ac.uk/~sw15190/) contains links to a (free) [Core Statistics book](https://people.maths.bris.ac.uk/~sw15190/core-statistics.pdf) and info on his new 2nd edition of 'Generalized Additive Models: An Introduction with R' ([errata](https://people.maths.bris.ac.uk/~sw15190/igam/errata.pdf) and sotware changes affecting its content). He also has slides for a lecture on [GAMs, GAMMs and other penalized GLMs using mgcv in R](https://people.maths.bris.ac.uk/~sw15190/talks/gam-mgcv.pdf) online.


## Matching

* Article [Optimal Full Matching and Related Designs via Network Flows](http://dept.stat.lsa.umich.edu/~bbh/hansenKlopfer2006.pdf)
* The accompanying [optmatch package](http://ftp.auckland.ac.nz/software/CRAN/doc/packages/optmatch.pdf) and its [vignette](http://ftp.auckland.ac.nz/software/CRAN/doc/vignettes/optmatch/optmatch.pdf).
* Some ideas to speed up R base's ``comb`` functionality on [link](https://stackoverflow.com/questions/26828301/faster-version-of-combn.)
* [Finding the best matching pairwise points from 2 vectors](https://stackoverflow.com/questions/13961493/finding-the-best-matching-pairwise-points-from-2-vectors)
* Gay King's [MatchIt: Nonparametric Preprocessing for Parametric Causal Inference](https://gking.harvard.edu/matchit) and [WhatIf: Software for Evaluating Counterfactuals](https://gking.harvard.edu/whatif)


## Splines
The [splines2](https://cran.r-project.org/web/packages/splines2/vignettes/splines2-intro.html) provides functions constructing B-splines, integral of B-splines, monotone splines (M-splines) and its integral (I-splines), convex splines (C-splines), and their derivatives.


## Optmization

* A nice post on [Which optimization algorithm to choose?](https://cran.r-project.org/web/packages/fitdistrplus/vignettes/Optimalgo.html#log-likelihood-function-and-its-gradient-for-beta-distribution)
* [Ben Bolker's MLE package](https://cran.r-project.org/web/packages/bbmle/vignettes/mle2.pdf) ``bbmle`` 
* IRLS for logistic regression [link](https://stats.stackexchange.com/questions/344309/why-using-newtons-method-for-logistic-regression-optimization-is-called-iterati)
* Introduction to the use of [Langrange multipliers](https://people.eecs.berkeley.edu/~klein/papers/lagrange-multipliers.pdf)
* Some introductory lectures on the [Lagrangian](https://www.khanacademy.org/math/multivariable-calculus/applications-of-multivariable-derivatives/lagrange-multipliers-and-constrained-optimization/v/the-lagrangian)


## General background information on regression

* [GLMs](https://www.sagepub.com/sites/default/files/upm-binaries/21121_Chapter_15.pdf)
* [Slides for 'Advanced Regression' course](https://web.as.uky.edu/statistics/users/pbreheny/760/S13/notes.html) (University of Kentucky) including general information on [Maximum likelihood estimation](https://web.as.uky.edu/statistics/users/pbreheny/760/S13/notes/1-29.pdf) and [Weighted least squares](https://web.as.uky.edu/statistics/users/pbreheny/760/S13/notes/2-7.pdf) and [GLM estimation and model fitting](https://web.as.uky.edu/statistics/users/pbreheny/760/S13/notes/2-19.pdf).








