---
created_at: '2026-04-27T05:11:27Z'
source_papers:
- '[[arxiv-260422511-optimal-sensor-placement-for-the-reconstruction-of-ocean-sta]]'
title: Computational efficiency of sampling-mask optimization
---

**Background:** Gradient-based optimization of discrete sampling masks often requires Monte Carlo estimates, which can impose significant computational costs during the training process.

**Question / Future Work:** Develop variance-reduction techniques or more efficient gradient estimators to reduce the number of samples needed for training, thereby improving the framework's computational efficiency and scalability for larger domains.

**Why It Matters:** High computational costs limit the ability to scale the framework to larger domains or to perform frequent, real-time re-optimization in operational environments.

**Evidence:** the need to use Monte Carlo sampling to handle the mask’s stochasticity increases the per-iteration computational cost.