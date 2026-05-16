---
created_at: '2026-05-16T05:14:04Z'
source_papers:
- '[[arxiv-260514069-surf-a-generative-model-for-multivariate-irregular-time-seri]]'
title: Foundation Models for Event Streams
---

**Background:** Temporal point processes often require numerical integration or specific parametric forms for intensity that limit their ability to transfer across diverse event-stream domains.

**Question / Future Work:** Determining the architectural requirements and data scale necessary to move from domain-specific event forecasting models to universal foundation models for asynchronous event streams remains a fundamental research challenge.

**Why It Matters:** This bottleneck captures the transition from task-specific forecasting to general-purpose temporal modeling, which is essential for advancing foundation model development in time-series and event streams.

**Evidence:** our six-datasets pre-training corpus is sufficient to demonstrate cross-dataset transfer but remains orders of magnitude smaller than language and vision corpora; scaling is the key milestone for foundation-scale models of asynchronous event streams.