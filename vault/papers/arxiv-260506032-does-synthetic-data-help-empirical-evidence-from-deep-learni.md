---
# CSL-compatible fields
title: "Does Synthetic Data Help? Empirical Evidence from Deep Learning Time Series Forecasters"
author:
  - literal: "Hugo Cazaux"
  - literal: "Eyjólfur Ingi Ásgeirsson"
  - literal: "Hlynur Stefánsson"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06032"

# Custom fields
paper_id: "2605.06032"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series-forecasting"
  - "data-augmentation"
  - "deep-learning"
  - "empirical-study"
  - "low-resource-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "architecture-conditional-augmentation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:19:23Z"
created_at: "2026-05-10T05:19:23Z"
---

# Does Synthetic Data Help? Empirical Evidence from Deep Learning Time Series Forecasters

**Authors**: Hugo Cazaux, Eyjólfur Ingi Ásgeirsson, Hlynur Stefánsson
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06032](https://arxiv.org/abs/2605.06032)

## Summary

This paper conducts a large-scale empirical study to assess the impact of synthetic data augmentation on deep learning time series forecasting. Through 4,218 systematic trials, the authors find that the effectiveness of synthetic data is highly dependent on the architecture, with channel-mixing models showing improvements while channel-independent models often suffer degradation. The study provides clear guidelines for practitioners, highlighting the utility of synthetic data in low-resource settings and the relative reliability of Seasonal-Trend generators compared to other methods.

## Key Contributions

- Conducts a large-scale evaluation of synthetic data augmentation across 4,218 experimental runs involving five architectures and seven datasets.
- Demonstrates that synthetic data performance is highly architecture-conditional, consistently benefiting channel-mixing models (TimesNet, iTransformer) while degrading channel-independent models (DLinear, PatchTST).
- Identifies that while synthetic augmentation generally degrades performance on average, it provides significant gains in low-resource settings, sometimes surpassing full-data baselines.
- Provides actionable empirical guidelines, identifying the Seasonal-Trend generator as the most reliable augmentation method and warning against hard curriculum switching.

## Open Questions & Future Work

- [[synthetic-time-series-transferability-bottleneck]]

## Key Concepts

- [[architecture-conditional-augmentation]]: The performance impact of time series data augmentation is heavily dependent on the model's channel-modeling paradigm.

## Archivist Review

I approved one concept capturing the architecture-conditional nature of data augmentation and one open question focused on the transferability of synthetic signals. I rejected the original candidate open question in favor of a more concise version that aligns better with existing vault terminology. The review focused on identifying structural insights that inform how forecasting models interact with synthetic data.

### Approved Concepts
- Architecture-Conditional Augmentation: Highlights a fundamental interaction between model inductive bias (channel-mixing vs. channel-independent) and data distribution, a critical consideration for future time series model design.

### Approved Open Questions
- Synthetic Time Series Transferability: Vital for transitioning from empirical trial-and-error to systematic, reliable synthesis methods in time series forecasting.

### Rejected Candidates
- [open_question] Generalization of Synthetic Time Series (`synthetic-ts-generalization-bottleneck`) - other: Renamed for clarity and conciseness to better fit the vault's standard naming conventions.

## Links

- [Abstract](https://arxiv.org/abs/2605.06032)
- [PDF](https://arxiv.org/pdf/2605.06032)

