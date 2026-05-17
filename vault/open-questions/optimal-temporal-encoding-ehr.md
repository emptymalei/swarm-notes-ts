---
created_at: '2026-05-17T05:25:26Z'
source_papers:
- '[[arxiv-260514227-dt-transformer-a-foundation-model-for-disease-trajectory-pre]]'
title: Optimal temporal encoding for EHRs
---

**Background:** Transformer-based models for disease trajectory prediction rely on temporal encoding schemes to represent clinical event sequences characterized by continuous time and varying intervals.

**Question / Future Work:** Determining an optimal interval-aware temporal representation that accounts for irregular clinical visit patterns and longitudinal censoring in real-world EHRs remains a major open methodological challenge.

**Why It Matters:** Temporal representation is a critical bottleneck for accurate clinical sequence modeling when dealing with non-uniform density and complex longitudinal gaps.

**Evidence:** The time encoding with age embeddings and no-event paddings may be suboptimal for real-world EHR data, where events are more tightly spaced and long-term observability and censoring are more pronounced.