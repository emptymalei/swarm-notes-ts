---
created_at: '2026-05-06T05:13:50Z'
source_papers:
- '[[arxiv-260502759-dynoslam-dynamic-slam-with-generative-graph-neural-networks]]'
title: Flow Matching for Trajectory Forecasting
---

**Background:** Flow-based generative models enable direct estimation of probability density functions for trajectory forecasting, bypassing the need for surrogate perturbations in Monte Carlo sampling.

**Question / Future Work:** Current approaches for estimating trajectory uncertainty in dynamic SLAM rely on Monte Carlo rollouts with manually injected perturbations. Future research should investigate using Flow Matching architectures to learn continuous probability density vector fields of pedestrian trajectories, providing a more mathematically rigorous approach to multimodal motion generation.

**Why It Matters:** Transitioning from perturbation-based sampling to learned flow fields could provide more reliable and computationally efficient uncertainty quantification in dynamic SLAM environments.

**Evidence:** While the Stochastic GAT successfully models interaction uncertainty via Monte Carlo sampling, it relies on manually injected perturbations. In future work, we plan to replace this surrogate stochasticity with a fully generative Flow Matching architecture.