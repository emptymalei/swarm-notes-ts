---
created_at: '2026-05-09T05:11:15Z'
source_papers:
- '[[arxiv-260506032-does-synthetic-data-help-empirical-evidence-from-deep-learni]]'
title: Architectural gating of synthetic data receptiveness
---

**Background:** Deep learning models for time series forecasting often exhibit different sensitivities to synthetic data based on whether they process channels independently or jointly.

**Question / Future Work:** The impact of synthetic data is highly dependent on model architecture, with current benchmarks suggesting channel-mixing models benefit while channel-independent models are often harmed. Future research is required to determine the specific architectural features, inductive biases, and training dynamics that gate this receptiveness to synthetic data and whether these findings hold across broader classes of foundation models.

**Why It Matters:** Identifying the core architectural bottlenecks is essential for developing future forecasting architectures that are inherently robust to synthetic data mismatch and capable of leveraging diverse synthetic distributions.

**Evidence:** The effect is sharply architecture-conditional: channel-mixing models (TimesNet, iTransformer) benefit in the majority of trials, while channel-independent models (DLinear, PatchTST) are consistently degraded.