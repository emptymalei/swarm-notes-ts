---
# CSL-compatible fields
title: "Sequential Structure in Intraday Futures Data: LSTM vs Gradient Boosting on MNQ"
author:
  - literal: "Mathias Mesfin"
issued:
  date-parts:
    - [2026, 5, 18]
url: "https://arxiv.org/abs/2605.17724"

# Custom fields
paper_id: "2605.17724"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "finance"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-19T05:30:21Z"
created_at: "2026-05-19T05:30:21Z"
---

# Sequential Structure in Intraday Futures Data: LSTM vs Gradient Boosting on MNQ

**Authors**: Mathias Mesfin
**Date**: 2026-05-18
**Paper ID**: [arxiv:2605.17724](https://arxiv.org/abs/2605.17724)

## Summary

This paper evaluates the predictive power of sequential intraday OHLCV patterns in Micro E-Mini Nasdaq 100 (MNQ) futures by comparing Gradient Boosting and LSTM models. Using a 944-day dataset, the study employs strict walk-forward validation to determine if models can outperform a 51.8% base rate. Results show no statistically significant edge for either architecture, with performance metrics remaining below the base rate, suggesting that single-instrument five-minute financial data at this scale is insufficient for reliable machine learning-based forecasting.

## Key Contributions

- Documented an empirical evaluation comparing Gradient Boosting and LSTM architectures for intraday directional prediction in MNQ futures.
- Demonstrated that four years of 5-minute OHLCV data for a single instrument are insufficient to achieve statistically significant predictive performance over the base rate.
- Identified high feature importance instability across walk-forward folds, suggesting reliance on noise fitting rather than stable structural signals.

## Links

- [Abstract](https://arxiv.org/abs/2605.17724)
- [PDF](https://arxiv.org/pdf/2605.17724)

