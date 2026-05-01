---
created_at: '2026-05-01T05:21:56Z'
source_papers:
- '[[arxiv-260428149-explainable-load-forecasting-with-covariate-informed-time-se]]'
title: Efficient SHAP Estimation for TSFMs
---

**Background:** SHAP-based explainability for time series models often relies on computationally expensive sampling-based approximations to handle input feature subsets.

**Question / Future Work:** Developing efficient SHAP estimation methods for time series foundation models that scale to large feature sets and high-resolution temporal inputs is crucial for critical infrastructure deployments. Current approaches often require exhaustive coalition evaluation or high-variance sampling, limiting the granularity of feature attribution.

**Why It Matters:** This addresses a primary bottleneck in making foundation models transparent for operational energy forecasting where feature sets are often large and diverse.

**Evidence:** Computational efficiency could be substantially improved by estimating SHAP values from subsets of feature group combinations rather than exhaustively evaluating all 2^N coalitions