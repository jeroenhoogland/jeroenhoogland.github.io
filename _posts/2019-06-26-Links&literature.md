---
layout: post
title: Links and literature
subtitle: Useful places on the web
bigimg: 
tags: [survival, test]
---

Just trying to tidy up my browser and prevent further piling of open tabs of 'things to do'...

## General information on maximum likelihood estimation
[Maximum Likelihood, Profile Likelihood, and Penalized Likelihood: A Primer](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3873110/pdf/kwt245.pdf)

## Classification vs Prediction
Frank Harrell's [blog post](https://www.fharrell.com/post/classification/)

## Survival 

Paul Lambert has a nice [website](https://pclambert.net) that includes 
[interactive graphs](https://pclambert.net/interactivegraphs/) on for instance splines 
([number and location of knots](https://pclambert.net/interactivegraphs/spline_eg/spline_eg)) and 
[mixture Weibull distributions](https://pclambert.net/interactivegraphs/mixture_weibull/mixture_weibull).

Piece-wise constant hazard model formulated as a Poisson regression model [link](https://data.princeton.edu/wws509/notes/c7s4)

Estimating a [smooth baseline hazard function for the Cox model](https://pdfs.semanticscholar.org/2f32/9b48f674a74253eb428b71ff237365fd4051.pdf) by Patrick Royston.

Some R code for modeling with left truncated and right/interval censored data [link](http://blogs2.datall-analyse.nl/2016/02/19/rcode_left_truncated_censored_data/#more-294) including the likelihood definition and ``optim`` routine. 

Using L-BFGS-B to fit a Weibul model (includes gradient) [link](https://stackoverflow.com/questions/39747569/r-optim-l-bfgs-b-needs-finite-values-of-fn-weibull)

Furthermore
* [Large-Scale Parametric Survival Analysis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3796130/#APP1) on regularized parametric survival modeling
* [Multilevel mixed effects parametric survival analysis](https://www.stata.com/meeting/uk13/abstracts/materials/uk13_crowther.pdf), a lecture by Michael Crowther
* A review on [Survival analysis with high-dimensional covariates](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4806549/) by Witten and Tibshirani
* Marginal effect in JM context [Floor van Oudenhoven](https://floorvanoudenhoven.shinyapps.io/presentatie/#29)

*  C-statistics for censored survival data [link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3079915/)

* Survival intro slides [Stanford](https://web.stanford.edu/~lutian/coursepdf/slideweek1.pdf)

## Missing data
* Stef van Buuren's most recent version of [Flexible Imputation of Missing Data](https://stefvanbuuren.name/fimd/sec-JM.html)


## Subgroup analysis / treatment-interactions

A comparison of several approaches to predict most beneficial treatment class (Elastic Net, ridge-regularized Cox proportional hazards model, RandomForest, linear Support Vector Machine (SVM), [Predictive Analysis of Clinical Trials](https://CRAN.R-project.org/package=pact)) [link](https://doi.org/10.1101/338996)

* A Simple Method for Estimating Interactions Between a Treatment and a Large Number of Covariates by [Lu Tian, Ash A. Alizadeh, Andrew J. Gentles & Robert Tibshirani](https://www.tandfonline.com/doi/pdf/10.1080/01621459.2014.951443?needAccess=true)


## Regularization

* Trevor Hastie's [website](https://web.stanford.edu/~hastie/index.html) contains an [overview](https://web.stanford.edu/~hastie/swData.htm) of some useful R packages he's worked on including ``gamsel``, ``glinternet``, and ``glmnet``. 
* [Statistics for High-Dimensional Data](https://link.springer.com/book/10.1007%2F978-3-642-20192-9) by Peter BühlmannSara van de Geer
* [grpreg](https://cran.r-project.org/web/packages/grpreg/grpreg.pdf) package by Patrick Breheny
* Solving ridge for a linear model based on just least squares [whuber](https://stats.stackexchange.com/questions/69205/how-to-derive-the-ridge-regression-solution)
* Hand coding of penalized logistic regression in R [link](https://datascienceplus.com/logistic-regression-regularized-with-optimization/) and/or [link](http://pingax.com/logistic-regression-r-step-step-implementation-part-2/?utm_source=rss&utm_medium=rss&utm_campaign=logistic-regression-r-step-step-implementation-part-2)
* [Lecture notes on ridge regression](https://arxiv.org/pdf/1509.09169;Lecture) 
* Post-double-selection LASSO [slides](https://statalasso.github.io/pdf/SwissStataConference2018_AhrensSchaffer.pdf)


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


## Optimization

* A nice post on [Which optimization algorithm to choose?](https://cran.r-project.org/web/packages/fitdistrplus/vignettes/Optimalgo.html#log-likelihood-function-and-its-gradient-for-beta-distribution)
* [Ben Bolker's MLE package](https://cran.r-project.org/web/packages/bbmle/vignettes/mle2.pdf) ``bbmle`` 
* IRLS for logistic regression [link](https://stats.stackexchange.com/questions/344309/why-using-newtons-method-for-logistic-regression-optimization-is-called-iterati)
* Introduction to the use of [Langrange multipliers](https://people.eecs.berkeley.edu/~klein/papers/lagrange-multipliers.pdf)
* Some introductory lectures on the [Lagrangian](https://www.khanacademy.org/math/multivariable-calculus/applications-of-multivariable-derivatives/lagrange-multipliers-and-constrained-optimization/v/the-lagrangian)

## Variable selection after multiple imputation
* [Stef van Buuren's suggestions](https://stats.stackexchange.com/questions/46719/multiple-imputation-and-model-selection) on Stack Exchange (including refs to book sections and Wood et al. 2008) 
* [MAMI package](http://mami.r-forge.r-project.org/MAMI_manual.pdf) in R, based on Schomaker, M. and C. Heumann (2014). Model selection and model averaging after multiple imputation. Computational Statistics and Data Analysis 71, 758–770.

## Speed and R
* Is R fast enough? An example on sorting: [link](http://predictiveecology.org/2015/04/28/Is-R-fast-enough-02.html)

## General background information on regression
* Logistic regression basics, numerical optimization, IRLS, GAM and more [Logistic regression chapter](https://www.stat.cmu.edu/~cshalizi/uADA/12/lectures/ch12.pdf)
* [GLMs](https://www.sagepub.com/sites/default/files/upm-binaries/21121_Chapter_15.pdf)
* [Slides for 'Advanced Regression' course](https://web.as.uky.edu/statistics/users/pbreheny/760/S13/notes.html) (University of Kentucky) including general information on [Maximum likelihood estimation](https://web.as.uky.edu/statistics/users/pbreheny/760/S13/notes/1-29.pdf) and [Weighted least squares](https://web.as.uky.edu/statistics/users/pbreheny/760/S13/notes/2-7.pdf) and [GLM estimation and model fitting](https://web.as.uky.edu/statistics/users/pbreheny/760/S13/notes/2-19.pdf).

## Math stuff
* (World Wide) Multivariable calculus [lectures](https://www.youtube.com/playlist?list=PLgKTLlHQn9510xXzi9tlZYU38XFs279qv) and [textbook](http://centerofmath.org/textbooks/multicalc/index.html)
* [MATH 19520 (Mathematics for Social Sciences)](https://vipulnaik.com/math-195/)
* Nice and simple introduction to [moment generating functions](https://towardsdatascience.com/moment-generating-function-explained-27821a739035)

## Multi-level stuff
* [Visualizing Nested and Cross Random Effects](http://errickson.net/stats-notes/vizrandomeffects.html)
* [Using R and lme/lmer to fit different two- and three-level longitudinal models](https://rpsychologist.com/r-guide-longitudinal-lme-lmer)
* [Singular random-effect covariance matrices](https://stats.stackexchange.com/questions/323273/what-to-do-with-random-effects-correlation-that-equals-1-or-1)
* In a multi-level model, [what are the practical implications of estimating versus not-estimating random effect correlation parameters?](https://stats.stackexchange.com/questions/49832/in-a-multi-level-model-what-are-the-practical-implications-of-estimating-versus/104054#104054)
* The effect of number of clusters and cluster size on statistical power and Type I error rates when testing random effects variance components in multilevel linear and logistic regression models [https://doi.org/10.1080/00949655.2018.1504945](https://doi.org/10.1080/00949655.2018.1504945)

## Assessing prediction model performance
* Steyerberg et al. [Assessing the performance of prediction models: a framework for some traditional and novel measures](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3575184/)
* [Consistent Estimation of the Expected Brier Scorein General Survival Models with Right-Censored Event Times](https://onlinelibrary.wiley.com/doi/epdf/10.1002/bimj.200610301)


## Stan
* [bayesplot](https://mc-stan.org/bayesplot/articles/plotting-mcmc-draws.html) package.
* [splines](https://mc-stan.org/users/documentation/case-studies/splines_in_stan.html) in stan.

## Data Sharing
* [NEJM on data sharing](https://www.nejm.org/data-sharing)
* [BMJ](https://bmjopen.bmj.com/content/9/8/e032334) on data sharing

## Fun stuff
* [Stein's paradox](https://en.wikipedia.org/wiki/Stein%27s_example)




