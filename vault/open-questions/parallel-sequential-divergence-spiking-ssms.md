---
created_at: '2026-04-03T05:25:04Z'
source_papers:
- '[[arxiv-2604.01295-parallelized-hierarchical-connectome-a-spatiotemporal-recurr]]'
title: Parallel vs Sequential Execution Divergence
---

**Background:** The parallel execution of recurrent spiking neural networks is often fundamentally constrained by their non-linear dynamics, complicating the application of standard parallel-scan techniques used in non-spiking state-space models.

**Question / Future Work:** Quantifying and minimizing the numerical divergence between parallel-scan-based training and sequential inference trajectories in spatiotemporal SSMs remains an open challenge, necessitating techniques to align parallel and sequential dynamics.

**Why It Matters:** Bridging the gap between parallel training and sequential inference is essential for the reliability of hardware-efficient sequence models that rely on parallelization for training performance.

**Evidence:** The parallel-to-sequential transition introduces a numerical divergence analogous to the accuracy gap documented in the ANN-to-SNN conversion literature.