---
created_at: '2026-05-09T05:11:15Z'
source_papers:
- '[[arxiv-260506032-does-synthetic-data-help-empirical-evidence-from-deep-learni]]'
title: Scaling laws for synthetic time series augmentation
---

**Background:** Synthetic data augmentation is increasingly utilized in deep learning for time series forecasting, yet the scaling laws governing how much synthetic data a model can effectively absorb remain unestablished.

**Question / Future Work:** While scaling laws for synthetic data have been advanced in large language models, there is no equivalent, well-defined understanding for time series forecasters. Establishing these laws would provide a principled basis for determining optimal synthetic-to-real data ratios and understanding the point of diminishing returns or performance degradation across different model architectures.

**Why It Matters:** Understanding scaling laws is critical for moving beyond empirical trial-and-error, enabling the design of more efficient training pipelines and predictable performance gains in data-scarce scenarios.

**Evidence:** Research on the scaling laws governing how much synthetic data a model can absorb has advanced rapidly for text (Kang et al., 2025; Goyal and Chaturvedi, 2023), but equivalent results for time series remain absent.