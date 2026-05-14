---
# CSL-compatible fields
title: "Three-Stage Learning Unlocks Strong Performance in Simple Models for Long-Term Time Series Forecasting"
author:
  - literal: "Zhenan Yu"
  - literal: "Guangxin Jiang"
  - literal: "Jin Yang"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13678"

# Custom fields
paper_id: "2605.13678"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series-forecasting"
  - "mlp"
  - "linear-models"
  - "training-paradigm"
  - "channel-independence"
architectures:
  []
datasets:
  []
concept_slugs:
  - "stair-stagewise-temporal-adaptation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:23:13Z"
created_at: "2026-05-14T05:23:13Z"
---

# Three-Stage Learning Unlocks Strong Performance in Simple Models for Long-Term Time Series Forecasting

**Authors**: Zhenan Yu, Guangxin Jiang, Jin Yang
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13678](https://arxiv.org/abs/2605.13678)

## Summary

This paper addresses the trend toward increasing architectural complexity in long-term time series forecasting by proposing STAIR, a training paradigm that unlocks the performance of simple models. STAIR decomposes learning into three progressive stages: shared temporal dynamic learning, channel-specific individualization, and cross-variable residual refinement. By replacing complex components with this stagewise training approach, the authors achieve competitive forecasting accuracy using simple shallow MLP and linear backbones across nine benchmark datasets.

## Key Contributions

- Introduced STAIR, a three-stage training paradigm that enables shallow MLPs and linear models to achieve state-of-the-art performance on long-term time series forecasting.
- Developed alpha-RevIN, a normalization technique that mitigates the overly aggressive distribution constraints imposed by standard RevIN in channel-independent settings.
- Empirically demonstrated that optimizing training strategy (shared-to-individual fine-tuning) can outperform complex architectural priors on nine standard long-term forecasting benchmarks.

## Open Questions & Future Work

- [[automated-normalization-strength-selection]]

## Key Concepts

- [[stair-stagewise-temporal-adaptation]]: A three-stage training paradigm for time series forecasting that decomposes the learning process into shared temporal dynamics, channel-specific adaptation, and cross-variable residual learning.

## Archivist Review

I approved the STAIR concept as it introduces a distinct training-centric paradigm for time series forecasting that reframes the model complexity debate. The open question on normalization strength was approved for its focus on the fundamental tension between noise removal and information retention in time series. Other candidates were rejected for being overly broad or duplicating existing concerns about residual modeling efficiency.

### Approved Concepts
- Stagewise Temporal Adaptation via Individualization and Residual Learning (STAIR): It defines a novel paradigm shift from architectural complexity to strategic training stages (shared, individual, residual) for time series models.

### Approved Open Questions
- Automated Normalization Strength Selection: Selecting the correct normalization strength is crucial because local mean and variance are not always pure nuisance factors; depending on the dataset, they may represent distribution shift, predictive state, or both.

### Rejected Candidates
- [open_question] Efficient Cross-Variable Residual Modeling (`efficient-cross-variable-residual-modeling`) - duplicate_existing: This is a broad algorithmic goal that overlaps with existing research into residual modules and architectural efficiency rather than a precise, distinct research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.13678)
- [PDF](https://arxiv.org/pdf/2605.13678)

