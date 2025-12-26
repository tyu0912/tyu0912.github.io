---
title: "Understanding bootstrapping, bagging, and boosting"
date: 2019-01-23 07:57:00 -0500
categories: [AI]
tags: [learnings]
---

Some good materials/examples to introduce data bootstrapping, a method to expand data through resampling:
- https://projecteuclid.org/download/pdf_1/euclid.aos/1176344552 (original paper)
- http://galton.uchicago.ehttps://ocw.mit.edu/courses/mathematics/18-05-introduction-to-probability-and-statistics-spring-2014/readings/MIT18_05S14_Reading24.pdfdu/~eichler/stat24600/Handouts/bootstrap.pdf (best examples)
- https://www.thoughtco.com/example-of-bootstrapping-3126155


For bagging vs boosting, in boosting there is resampling between each model training to focus on the bad data. There is a weight attributed to each model when developing the polling algorithm. In bagging, every model has the same weight.

Resources:
- https://quantdare.com/what-is-the-difference-between-bagging-and-boosting/