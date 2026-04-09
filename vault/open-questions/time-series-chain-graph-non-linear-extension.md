---
created_at: '2026-04-09T04:54:50Z'
source_papers:
- '[[arxiv-260407018-time-series-gaussian-chain-graph-models]]'
title: Non-linear Chain Graph Extensions
---

**Background:** Gaussian chain graph models represent multivariate dependence structures by partitioning variables into blocks with within-block undirected edges and cross-block directed edges. Existing estimation methods for these models have been primarily developed for static data or stationary processes, leaving gaps in handling more complex, non-linear dynamic dependencies.

**Question / Future Work:** Extending time series Gaussian chain graph models to account for non-stationary or non-linear innovations (e.g., GARCH-type volatility) and maintaining theoretical guarantees in high-dimensional regimes where variables exceed observations remains an open research challenge.

**Why It Matters:** The model's current reliance on stationary, linear-innovation assumptions limits its applicability to real-world financial data, where volatility clustering and non-linear dynamics are pervasive.