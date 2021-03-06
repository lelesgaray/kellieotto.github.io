---
title: "An Empirical Comparison of Parametric and Permutation Tests for Regression Analysis of Randomized Experiments"
collection: publications
permalink: /publication/2017-10-10-nonparametric-ancova
excerpt: 'We compared traditional ANCOVA to permutation approaches in the analysis of randomized experiments.'
date: 2017-10-10
paperurl: 'https://arxiv.org/abs/1702.04851'
---
*with Fraser Lewis and Luigi Salmaso*

[Visit the project repo](https://github.com/kellieotto/ancova-permutations)

Hypothesis tests based on linear models are widely accepted by organizations that regulate clinical trials. These tests are derived using strong assumptions about the data-generating process so that the resulting inference can be based on parametric distributions. Because these methods are well understood and robust, they are sometimes applied to data that depart from assumptions, such as ordinal integer scores. Permutation tests are a nonparametric alternative that require minimal assumptions which are often guaranteed by the randomization that was conducted. We compare analysis of covariance (ANCOVA), a special case of linear regression that incorporates stratification, to several permutation tests based on linear models that control for pretreatment covariates. In simulations of randomized experiments using models which violate some of the parametric regression assumptions, the permutation tests maintain power comparable to ANCOVA. We illustrate the use of these permutation tests alongside ANCOVA using data from a clinical trial comparing the effectiveness of two treatments for gastroesophageal reflux disease. Given the considerable costs and scientific importance of clinical trials, an additional nonparametric method, such as a linear model permutation test, may serve as a robustness check on the statistical inference for the main study endpoints.