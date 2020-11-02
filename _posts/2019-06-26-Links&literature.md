---
layout: post
title: Links and literature
subtitle: Useful places on the web
bigimg: 
tags: [survival, test]
---

Just trying to tidy up my browser and prevent further piling of open tabs of 'things to do'...

## Of general interest
* The [Data Methods forum](https://discourse.datamethods.org) discusses many many many interesting topics (e.g. [Reference Collection to push back against “Common Statistical Myths”](https://discourse.datamethods.org/t/reference-collection-to-push-back-against-common-statistical-myths/1787), or [Should we ignore covariate imbalance and stop presenting a stratified ‘table one’ for randomized trials?](https://discourse.datamethods.org/t/should-we-ignore-covariate-imbalance-and-stop-presenting-a-stratified-table-one-for-randomized-trials/547)
* Frank Harrell's [blog](https://www.fharrell.com/), including posts on [Assessing Heterogeneity of Treatment Effect](https://www.fharrell.com/post/varyor/), and [Added Predictive Value](https://www.fharrell.com/post/addvalue/).

## ISCB 2020
* [Nicole Erler](https://www.nerler.com) on JointAI: [Joint Analysis and Imputation of Incomplete Data in R](https://www.nerler.com/publication/erler2019jointai/). Citing:"JointAI provides functions for Bayesian inference with generalized linear and generalized linear mixed models as well as survival models, that take arguments analogous to their corresponding and well known complete data versions from base R and other packages." Also see [arXiv](https://arxiv.org/abs/1907.10867).

## General information on maximum likelihood estimation
* [Maximum Likelihood, Profile Likelihood, and Penalized Likelihood: A Primer](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3873110/pdf/kwt245.pdf)
* [Is there always a maximizer for any MLE problem?](https://stats.stackexchange.com/questions/16758/is-there-always-a-maximizer-for-any-mle-problem)

## Exchangeability
* [The Concept of Exchangeability and its Applications](https://www.uv.es/~bernardo/Exchangeability.pdf)

## Classification vs Prediction
Frank Harrell's [blog post](https://www.fharrell.com/post/classification/)

## Survival 

Paul Lambert has a nice [website](https://pclambert.net) that includes 
[interactive graphs](https://pclambert.net/interactivegraphs/) on for instance splines 
([number and location of knots](https://pclambert.net/interactivegraphs/spline_eg/spline_eg)) and 
[mixture Weibull distributions](https://pclambert.net/interactivegraphs/mixture_weibull/mixture_weibull).

Piece-wise constant hazard model formulated as a Poisson regression model [link](https://data.princeton.edu/wws509/notes/c7s4)

Residual diagnostics in Cox PH model [RPubs](https://rpubs.com/kaz_yos/resid_cox)

Using Time Dependent Covariates and Time Dependent Coefficients in the Cox Model [Therneau](https://cran.r-project.org/web/packages/survival/vignettes/timedep.pdf)

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

* Simulating right censored survival data in R [simsurv](https://cran.r-project.org/web/packages/simsurv/vignettes/simsurv_usage.html)

* Performance measures for survival prediction models [link](https://bmcmedresmethodol.biomedcentral.com/articles/10.1186/s12874-017-0336-2)

* Comparing the Weibull and Cox PH model [link](https://core.ac.uk/download/pdf/5172563.pdf)

* Very nice blog by Devin Incerti on the basics of parametric survival modeling, including specification of frequently used distribtions, many insightful plots, and R code. Inludes PH parametrization of the Weibull as well. [link](https://devinincerti.com/2019/06/18/parametric_survival.html#weibull-distribution-ph)

## Bayesian Regression
* [bamlss: A Lego Toolbox for Flexible Bayesian Regression (and Beyond)](https://arxiv.org/pdf/1909.11784.pdf)

## Missing data
* Stef van Buuren's most recent version of [Flexible Imputation of Missing Data](https://stefvanbuuren.name/fimd/sec-JM.html)
* Research by Bart Mertens, including [mipred](https://cran.r-project.org/web/packages/mipred/vignettes/mipred_for_glm.html), 
* hmi package for [hierarchical multiple imputation](https://cran.r-project.org/web/packages/hmi/vignettes/myvignette.html)

## Meta-analysis
* General notes on aggregate versus IPD-MA [link](https://www.publichealth.columbia.edu/research/population-health-methods/meta-analyses-aggregate-data-or-individual-participant-data-meta-analyses-retrospectively-and)
* Meta-analysis of Individual Participant Data: Rationale, Conduct, and Reporting in BMJ (2010) [Riley et al.](https://doi.org/10.1136/bmj.c221)
* Cochrane's 'Everything you wanted to know about IPD MA - series' [link](https://methods.cochrane.org/ipdma/everything-you-wanted-know-about-ipd-ma-series)

## Prediction models and uncertainty
* The uncertainty with using risk prediction models for individual decision making: an exemplar cohort study examining the prediction of cardiovascular disease in English primary care [BMC](https://bmcmedicine.biomedcentral.com/articles/10.1186/s12916-019-1368-8)
* Do population-level risk prediction models that use routinely collected health data reliably predict individual risks? [Sci Rep](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6677736/)


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
* [Replicating results for glmnet linear regression using a generic optimizer](https://stats.stackexchange.com/questions/236866/replicating-results-for-glmnet-linear-regression-using-a-generic-optimizer) (Cross Validated)
* [A lasso for hierarchical interactions](http://dx.doi.org/10.1214/13-AOS1096) (Paper by Tibshirani) and the accompanying package [hierNet](https://cran.r-project.org/web/packages/hierNet/index.html)
* Linking smoothing splines to ridge regression [crossvalidated](https://stats.stackexchange.com/questions/93749/selection-of-k-knots-in-regression-smoothing-spline-equivalent-to-k-categorical)
* Freakonometrics [CLASSIFICATION FROM SCRATCH, PENALIZED LASSO LOGISTIC](https://freakonometrics.hypotheses.org/52894) and the referred to [Getting to the Bottom of Regression with Gradient Descent](http://jocelynchi.com/pdf/gettingtothebottom_gradient_descent_R_tutorial.pdf)
* Stats Exchange on lasso versus versus group lasso [link](https://stats.stackexchange.com/questions/214325/why-use-group-lasso-instead-of-lasso)

## Generalized additive modeling
Simon Wood's [website](https://people.maths.bris.ac.uk/~sw15190/) contains links to a (free) [Core Statistics book](https://people.maths.bris.ac.uk/~sw15190/core-statistics.pdf) and info on his new 2nd edition of 'Generalized Additive Models: An Introduction with R' ([errata](https://people.maths.bris.ac.uk/~sw15190/igam/errata.pdf) and sotware changes affecting its content). He also has slides for a lecture on [GAMs, GAMMs and other penalized GLMs using mgcv in R](https://people.maths.bris.ac.uk/~sw15190/talks/gam-mgcv.pdf) online.


## Matching

* Article [Optimal Full Matching and Related Designs via Network Flows](http://dept.stat.lsa.umich.edu/~bbh/hansenKlopfer2006.pdf)
* The accompanying [optmatch package](http://ftp.auckland.ac.nz/software/CRAN/doc/packages/optmatch.pdf) and its [vignette](http://ftp.auckland.ac.nz/software/CRAN/doc/vignettes/optmatch/optmatch.pdf).
* [Vigenette](https://cran.r-project.org/web/packages/optmatch/vignettes/fullmatch-vignette.pdf) for matching in R using the optmatch and RItools packages.
* Some ideas to speed up R base's ``comb`` functionality on [link](https://stackoverflow.com/questions/26828301/faster-version-of-combn.)
* [Finding the best matching pairwise points from 2 vectors](https://stackoverflow.com/questions/13961493/finding-the-best-matching-pairwise-points-from-2-vectors)
* Gay King's [MatchIt: Nonparametric Preprocessing for Parametric Causal Inference](https://gking.harvard.edu/matchit) and [WhatIf: Software for Evaluating Counterfactuals](https://gking.harvard.edu/whatif)
* Short blog on Matching Algorithms (Graph Theory) [link](https://brilliant.org/wiki/matching-algorithms/)



## Splines
The [splines2](https://cran.r-project.org/web/packages/splines2/vignettes/splines2-intro.html) provides functions constructing B-splines, integral of B-splines, monotone splines (M-splines) and its integral (I-splines), convex splines (C-splines), and their derivatives.




## Optimization

* A nice post on [Which optimization algorithm to choose?](https://cran.r-project.org/web/packages/fitdistrplus/vignettes/Optimalgo.html#log-likelihood-function-and-its-gradient-for-beta-distribution)
* [Ben Bolker's MLE package](https://cran.r-project.org/web/packages/bbmle/vignettes/mle2.pdf) ``bbmle`` 
* IRLS for logistic regression [link](https://stats.stackexchange.com/questions/344309/why-using-newtons-method-for-logistic-regression-optimization-is-called-iterati)
* Introduction to the use of [Langrange multipliers](https://people.eecs.berkeley.edu/~klein/papers/lagrange-multipliers.pdf)
* Some introductory lectures on the [Lagrangian](https://www.khanacademy.org/math/multivariable-calculus/applications-of-multivariable-derivatives/lagrange-multipliers-and-constrained-optimization/v/the-lagrangian)
* Optimization problems constrained by parameter sums [link](http://optimizer.r-forge.r-project.org/sumscale16.pdf)
* Overview of optimers in R [link](https://hwborchers.lima-city.de/Presents/ROptimSlides4.pdf)
* Goeman's [penalized](https://cran.r-project.org/web/packages/penalized/penalized.pdf) package for R.
* Regularization Paths for Regression Models with Grouped Covariates as provided in R package [grpreg](https://cran.r-project.org/web/packages/grpreg/grpreg.pdf)
* [Convex optimization in R](http://www.econ.uiuc.edu/~roger/research/conopt/coptr.pdf)
* Simple LARS example in R [link](https://www4.stat.ncsu.edu/~reich/BigData/code/lasso_cd.html)
* LASSO for general likelihood [CrossValidated](https://stats.stackexchange.com/questions/313790/lasso-for-general-likelihood)
* [Generalized Lasso Regularization for Regression Models](https://epub.ub.uni-muenchen.de/11708/1/DA_Flexeder.pdf)
* [Convex Optimization in R](https://machinelearningmastery.com/convex-optimization-in-r/)
* [An overview of gradient descent optimization algorithms](https://ruder.io/optimizing-gradient-descent/), including descriptions of batch gradient descent, stochastic gradient descent, mini-batch gradient descent, Nesterov accelerated gradient, Adagrad, AdaMax, and more.
* Manuscript on Saturating Splines and Feature Selection by Boyd and Hastie [link](https://arxiv.org/pdf/1609.06764.pdf)


## Directional derivatives
* Basic description and examples [Paul's Online Notes](https://tutorial.math.lamar.edu/Classes/CalcIII/DirectionalDeriv.aspx)
* Nice exposition on [Math Libretexts](https://math.libretexts.org/Courses/University_of_California%2C_Davis/UCD_Mat_21C%3A_Multivariate_Calculus/13%3A_Partial_Derivatives/13.5%3A_Directional_Derivatives_and_Gradient_Vectors)


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
* Short recap of Gradient, Jacobian, and Hessian [link](https://www.value-at-risk.net/functions/) 

## Multi-level stuff
* [Visualizing Nested and Cross Random Effects](http://errickson.net/stats-notes/vizrandomeffects.html)
* [Crossed vs nested random effects: how do they differ and how are they specified correctly in lme4?](https://stats.stackexchange.com/questions/228800/crossed-vs-nested-random-effects-how-do-they-differ-and-how-are-they-specified)
* [Using R and lme/lmer to fit different two- and three-level longitudinal models](https://rpsychologist.com/r-guide-longitudinal-lme-lmer)
* [Singular random-effect covariance matrices](https://stats.stackexchange.com/questions/323273/what-to-do-with-random-effects-correlation-that-equals-1-or-1)
* In a multi-level model, [what are the practical implications of estimating versus not-estimating random effect correlation parameters?](https://stats.stackexchange.com/questions/49832/in-a-multi-level-model-what-are-the-practical-implications-of-estimating-versus/104054#104054)
* The effect of number of clusters and cluster size on statistical power and Type I error rates when testing random effects variance components in multilevel linear and logistic regression models [https://doi.org/10.1080/00949655.2018.1504945](https://doi.org/10.1080/00949655.2018.1504945)

## Assessing prediction model performance
* Steyerberg et al. [Assessing the performance of prediction models: a framework for some traditional and novel measures](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3575184/)
* [Consistent Estimation of the Expected Brier Scorein General Survival Models with Right-Censored Event Times](https://onlinelibrary.wiley.com/doi/epdf/10.1002/bimj.200610301)
* [Does ignoring clustering in multicenter data influence the performance of prediction models? A simulation study](https://doi.org/10.1177%2F0962280216668555) by Wynants et al. 

## Sample size
* [Calculating the sample size required for developing a clinical prediction model](https://doi.org/10.1136/bmj.m441) by R. Riley et al.

## Data decomposition and reduction
* Singular value decomposition and PCA [link](https://medium.com/@jonathan_hui/machine-learning-singular-value-decomposition-svd-principal-component-analysis-pca-1d45e885e491)
* Nice stats exchange contribution on PCA and its relation to eigenvalues and singular value decomposition [link](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues). See also [link](https://stats.stackexchange.com/questions/134282/relationship-between-svd-and-pca-how-to-use-svd-to-perform-pca).
* Very nice and comprehensive tutorial on the inner workings of PCA [link](https://www.cs.princeton.edu/picasso/mats/PCA-Tutorial-Intuition_jp.pdf)


## Stan
* Stan Reference Manual [link](https://mc-stan.org/docs/2_21/reference-manual/index.html)
* Stan tutorials [link](https://mc-stan.org/users/documentation/tutorials)
* [bayesplot](https://mc-stan.org/bayesplot/articles/plotting-mcmc-draws.html) package.
* [splines](https://mc-stan.org/users/documentation/case-studies/splines_in_stan.html) in stan.

## Data Sharing
* [NEJM on data sharing](https://www.nejm.org/data-sharing)
* [BMJ](https://bmjopen.bmj.com/content/9/8/e032334) on data sharing

## Fun stuff
* [Stein's paradox](https://en.wikipedia.org/wiki/Stein%27s_example)
* All of the 3BLUE1BROMN stuff, ordered by season and series [here](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

## MIT Stuff
* [Matrix Methods in Data Analysis, Signal Processing, and Machine Learning](https://ocw.mit.edu/courses/mathematics/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/index.htm) and the accompanying book and [website](http://math.mit.edu/~gs/learningfromdata/) including solutions to selected problems.
* [Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/)
* MIT 18.01SC Single Variable Calculus, Fall 2010 [lectures](https://archive.org/details/MIT18_01SCF10/MIT18_01SCF10Rec_00_300k.mp4) and [website](http://ocw.mit.edu/18-01SCF10)
* MIT 18.02SC Multivariable Calculus, Fall 2010 [lectures](https://archive.org/details/MIT18_02SCF10/MIT18_02SCF10Rec_37_300k.mp4) and [website](http://ocw.mit.edu/18-02SCF10)
* MIT 18.05 Introduction to Probability and Statistics, Spring 2014 [lectures](https://archive.org/details/MIT18.05S14)
* MIT OCW: 18.650 Statistics for Applications, Fall 2016  [lectures](https://archive.org/details/MIT18.650F16/MIT18_650F16_lec24_300k.mp4)


## Julia
* Learning Julia [link](https://juliacomputing.com/training/#training-2).
* Julia academy courses to get things started [link](https://juliaacademy.com)

## Causal Inference
* Causal inference in randomized trials [nature bone marrow transpl](https://www.nature.com/articles/s41409-018-0424-x)
* A short paper as a primer on Pearl's work as published in the International Journal of Epidemiology [Pearce and Lawlor](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5841844/#!po=81.5789)
* Armitage lecture by Miguel Hernan [lecture](https://view6.workcast.net/ControlUsher.aspx?cpak=7893749515199787&pak=7155440261855153)
* [A Brief Review of Counterfactual Causality](https://www.ssc.wisc.edu/~felwert/causality/wp-content/uploads/2013/06/1-Elwert_Causal_Intro.pdf) 

## Bookdown
* [bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)
* Nice short overview on prediction modeling in general by Eduardo García Portugués, including non-parametric regression [link[(https://bookdown.org/egarpor/PM-UC3M/)

## Nice solutions for typical problems in R
* Get inner, outer, left, and right joins [link](https://stackoverflow.com/questions/1299871/how-to-join-merge-data-frames-inner-outer-left-right)

## Assignment problem
* Easy example of the assignment problem as a linear program, solved using the lpSolve package in R [link](https://towardsdatascience.com/operations-research-in-r-assignment-problem-4a1f92a09ab)

## Covid-19
* Prediction models for diagnosis and prognosis of covid-19: systematic review and critical appraisal (Wynants et al.)(https://doi.org/10.1136/bmj.m1328)
* [CoronaWatchNL](https://github.com/J535D165/CoronaWatchNL) on Github

## Organisations
* [RSS](https://rss.org.uk)
* [VVSOR](https://www.vvsor.nl)
* [Alan Turing Institute](https://www.turing.ac.uk) and their [Theory and Method Challenge Fortnights](https://www.turing.ac.uk/research/theory-and-method-challenge-fortnights). For instance, the on on [Prediction algorithms with a causal interpretation](https://www.turing.ac.uk/research/theory-and-method-challenge-fortnights/prediction-algorithms-causal-interpretation)
* [Statistical Modelling Society](http://www.statmod.org/workshops.htm) and their International Workshop on Statistical Modelling (IWSM).

## Writing
* [Consequences of Erudite Vernacular Utilized Irrespective of Necessity: Problems with Using Long Words Needlessly](http://www2.psych.utoronto.ca/users/psy3001/files/simple%20writing.pdf)
* 


