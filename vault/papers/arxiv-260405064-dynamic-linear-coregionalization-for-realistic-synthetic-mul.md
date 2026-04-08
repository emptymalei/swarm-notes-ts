---
# CSL-compatible fields
title: "Dynamic Linear Coregionalization for Realistic Synthetic Multivariate Time Series"
author:
  - literal: "Annita Vapsi"
  - literal: "Penghang Liu"
  - literal: "Saheed Obitayo"
  - literal: "Aakriti"
  - literal: "Manoj Cherukumalli"
  - literal: "Prathamesh Patil"
  - literal: "Amit Varshney"
  - literal: "Nicolas Marchesotti"
  - literal: "Elizabeth Fons"
  - literal: "Vamsi K. Potluru"
  - literal: "Manuela Veloso"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.05064"

# Custom fields
paper_id: "2604.05064"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dynamic-linear-model-of-coregionalization-dynlmc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:58:05Z"
created_at: "2026-04-08T04:58:05Z"
---

# Dynamic Linear Coregionalization for Realistic Synthetic Multivariate Time Series

**Authors**: Annita Vapsi, Penghang Liu, Saheed Obitayo, Aakriti, Manoj Cherukumalli, Prathamesh Patil, Amit Varshney, Nicolas Marchesotti, Elizabeth Fons, Vamsi K. Potluru, Manuela Veloso
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.05064](https://arxiv.org/abs/2604.05064)

## Summary

This paper introduces DynLMC, a generative framework for producing realistic synthetic multivariate time series by incorporating time-varying, regime-switching correlations and cross-channel lag structures. Addressing the limitations of static correlation assumptions in current generators, DynLMC enables more effective pretraining for foundation models for time series (FMTS). Experiments across nine benchmarks demonstrate that incorporating these dynamic dependencies significantly enhances the zero-shot forecasting performance and transferability of foundation models.

## Key Contributions

- Introduces DynLMC, a framework that models time-varying, regime-switching correlations and cross-channel lags for synthetic data generation.
- Demonstrates that fine-tuning foundation models for time series on DynLMC-generated data yields consistent zero-shot forecasting improvements.
- Evaluates performance across nine benchmarks, confirming that capturing dynamic inter-channel correlations improves transferability of foundation models.

## Open Questions & Future Work

- [[retention-adaptation-tradeoff-fmts]]

## Key Concepts

- [[dynamic-linear-model-of-coregionalization-dynlmc]]: A generative approach that models time-varying, regime-switching correlations and cross-channel lag structures to produce realistic synthetic multivariate time series.

## Archivist Review

I approved the Dynamic Linear Model of Coregionalization (DynLMC) as a novel, reusable approach to synthetic multivariate time series generation that explicitly models regime-switching inter-channel correlations. I also approved the Retention-Adaptation Trade-off in FMTS as it addresses the critical, unresolved challenge of fine-tuning black-box foundation models on synthetic data without catastrophic forgetting. Other candidates were not submitted.

### Approved Concepts
- Dynamic Linear Model of Coregionalization: It addresses the limitation of static correlations in existing synthetic data generators for multivariate time series, which is crucial for training foundation models.

### Approved Open Questions
- Retention-Adaptation Trade-off in FMTS: As more foundation models become available without public training data, developing principled methods for fine-tuning these models on new synthetic data without catastrophic forgetting is essential for practical application.

## Links

- [Abstract](https://arxiv.org/abs/2604.05064)
- [PDF](https://arxiv.org/pdf/2604.05064)

