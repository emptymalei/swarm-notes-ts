---
# CSL-compatible fields
title: "Forecasting Oil Prices Across the Distribution: A Quantile VAR Approach"
author:
  - literal: "Hilde C. Bjornland"
  - literal: "Nicolas Hardy"
  - literal: "Dimitris Korobilis"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12927"

# Custom fields
paper_id: "2604.12927"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "quantile-bayesian-vector-autoregression-qbvar"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:07:37Z"
created_at: "2026-04-16T05:07:37Z"
---

# Forecasting Oil Prices Across the Distribution: A Quantile VAR Approach

**Authors**: Hilde C. Bjornland, Nicolas Hardy, Dimitris Korobilis
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12927](https://arxiv.org/abs/2604.12927)

## Summary

This paper introduces a Quantile Bayesian Vector Autoregression (QBVAR) to model real oil prices, enabling researchers to forecast across the entire conditional distribution rather than focusing solely on the mean. By allowing predictor effects to vary across quantiles, the model captures complex asymmetries in oil market dynamics. Empirical results demonstrate significant gains in both median point forecasts and tail-risk assessment compared to traditional Bayesian VAR and stochastic volatility models. The approach proves particularly effective at predicting downside risk during periods of significant market disruption.

## Key Contributions

- Introduces a Quantile Bayesian Vector Autoregression (QBVAR) to capture asymmetric predictor effects across the conditional distribution of real oil prices.
- Demonstrates that QBVAR improves median point forecast accuracy by 2-5% over standard BVAR baselines.
- Achieves a 10-25% improvement in left-tail risk forecasting, particularly during identified economic crisis episodes.

## Open Questions & Future Work

- [[hybrid-tail-risk-forecasting]]

## Key Concepts

- [[quantile-bayesian-vector-autoregression-qbvar]]: A vector autoregressive framework that models the conditional distribution of time series by allowing predictor effects to vary across quantiles.

## Archivist Review

The review focused on identifying core methodological contributions and substantive research bottlenecks. I approved the Quantile Bayesian Vector Autoregression (QBVAR) as a foundational concept for distribution-aware time series modeling and the open question regarding hybridizing quantile and stochastic volatility models to resolve asymmetries in tail-risk forecasting performance. Other candidate concepts and datasets were rejected as they were either too specific to the paper's local domain or failed to provide sufficient, novel, and reusable modeling primitives.

### Approved Concepts
- Quantile Bayesian Vector Autoregression (QBVAR): Provides a methodology for modeling asymmetric predictor effects across the entire conditional distribution, moving beyond mean-only forecasting in vector autoregressive settings.

### Approved Open Questions
- Hybrid Models for Upside Risks: Improving upside tail risk prediction is essential for energy market risk management, where models currently struggle compared to downside risk assessment.

## Links

- [Abstract](https://arxiv.org/abs/2604.12927)
- [PDF](https://arxiv.org/pdf/2604.12927)

