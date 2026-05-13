---
created_at: '2026-05-13T05:23:38Z'
source_papers:
- '[[arxiv-260512196-ecto-exogenous-conditioned-temporal-operator-for-ultra-short]]'
title: Adaptive regime expert scaling
---

**Background:** Mixture-of-experts (MoE) architectures in time-series forecasting rely on routing mechanisms to partition input samples into predictive regimes, with the number of experts typically set as a fixed hyperparameter.

**Question / Future Work:** Determining the optimal number of regime experts in an end-to-end forecasting architecture is a significant bottleneck, as current implementations rely on predefined, fixed hyperparameters. An adaptive mechanism that learns the appropriate number of regimes directly from training data is needed to reduce manual tuning and improve generalization.

**Why It Matters:** Adaptive expert counts would allow models to automatically match the complexity of the underlying data distribution, preventing both underfitting and overfitting/instability.