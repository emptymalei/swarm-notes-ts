---
created_at: '2026-05-02T05:07:18Z'
source_papers:
- '[[arxiv-260428149-explainable-load-forecasting-with-covariate-informed-time-se]]'
title: Scalable SHAP for TSFMs
---

**Background:** Shapley Additive Explanations (SHAP) are computationally intensive because the number of model evaluations required scales exponentially with the number of features. While temporal and covariate masking strategies for Time Series Foundation Models (TSFMs) can mitigate this by avoiding background data sampling, the cost remains significant as the number of coalitions to evaluate grows with the number of groups.

**Question / Future Work:** Future research is required to optimize the computational efficiency of SHAP for TSFMs by avoiding exhaustive evaluation of all feature coalition combinations. Specifically, there is a need for methods that can estimate SHAP values from strategic subsets of feature group combinations, allowing for finer-grained temporal groupings than currently feasible. This is especially critical for models with higher inference costs, such as TabPFN-TS, and for scenarios involving larger, more complex feature sets.

**Why It Matters:** As TSFMs become more complex and the number of input covariates increases, the current exhaustive evaluation approach becomes a bottleneck for real-time or scalable model interpretability in operational environments. Developing sub-sampling or approximation strategies is essential for the practical deployment of these explainability methods.