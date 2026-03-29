---
created_at: '2026-03-29T20:15:47Z'
source_papers:
- '[[openalex-2603.25597-spatiotemporal-system-forecasting-with-irregular-time-steps]]'
title: Scalable Attention for Long Sequences
---

**Background:** The complexity of transformer models, particularly the self-attention mechanism, scales quadratically with the length of the input sequence.

**Question / Future Work:** Investigate and implement alternatives to the standard quadratic complexity self-attention mechanism, such as local or sparse attention methods, to improve the scalability of the P-STMAE framework for processing extremely long spatiotemporal sequences.

**Why It Matters:** Scaling self-attention is a critical bottleneck for applying transformer-based sequence models, like P-STMAE, to very long time series data common in long-term climate forecasting.

**Evidence:** The quadratic complexity of the transformer’s global self-attention poses challenges for processing very long sequences. Exploring alternatives like local or sparse attention mechanisms could enhance scalability.