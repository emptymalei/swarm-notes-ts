---
# CSL-compatible fields
title: "Hedging Memory Horizons for Non-Stationary Prediction via Online Aggregation"
author:
  - literal: "Yutong Wang"
  - literal: "Yannig Goude"
  - literal: "Qiwei Yao"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06541"

# Custom fields
paper_id: "2605.06541"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "online-learning"
  - "distribution-shift"
  - "forecast-reconciliation"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "melo-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:18:05Z"
created_at: "2026-05-10T05:18:05Z"
---

# Hedging Memory Horizons for Non-Stationary Prediction via Online Aggregation

**Authors**: Yutong Wang, Yannig Goude, Qiwei Yao
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06541](https://arxiv.org/abs/2605.06541)

## Summary

The paper introduces MELO (Memory-hedged Exponentially Weighted Least-Squares Online aggregation) to address online prediction under non-stationary regimes where the optimal adaptation memory is unknown. MELO aggregates forecasts from base-predictors across various forgetting factors using a parameter-free online rule, requiring only lightweight recursive updates. It provides theoretical guarantees through oracle inequalities and demonstrates practical robustness by outperforming covariate-assisted benchmarks in electricity-load forecasting during the COVID-19 pandemic.

## Key Contributions

- Proposes MELO, a model-agnostic aggregation framework that wraps base-predictor pools with multi-scale EWLS adaptation experts.
- Establishes deterministic oracle inequalities demonstrating that MELO competes with the best time-varying affine combinations of base predictors.
- Demonstrates superior performance on French electricity-load forecasting, achieving a 34.7% RMSE reduction over base-only MLpol without needing exogenous policy covariates.

## Open Questions & Future Work

- [[diversity-diagnostics-online-aggregation]]

## Key Concepts

- [[melo-framework]]: A model-agnostic online aggregation method that hedges across multiple memory scales to handle distribution shifts and regime transitions.

## Archivist Review

The MELO framework is approved as a reusable method for online aggregation under non-stationarity, as it addresses the common forecasting bottleneck of unknown optimal adaptation scales. The open question regarding the relationship between base-model diversity and aggregation gain was approved as a substantial and tracked issue in online time-series learning. No datasets were approved, as the study used standard utility-load electricity data that is already represented in the vault or is routine.

### Approved Concepts
- MELO: It provides a novel, model-agnostic framework for handling non-stationarity by aggregating forecasts across multiple forgetting factors, requiring only lightweight recursive updates.

### Approved Open Questions
- Aggregation gain and diversity: Understanding the relationship between base-model diversity and aggregation utility is essential for assessing the applicability of online meta-learning approaches in real-world time-series forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2605.06541)
- [PDF](https://arxiv.org/pdf/2605.06541)

