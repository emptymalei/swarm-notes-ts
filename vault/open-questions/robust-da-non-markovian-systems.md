---
created_at: '2026-05-16T05:13:35Z'
source_papers:
- '[[arxiv-260514285-forcingdas-unified-and-robust-data-assimilation-via-diffusio]]'
title: Robust DA in Non-Markovian Systems
---

**Background:** In complex dynamical systems where observations form only a partial projection of a higher-dimensional latent state, the sequence of observations is inherently non-Markovian. Existing per-frame learned DA methods assume Markovian dynamics and suffer from error accumulation over long temporal horizons.

**Question / Future Work:** It remains an open challenge to develop models that effectively capture long-horizon temporal dependencies and hidden degrees of freedom in non-Markovian dynamical systems, preventing the performance degradation and error accumulation observed in autoregressive per-frame models.

**Why It Matters:** Robustness to non-Markovian data is essential for real-world scientific applications like weather and climate forecasting where full state observability is impossible.