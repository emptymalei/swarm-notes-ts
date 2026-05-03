---
created_at: '2026-05-03T05:14:01Z'
source_papers:
- '[[arxiv-260428149-explainable-load-forecasting-with-covariate-informed-time-se]]'
title: Efficient SHAP for TSFMs
---

**Background:** Shapley Additive Explanations (SHAP) typically require exhaustive evaluation of all possible feature coalitions, leading to exponential computational complexity that becomes intractable for large-scale time series models.

**Question / Future Work:** Investigating efficient estimation of SHAP values for TSFMs by leveraging their flexibility in context window masking, specifically through subset feature group combination evaluation rather than exhaustive computation. This is crucial for enabling model transparency in safety-critical infrastructure where high-dimensional time series data is processed by large models.

**Why It Matters:** Scalable feature attribution is essential for the reliable deployment of foundation models in industrial settings, where black-box behavior is unacceptable.