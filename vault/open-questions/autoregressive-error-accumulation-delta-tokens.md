---
created_at: '2026-04-07T04:52:57Z'
source_papers:
- '[[arxiv-260404913-a-frame-is-worth-one-token-efficient-generative-world-modeli]]'
title: Mitigating Autoregressive Error Accumulation
---

**Background:** Autoregressive generation models often suffer from error accumulation when repeatedly conditioning predictions on previous outputs, leading to temporal drift.

**Question / Future Work:** Since delta-token approaches represent features as differences, long-term autoregressive generation requires recursive reconstruction of absolute states. Investigating how to maintain scene consistency and mitigate compounded errors in this context is critical for long-horizon forecasting.

**Why It Matters:** Solving the drift and compounding error issue is essential for robust long-term temporal sequence prediction.

**Evidence:** Because delta tokens encode temporal differences, reconstructing absolute feature maps requires repeatedly decoding delta tokens conditioned on previous features. During tokenizer reconstruction, errors may compound across steps, potentially leading to feature drift.