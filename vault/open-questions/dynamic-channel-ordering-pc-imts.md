---
created_at: '2026-05-02T05:07:59Z'
source_papers:
- '[[arxiv-260427814-probabilistic-circuits-for-irregular-multivariate-time-serie]]'
title: Dynamic Channel Ordering in PCs
---

**Background:** Probabilistic circuits (PCs) are a flexible framework for modeling joint probability distributions, but their application to irregular multivariate time series requires defining a structure that remains valid under varying query sets. Providing structural guarantees for marginalization consistency is a significant challenge in high-dimensional domains.

**Question / Future Work:** The recursive factorization structure in probabilistic circuits for multivariate time series is dependent on channel ordering. Identifying an optimal permutation is computationally intractable, leaving the impact of fixed-ordering heuristics versus dynamic or learned orderings on model expressivity an unresolved research direction.

**Why It Matters:** Channel ordering defines the inductive bias of the recursive decomposition in circuit-based models, and its optimization is a known bottleneck for capacity scaling in high-dimensional multivariate settings.

**Evidence:** While the sequential structure of the SPN implies that the order theoretically influences the modeled joint density, identifying an optimal order is computationally intractable due to the C! possible permutations.