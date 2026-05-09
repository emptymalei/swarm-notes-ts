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
  - "time-series-forecasting"
  - "non-stationary-time-series"
  - "model-agnostic-aggregation"
  - "probabilistic-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "melo-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:09:55Z"
created_at: "2026-05-09T05:09:55Z"
---

# Hedging Memory Horizons for Non-Stationary Prediction via Online Aggregation

**Authors**: Yutong Wang, Yannig Goude, Qiwei Yao
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06541](https://arxiv.org/abs/2605.06541)

## Summary

This paper introduces MELO, a model-agnostic online aggregation method for time-series forecasting under non-stationary conditions where the optimal memory length for adaptation is unknown. By wrapping base-predictor pools in exponentially weighted least-squares (EWLS) experts and using a parameter-free aggregation rule, the method effectively tracks shifting regimes without requiring explicit change-point detection or external covariates. Extensive evaluation on French electricity-load data during the COVID-19 pandemic confirms significant improvements over baseline aggregation methods.

## Key Contributions

- Introduces MELO, a model-agnostic online aggregation framework that hedges across multiple forgetting factors using EWLS adaptation experts.
- Establishes deterministic oracle inequalities demonstrating competitiveness with the best time-varying combinations of base predictors.
- Demonstrates 34.7% RMSE reduction on French electricity-load forecasting during COVID-19 without external regime covariates, outperforming state-of-the-art baselines.

## Open Questions & Future Work

- [[dynamic-memory-scale-grid-expansion]]

## Key Concepts

- [[melo-framework]]: A model-agnostic framework that aggregates base predictors across multiple adaptation scales using exponentially weighted least-squares experts and a parameter-free online aggregation rule.

## Archivist Review

I have approved the MELO framework as a central contribution for handling non-stationary time series through online aggregation of memory horizons. I also approved an open question regarding the dynamic expansion of memory scales, which represents a substantial research bottleneck in adaptive online learning. Other candidates were either too specific to the paper or did not meet the bar for long-term knowledge retention.

### Approved Concepts
- MELO Framework: The paper's core contribution, providing a robust, model-agnostic way to handle unknown non-stationary memory horizons in online prediction.

### Approved Open Questions
- Dynamic memory-scale grid expansion: Dynamically adjusting the memory-scale grid could mitigate the limitations of a fixed geometric grid, which might be too coarse or incorrectly placed if the drift characteristics change drastically over time.

### Rejected Candidates
- [dataset] French national electricity-load dataset (`french-national-electricity-load-dataset`) - not_reusable: Dataset is a specific, non-publicly named study-local collection rather than a standard benchmark or widely accessible research resource.

## Links

- [Abstract](https://arxiv.org/abs/2605.06541)
- [PDF](https://arxiv.org/pdf/2605.06541)

