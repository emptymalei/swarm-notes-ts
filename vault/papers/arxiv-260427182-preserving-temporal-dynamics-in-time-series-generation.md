---
# CSL-compatible fields
title: "Preserving Temporal Dynamics in Time Series Generation"
author:
  - literal: "Ci Lin"
  - literal: "Futong Li"
  - literal: "Tet Yeap"
  - literal: "Iluju Kiringa"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.27182"

# Custom fields
paper_id: "2604.27182"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "generative-modeling"
  - "data-augmentation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mcmc-based-temporal-alignment"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:24:03Z"
created_at: "2026-05-01T05:24:03Z"
---

# Preserving Temporal Dynamics in Time Series Generation

**Authors**: Ci Lin, Futong Li, Tet Yeap, Iluju Kiringa
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27182](https://arxiv.org/abs/2604.27182)

## Summary

This paper addresses the degradation of synthetic time series fidelity caused by temporal drift and distribution shift in existing GAN frameworks. The authors demonstrate that relying solely on marginal distribution matching is insufficient, proposing a model-agnostic MCMC-based framework to enforce consistency with empirical transition laws. Experiments across several generative models show that incorporating this transition-preserving correction significantly improves both autocorrelation alignment and downstream forecasting performance.

## Key Contributions

- Identifies that GAN-based time series generation often suffers from distribution shift and temporal drift due to neglecting transition statistics.
- Introduces a model-agnostic MCMC-based framework that enforces consistency with empirical transition laws between neighboring time points.
- Demonstrates consistent improvement in autocorrelation alignment and predictive metrics across five generative models and four datasets (Lorenz, Licor, ETTh, ILI).

## Open Questions & Future Work

- [[mcmc-integration-in-generative-training]]

## Key Concepts

- [[mcmc-based-temporal-alignment]]: A model-agnostic MCMC framework that enforces consistency with empirical transition statistics to improve synthetic time-series fidelity.

## Archivist Review

I approved the MCMC-based temporal alignment concept for its model-agnostic utility in mitigating cumulative temporal drift, a common issue in time-series generation. The open question regarding MCMC integration in training was approved because it addresses the shift from post-hoc correction to structural training objectives, which is a major research frontier. I rejected the datasets because they are common benchmarks that do not represent novel contributions in this context.

### Approved Concepts
- MCMC-based Temporal Alignment: Provides a model-agnostic correction mechanism to mitigate temporal drift and distribution shift in synthetic time-series generation, which is a fundamental challenge for autoregressive and generative models.

### Approved Open Questions
- MCMC Integration in Generative Training: This explores the transition from external, post-hoc correction to end-to-end differentiable regularization, which is critical for long-horizon time-series generation.

## Links

- [Abstract](https://arxiv.org/abs/2604.27182)
- [PDF](https://arxiv.org/pdf/2604.27182)

