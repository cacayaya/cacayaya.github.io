---
title: Learning Functional Distributions with Private Labels
description: 
toc: true
authors:
  - Yifan Wang
tags:
categories:
series:
date: '2023-05-23T16:31:26-04:00'
lastmod: '2023-05-23T16:31:26-04:00'
featuredImage:
draft: true
---

We study the problem of learning functional distributions in the presence of noise. The functional is a map from features to distributions over a set of labels and is assumed to belong to a known class of hypotheses. Features are generated by a general random process and labels are sampled independently from the feature-dependent distributions and then passed through a noisy kernel. We consider online learning where at each time step a predictor attempts to predict the actual (label) distribution given only the features revealed so far and noisy labels in prior steps. The performance of the predictor is measured by the expected KL-risk that compares the predicted distributions to the underlying truth. We show that the minimax
expected KL-risk is of order $\Theta^~(T\log|\mathcal{F}|)$ for finite hypothesis class $\mathcal{F}$. We then extend this result to general infinite classes via the concept of stochastic sequential covering and provide matching lower and upper bounds for a wide range of natural classes.

Full paper: https://www.cs.purdue.edu/homes/spa/papers/icml23-privacy.pdf