---
created_at: '2026-03-29T20:18:01Z'
source_papers:
- '[[openalex-2603.25473-causal-insight-probing-temporal-models-to-extract-causal-str]]'
title: Extend probing to multi-horizon predictors
---

**Background:** Understanding directed temporal interactions in multivariate time series is essential for interpreting complex dynamical systems and the predictive models trained on them.

**Question / Future Work:** Extending the probing framework to models designed for multi-horizon forecasting rather than single-step prediction. This requires adapting the input clamping and influence signal aggregation to account for future prediction targets that depend on potentially longer historical contexts.

**Why It Matters:** Multi-horizon predictors are common in time series modeling, and adapting post-hoc probing techniques to them is essential for broader interpretability in forecasting tasks.

**Evidence:** Future work includes extending the probing framework to multi-horizon predictors and developing adaptive clamping schemes to better capture distributed or multi-lag influence patterns.