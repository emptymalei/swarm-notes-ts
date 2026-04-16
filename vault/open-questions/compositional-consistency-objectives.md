---
created_at: '2026-04-16T05:07:58Z'
source_papers:
- '[[arxiv-260412794-stable-fine-time-step-long-horizon-turbulence-prediction-wit]]'
title: Compositional Consistency Objectives
---

**Background:** Neural operator surrogates for turbulent flow forecasting often struggle with long-horizon autoregressive stability and the choice of optimal prediction time-interval, especially at fine temporal resolutions.

**Question / Future Work:** Future work should investigate multi-step training objectives that explicitly enforce compositional consistency across different time-step strides to further improve the stability of autoregressive rollouts beyond simple data-fidelity optimization.

**Why It Matters:** Compositional consistency is a theoretical property of exact flow maps; enforcing it during training is a promising avenue to reduce error accumulation and improve long-term physical fidelity in neural PDE surrogates.

**Evidence:** Future work includes [...] multi-step objectives that enforce compositional consistency across strides