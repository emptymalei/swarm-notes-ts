---
created_at: '2026-04-08T04:56:05Z'
source_papers:
- '[[arxiv-260405543-channel-wise-retrieval-for-multivariate-time-series-forecast]]'
title: Adaptive Retrieval Parameter Selection
---

**Background:** Retrieval-augmented forecasting models improve long-range dependency modeling by retrieving historical segments from memory, but existing implementations often rely on static, manually tuned hyperparameters for selecting relevant temporal references.

**Question / Future Work:** Developing adaptive methods to dynamically determine optimal frequency components and retrieval parameters for different channels, rather than using global hyperparameters, is necessary for handling highly heterogeneous multivariate time series.

**Why It Matters:** Static hyperparameters for retrieval limit the model's ability to effectively handle channels with varying noise levels or spectral characteristics.

**Evidence:** In the sparse relation graph, the number of candidates M is set to 3. During retrieval, the number of references k is set to 1, selected by spectral similarity over the first F = 36 frequency components... The weighting coefficient α is set to 0.001.