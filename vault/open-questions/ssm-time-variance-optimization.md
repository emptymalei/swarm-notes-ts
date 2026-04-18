---
created_at: '2026-04-18T04:51:32Z'
source_papers:
- '[[arxiv-260415174-mambasl-exploring-single-layer-mamba-for-time-series-classif]]'
title: Optimizing SSM Time Variance
---

**Background:** State Space Models (SSMs) provide flexibility by employing time-variant (TV) parameters for state transitions, but the optimal balance between these and time-invariant (TI) parameters remains poorly understood across different task domains.

**Question / Future Work:** There is a need to systematically characterize the relationship between time series dataset properties and the optimal time-variance configuration of SSM parameters (e.g., Δ, B, C matrices) to guide the design of future architectures in non-language domains.

**Why It Matters:** As SSMs gain traction in time series, determining when to enforce stationarity (TI) versus when to allow adaptability (TV) is fundamental to reducing architectural search spaces and improving transferability.

**Evidence:** These observations support our hypothesis that while the time variance of Δ and B can be dataset-specific, that of C has limited impact.