---
created_at: '2026-05-02T05:07:35Z'
source_papers:
- '[[arxiv-260427967-differentiable-latent-structure-discovery-for-interpretable]]'
title: Scalability of GP Clinical Models
---

**Background:** Gaussian processes (GPs) are limited by cubic computational complexity with respect to the number of observations, which challenges their application to long clinical time series or large multivariate datasets.

**Question / Future Work:** Enhancing the scalability of process convolution models to settings involving longer individual trajectories or a larger number of tasks while maintaining the benefits of an exact GP framework remains a significant challenge. Future work requires the integration of dedicated block-sparse routines for GP solvers to overcome current computational bottlenecks.

**Why It Matters:** Scalability is a primary bottleneck for adopting principled, uncertainty-aware GP models in large-scale settings, which often forces a trade-off between statistical rigor and computational feasibility.