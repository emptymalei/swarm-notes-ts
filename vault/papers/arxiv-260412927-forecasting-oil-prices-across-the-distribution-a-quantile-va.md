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
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:02:37Z"
created_at: "2026-04-15T05:02:37Z"
---

# Forecasting Oil Prices Across the Distribution: A Quantile VAR Approach

**Authors**: Hilde C. Bjornland, Nicolas Hardy, Dimitris Korobilis
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12927](https://arxiv.org/abs/2604.12927)

## Summary

This paper introduces a Quantile Bayesian Vector Autoregression (QBVAR) to forecast oil prices, specifically capturing asymmetries across different quantiles of the conditional distribution that standard mean-focused models neglect. By training on monthly data from 1975 to 2025, the authors demonstrate that the model significantly improves both median point forecasts and tail risk assessment. Their findings highlight the importance of quantile-specific dynamics for capturing downside risks, especially during periods of market volatility and financial instability.

## Key Contributions

- Introduces a Quantile Bayesian Vector Autoregression (QBVAR) to model conditional distributions and capture asymmetric predictor effects in oil prices.
- Demonstrates that QBVAR improves median point forecast accuracy by 2-5% compared to standard Bayesian VARs.
- Achieves 10-25% improvement in left-tail risk forecasting, particularly during crisis episodes, by leveraging uncertainty and financial condition indicators.

## Open Questions & Future Work

- [[upside-tail-risk-forecasting-challenges]]

## Archivist Review

The paper presents an empirical application of Quantile Bayesian VARs to oil price forecasting. I rejected the model name (QBVAR) as it is a standard extension of known techniques rather than a novel, reusable architecture. I approved one open question regarding the asymmetry in tail risk predictability, as this touches on a fundamental limitation in current time-series forecasting paradigms.

### Approved Open Questions
- Upside Oil Price Risk Forecasting: Understanding the fundamental disconnect between forecasting downside versus upside tail risks is critical for improving systemic risk management tools in commodity markets.

### Rejected Candidates
- [concept] Quantile Bayesian Vector Autoregression (`qbvar`) - not_novel: This is a specific application of established Bayesian Vector Autoregression (BVAR) and Quantile Regression techniques, which do not individually or collectively qualify as a reusable architectural novelty for this vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.12927)
- [PDF](https://arxiv.org/pdf/2604.12927)

