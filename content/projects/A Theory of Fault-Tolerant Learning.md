---
title: A Theory of Fault-Tolerant Learning
description: 
toc: true
authors:
  - Yifan Wang
tags:
categories:
series:
date: '2024-05-25T16:31:26-04:00'
lastmod: '2024-05-25T16:31:26-04:00'
featuredImage:
draft: false
---

Developing machine learning models that account for potential faults encountered in real-world environments presents a fundamental challenge for mission-critical applications. In this paper, we introduce a novel theoretical framework grounded in learning theory for dealing with faults. In particular, we propose a framework called *fault-tolerant PAC learning*, aimed at identifying the most fault-tolerant models from a given hypothesis class (such as neural networks). We show that if faults occur randomly, fault-tolerant learning is equivalent to regular PAC learning. However, for *adversarial* faults, we show that the sample complexity of fault-tolerant PAC learning can grow linearly w.r.t. the number of perturbing functions induced by the faults, even for a hypothesis class with VC-dimension 1. We then provide a matching upper bound by restricting the number of perturbing functions. Finally, we show that the linear dependency on the number of perturbing functions can be substantially improved for *deletion faults* in neural networks. Our work provides a powerful formal framework and avenues for a number of future investigations on the precise characterization of fault-tolerant learning.
