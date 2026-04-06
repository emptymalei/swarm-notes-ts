---
created_at: '2026-04-06T05:02:24Z'
source_papers:
- '[[arxiv-260402928-new-robust-streaming-dmd-with-forecasting]]'
title: Data Forgetting in Streaming DMD
---

**Background:** Streaming variants of the Dynamic Mode Decomposition (DMD) algorithm typically aggregate streaming observations into compact cross-product matrices to achieve computational efficiency.

**Question / Future Work:** Developing computationally efficient methods to perform 'data forgetting' or sliding-window truncation within aggregated cross-product representations remains an open challenge, as it currently requires access to original snapshot data which contradicts the goal of streaming, memory-bounded execution.

**Why It Matters:** Effective forgetting is essential for maintaining model performance in non-stationary environments where system dynamics drift over time.