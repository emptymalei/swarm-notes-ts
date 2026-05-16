---
# CSL-compatible fields
title: "SurF: A Generative Model for Multivariate Irregular Time Series Forecasting"
author:
  - literal: "Mohammad R. Rezaei"
  - literal: "Tejas Balaji"
  - literal: "Rahul G. Krishnan"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.14069"

# Custom fields
paper_id: "2605.14069"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "generative-modeling"
  - "irregular-time-series"
  - "time-series-forecasting"
  - "foundation-models"
  - "asynchronous-event-streams"
architectures:
  []
datasets:
  []
concept_slugs:
  - "time-rescaling-theorem-for-event-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:14:04Z"
created_at: "2026-05-16T05:14:04Z"
---

# SurF: A Generative Model for Multivariate Irregular Time Series Forecasting

**Authors**: Mohammad R. Rezaei, Tejas Balaji, Rahul G. Krishnan
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.14069](https://arxiv.org/abs/2605.14069)

## Summary

SurF addresses the limitations of tokenization and numerical quadrature in irregularly sampled multivariate event stream modeling by utilizing the Time Rescaling Theorem (TRT). The model establishes a learnable bijection between heterogeneous event sequences and i.i.d. unit-rate exponential noise, allowing for cross-dataset training. It introduces scalable cumulative intensity parameterizations and a Transformer-based encoder, achieving competitive performance on six real-world benchmarks while demonstrating potential as a foundation model for asynchronous streams.

## Key Contributions

- Proposes SurF, a generative model using the Time Rescaling Theorem (TRT) to achieve a learnable bijection between heterogeneous event streams and unit-rate exponential noise.
- Develops three efficient cumulative intensity parameterizations that scale effectively to long-sequence event forecasting.
- Demonstrates state-of-the-art performance on multiple real-world benchmarks, showing superior zero-shot generalization capabilities compared to existing classical and neural-autoregressive baselines.

## Open Questions & Future Work

- [[scaling-irregular-event-streams-to-foundation-models]]

## Key Concepts

- [[time-rescaling-theorem-for-event-forecasting]]: A method for modeling asynchronous event streams by learning a bijection between irregular event sequences and unit-rate exponential noise.

## Archivist Review

I approved the TRT mapping as a core conceptual contribution because it offers a principled alternative to numerical quadrature in event stream modeling. I also approved the open question regarding scaling these models to foundation-level as it frames a clear research transition from specialist models to general-purpose temporal modeling. Other candidates were either too specific to the proposed model architecture or lacked sufficient novelty for standalone vault notes.

### Approved Concepts
- Time Rescaling Theorem for Event Forecasting: It transforms the problem of modeling irregularly sampled events into a standardized mapping to uniform noise, providing a principled foundation for multivariate event stream modeling that avoids expensive numerical quadrature.

### Approved Open Questions
- Foundation Models for Event Streams: This bottleneck captures the transition from task-specific forecasting to general-purpose temporal modeling, which is essential for advancing foundation model development in time-series and event streams.

## Links

- [Abstract](https://arxiv.org/abs/2605.14069)
- [PDF](https://arxiv.org/pdf/2605.14069)

