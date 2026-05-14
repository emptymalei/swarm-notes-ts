---
created_at: '2026-05-14T05:24:47Z'
source_papers:
- '[[arxiv-260513150-generative-modeling-of-approximately-periodic-time-series-by]]'
title: Scaling Likelihood for Many Repetitions
---

**Background:** Gaussian Processes (GPs) provide probabilistic modeling for temporal sequences but often struggle to efficiently balance consistent structural periodicities with inter-repetition variability. Traditional periodic kernels are too rigid, while standard non-periodic kernels fail to capture long-term structural constraints.

**Question / Future Work:** Computational complexity arises when evaluating the likelihood of approximately periodic GP models based on modulated posterior kernels, particularly as the number of repetitions increases. Adapting sparse or approximate inference techniques—originally developed for standard GPs—to this covariance modulation framework remains a significant open challenge for scalability.

**Why It Matters:** The current likelihood evaluation mechanism precludes the application of the model to industrial systems with long sequences of repetitions, limiting its practical utility.