---
created_at: '2026-04-28T05:15:20Z'
source_papers:
- '[[arxiv-260424041-end-to-end-learning-for-partially-observed-time-series-with]]'
title: Joint Imputation-Forecasting Optimization
---

**Background:** Incomplete data is common in temporal forecasting, but handling missing values often remains decoupled from downstream model optimization.

**Question / Future Work:** Investigate how to optimize jointly for imputation and downstream task performance to prevent error propagation and improve predictive consistency in long-horizon, high-missingness scenarios.

**Why It Matters:** This is a fundamental bottleneck in time series research; current approaches are often disconnected, leading to suboptimal performance and lack of standardized end-to-end evaluation.

**Evidence:** Dealing with incomplete data often leads to fragmented workflows where imputation and downstream predictive tasks are entirely decoupled, resulting in suboptimal performance.