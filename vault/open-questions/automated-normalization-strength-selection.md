---
created_at: '2026-05-14T05:23:13Z'
source_papers:
- '[[arxiv-260513678-three-stage-learning-unlocks-strong-performance-in-simple-mo]]'
title: Automated Normalization Strength Selection
---

**Background:** Normalization methods such as Reversible Instance Normalization (RevIN) are used to address non-stationarity in time series by removing local statistics, but these methods often treat local mean and variance as nuisances rather than as potentially predictive information.

**Question / Future Work:** There is a need to develop methods for automatically determining the optimal strength of instance-level statistic removal for normalization. Current techniques often rely on fixed, dataset-specific hyperparameters to balance between mitigating distribution shift and preserving predictive state information, and a more robust, automated approach would improve generalizability.

**Why It Matters:** Selecting the correct normalization strength is crucial because local mean and variance are not always pure nuisance factors; depending on the dataset, they may represent distribution shift, predictive state, or both.