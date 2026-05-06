---
# CSL-compatible fields
title: "Training-Free Probabilistic Time-Series Forecasting with Conformal Seasonal Pools"
author:
  - literal: "Valery Manokhin"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03789"

# Custom fields
paper_id: "2605.03789"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "probabilistic-forecasting"
  - "conformal-prediction"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "conformal-seasonal-pools-csp"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:11:44Z"
created_at: "2026-05-06T05:11:44Z"
---

# Training-Free Probabilistic Time-Series Forecasting with Conformal Seasonal Pools

**Authors**: Valery Manokhin
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03789](https://arxiv.org/abs/2605.03789)

## Summary

This paper introduces Conformal Seasonal Pools (CSP), a training-free approach to probabilistic time-series forecasting that generates predictions by combining seasonal empirical and residual draws. By avoiding parameter estimation, CSP delivers significantly better interval calibration and computational efficiency compared to learned non-parametric baselines like DeepNPTS. Empirical evaluations across six benchmark datasets show that CSP provides superior reliability and speed, offering a critical safeguard against the poor coverage failure modes common in complex learned forecasters.

## Key Contributions

- Introduces Conformal Seasonal Pools (CSP), a training-free probabilistic forecasting method that achieves state-of-the-art calibration.
- Demonstrates significant performance improvements over DeepNPTS on six benchmark datasets, achieving higher empirical coverage and superior CRPS scores.
- Provides a 500x speedup in inference time compared to learned non-parametric models by eliminating training requirements.

## Open Questions & Future Work

- [[time-series-conformal-coverage-guarantees]]

## Key Concepts

- [[conformal-seasonal-pools-csp]]: A training-free probabilistic time-series forecasting method that uses conformal empirical and residual draws around a seasonal naive baseline to ensure interval calibration.

## Archivist Review

I approved the CSP concept because it introduces a distinct, training-free methodology that effectively challenges existing neural non-parametric forecasters. The open question was approved for its fundamental role in addressing the theoretical limitations of applying conformal inference to non-exchangeable time-series data. I rejected the datasets as they are common benchmark names rather than novel, domain-specific sources.

### Approved Concepts
- Conformal Seasonal Pools (CSP): Establishes a robust, training-free baseline that outperforms state-of-the-art neural methods in interval calibration and computational efficiency.

### Approved Open Questions
- Time-Series Conformal Coverage Guarantees: Theoretical validation is essential for establishing reliable prediction intervals in decision-critical forecasting applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.03789)
- [PDF](https://arxiv.org/pdf/2605.03789)

