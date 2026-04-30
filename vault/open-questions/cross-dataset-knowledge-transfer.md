---
created_at: '2026-04-30T05:15:50Z'
source_papers:
- '[[arxiv-260425499-evotsc-evolving-feature-learning-models-for-time-series-clas]]'
title: Transfer Learning in GP
---

**Background:** Genetic programming (GP) for feature learning is typically performed in isolation for each dataset, which can lead to redundant computation and loss of structural insights shared across similar tasks.

**Question / Future Work:** Investigating methods to transfer or adapt effective sub-structures or primitives discovered by GP across distinct datasets could accelerate search and improve performance in low-data regimes.

**Why It Matters:** Transferring structural building blocks mitigates the computational cost of re-evolving pipelines and enables the accumulation of generalized inductive biases in evolutionary systems.

**Evidence:** Investigating how to transfer or reuse building blocks, such as effective subtree structures, across related datasets could potentially accelerate the evolutionary search and improve performance on label-limited tasks.