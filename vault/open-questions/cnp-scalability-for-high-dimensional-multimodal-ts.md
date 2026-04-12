---
created_at: '2026-04-12T05:02:31Z'
source_papers:
- '[[arxiv-260408418-exploring-temporal-representation-in-neural-processes-for-mu]]'
title: CNP scalability for multimodal TS
---

**Background:** Conditional Neural Processes treat input data as sets, which can obscure temporal ordering and long-range dependencies in sequential data. The sufficiency of these architectures for high-dimensional, complex, and multimodal time series remains an open research area.

**Question / Future Work:** There is a lack of comprehensive empirical evaluation regarding the scalability and robustness of Conditional Neural Process (CNP) architectures when applied to high-dimensional, multimodal, and temporally extended sensory data. Specifically, determining if current set-based encoding strategies are sufficient for capturing long-term dependencies and complex multimodal correlations without losing essential temporal context is a critical bottleneck.

**Why It Matters:** This is fundamental to determining if CNPs can serve as a viable alternative to autoregressive models for robotics and time-series forecasting, as current implementations often struggle to maintain temporal consistency in non-synthetic scenarios.