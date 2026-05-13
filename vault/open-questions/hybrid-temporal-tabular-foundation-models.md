---
created_at: '2026-05-13T05:23:29Z'
source_papers:
- '[[arxiv-260512200-investigating-simple-target-covariate-relationships-for-chro]]'
title: Hybrid Temporal-Tabular Foundation Architectures
---

**Background:** Modern time series foundation models (TSFMs) demonstrate varying proficiency in balancing temporal auto-regression with exogenous covariate integration depending on the underlying task structure.

**Question / Future Work:** There is a need to develop unified foundation model architectures that effectively synthesize explicit temporal dependency modeling—typical of sequence-based TSFMs—with the robust in-context regression capabilities characteristic of tabular foundation models. Such hybrid models would be better suited to handle tasks where the target is governed by a complex mixture of historical temporal patterns and instantaneous covariate-driven relationships.

**Why It Matters:** The paper demonstrates that existing TSFMs specialize either in temporal modeling or tabular regression, leading to performance trade-offs based on the relative importance of these components in a specific forecasting task. Creating a model that bridges this gap is essential for building more general-purpose forecasting tools.

**Evidence:** In particular, a foundation architecture that combines explicit temporal dependency modeling, as in Chronos-2, with in-context regression capabilities inspired by TabPFN-TS, could represent an interesting direction for covariate-aware time series foundation models.