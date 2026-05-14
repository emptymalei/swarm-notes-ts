---
created_at: '2026-05-14T05:25:15Z'
source_papers:
- '[[arxiv-260512992-spikeprophecy-a-large-scale-benchmark-for-autoregressive-neu]]'
title: Modeling and evaluating sub-Poisson neurons
---

**Background:** Sub-Poisson neurons, which exhibit highly regular firing, are consistently the most difficult to predict in current autoregressive neural forecasting models due to biophysical factors and metric limitations.

**Question / Future Work:** Research is needed to develop dispersion-aware loss functions or modeling techniques that can better account for sub-Poisson regularity. Developing metrics or loss functions that disentangle genuine phase-prediction failures from timing jitter artifacts is necessary to avoid imposing an artificial performance floor on models and to better assess true forecasting capability for these neuron types.

**Why It Matters:** Standard aggregate metrics currently mask model improvements in regular-firing neurons, leading to misinterpretations of model performance and hindering the development of architectures capable of capturing precise intrinsic neural dynamics.

**Evidence:** These neurons therefore impose a hard noise floor on aggregate metrics: ~0.07 regardless of model quality. ... the sub-Poisson floor motivates dispersion-aware losses (e.g., Conway–Maxwell–Poisson).