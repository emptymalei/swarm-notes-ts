---
# CSL-compatible fields
title: "Scenario generation of intraday electricity price paths for optimal trading in continuous markets"
author:
  - literal: "Andrzej Puć"
  - literal: "Joanna Janczura"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13446"

# Custom fields
paper_id: "2605.13446"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "probabilistic-electricity-price-forecasting-pepf"
  - "quantile-based-trading-strategies-qbts"
architectures:
  []
datasets:
  []
concept_slugs:
  - "support-vector-sorting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:23:49Z"
created_at: "2026-05-14T05:23:49Z"
---

# Scenario generation of intraday electricity price paths for optimal trading in continuous markets

**Authors**: Andrzej Puć, Joanna Janczura
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13446](https://arxiv.org/abs/2605.13446)

## Summary

This paper presents an ensemble forecasting framework for intraday electricity prices in continuous markets, focusing on generating probabilistic price trajectories to support adaptive trading. The authors introduce a corrected Support Vector Regression (SVR) model to produce point forecasts, which are then extended to scenario sets representing price paths. A novel Support Vector Sorting procedure is proposed to efficiently select representative scenarios from these ensembles. Evaluation on German intraday market data shows that this approach improves both statistical accuracy and trading profitability compared to standard benchmarks.

## Key Contributions

- Introduces a corrected Support Vector Regression framework that generates probabilistic intraday electricity price trajectories.
- Develops Support Vector Sorting, a technique for selecting representative price scenarios that improves trading decision performance.
- Demonstrates that ensemble-based forecasts combined with dynamic scenario reweighting outperform naive trading benchmarks in economic terms.

## Open Questions & Future Work

- [[volatility-aware-scenario-reweighting]]
- [[incorporating-meteorological-ensembles]]

## Key Concepts

- [[support-vector-sorting]]: A technique for selecting representative price trajectory scenarios from an ensemble by leveraging support vector model characteristics.

## Archivist Review

The paper's concept, Support Vector Sorting, provides a distinct mechanism for scenario selection that is likely to be useful across various stochastic optimization tasks. I have approved two open questions that highlight significant limitations in handling volatility and exogenous meteorological data, which are perennial challenges in electricity price forecasting. The local dataset was rejected as it lacks broad scientific reusability beyond this specific case study.

### Approved Concepts
- Support Vector Sorting: Provides a structured mechanism for scenario reduction in time-series forecasting contexts, improving downstream decision-making efficiency.

### Approved Open Questions
- Volatility-aware scenario reweighting: Integrating volatility-sensitive weighting is critical for improving the robustness of adaptive trading strategies in volatile markets.
- Incorporating meteorological ensembles: Capturing the weather-dependent stochastic nature of electricity supply and demand is essential for improving forecast accuracy.

### Rejected Candidates
- [dataset] German intraday continuous market dataset (`german-intraday-continuous-market-dataset`) - low_impact: Dataset is specific to a regional exchange and not a widely applicable benchmark.

## Links

- [Abstract](https://arxiv.org/abs/2605.13446)
- [PDF](https://arxiv.org/pdf/2605.13446)

