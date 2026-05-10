---
created_at: '2026-05-10T05:18:05Z'
source_papers:
- '[[arxiv-260506541-hedging-memory-horizons-for-non-stationary-prediction-via-on]]'
title: Aggregation gain and diversity
---

**Background:** Online aggregation methods for non-stationary prediction often rely on the base forecaster pool exhibiting sufficient diversity to cover different regimes. When base models are nearly collinear or make highly correlated errors, the potential gain from online affine combinations is diminished.

**Question / Future Work:** The paper identifies residual diversity as a critical bottleneck for the effectiveness of online aggregation. Investigating more robust diagnostics for expected aggregation gain, as well as methods to dynamically expand the memory-scale grid, remains an open problem for scaling this framework across diverse time-series settings.

**Why It Matters:** Understanding the relationship between base-model diversity and aggregation utility is essential for assessing the applicability of online meta-learning approaches in real-world time-series forecasting.

**Evidence:** The limitation is that large gains require both exploitable non-stationarity and a base pool with residual diversity. When base predictors make highly correlated errors, the EWLS combination space has limited room to help.