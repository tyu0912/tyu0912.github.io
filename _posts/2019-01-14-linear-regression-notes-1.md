---
title: "Linear Regression Notes 1"
date: 2019-01-14 06:58:00 -0500
categories: [AI]
tags: [learnings]
---

- The method to OLS comes from finding the partial derivatives of the yhat
- estimator for a line with respect to b_0 and b_1, ie, the traditional intercept and slope coefficients.
- R^2 is basically looking at the RSS/TSS where RSS is the residual sum of squares sum(yhat - y_avg)/sum(y - y_avg). If R = 0 then yhat = y_avg and you essentially have a horizontal line. If R = 1 then yhat = y meaning that all your points line up straight on a line.
- Important to note that R^2 sucks. It can increase by just adding more variables. Try Radj or AIC.

MLS Assumptions:
- There must be a linear relationship
- No colinearity
- Random Sampling
- Expected value of error given x's is 0
- Homoskedasticity - variance of error must be constant
- The population error is independent of the variables and is normally distributed

Although this is written from a biological perspective, this is a great [resource](http://www.biostathandbook.com):

This is also a good [link](https://www.statisticssolutions.com/assumptions-of-logistic-regression/) that contrasts linear and logistic regression.

Also, there are diagnostic plots on R that are very useful. To interpret, go [here](https://stats.idre.ucla.edu/r/dae/robust-regression/).