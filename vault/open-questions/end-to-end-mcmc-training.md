---
created_at: '2026-05-02T05:09:05Z'
source_papers:
- '[[arxiv-260427182-preserving-temporal-dynamics-in-time-series-generation]]'
title: End-to-end MCMC training integration
---

**Background:** Current generative frameworks for time series often rely on post-hoc correction to enforce consistency with empirical transition statistics, which introduces computational overhead. Training architectures that natively incorporate these consistency constraints could theoretically improve both fidelity and generation efficiency.

**Question / Future Work:** Research the feasibility of integrating transition-law-enforcing MCMC modules directly into the training objectives of generative architectures to enable end-to-end learning of temporal consistency.

**Why It Matters:** End-to-end integration would potentially eliminate post-processing overhead and allow generators to learn native temporal consistency, representing a significant shift in training methodology.