---
# CSL-compatible fields
title: "Channel-wise Retrieval for Multivariate Time Series Forecasting"
author:
  - literal: "Junhyeok Kang"
  - literal: "Jun Seo"
  - literal: "Soyeon Park"
  - literal: "Sangjun Han"
  - literal: "Seohui Bae"
  - literal: "Hyeokjun Choe"
  - literal: "Soonyoung Lee"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.05543"

# Custom fields
paper_id: "2604.05543"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "craft-channel-wise-retrieval-augmented-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:56:05Z"
created_at: "2026-04-08T04:56:05Z"
---

# Channel-wise Retrieval for Multivariate Time Series Forecasting

**Authors**: Junhyeok Kang, Jun Seo, Soyeon Park, Sangjun Han, Seohui Bae, Hyeokjun Choe, Soonyoung Lee
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.05543](https://arxiv.org/abs/2604.05543)

## Summary

CRAFT is a novel retrieval-augmented multivariate time series forecasting framework that addresses the limitations of channel-agnostic retrieval strategies. By performing retrieval independently for each channel, the model captures distinct periodicities and spectral profiles inherent to different variables. The approach utilizes a two-stage pipeline, combining time-domain pruning via sparse relation graphs with frequency-domain similarity ranking to enhance prediction accuracy and computational efficiency.

## Key Contributions

- Introduces CRAFT, a channel-wise retrieval-augmented forecasting framework that accounts for inter-variable heterogeneity.
- Implements a two-stage retrieval process using time-domain sparse relation graphs for pruning and frequency-domain spectral similarity for ranking.
- Demonstrates superior forecasting accuracy and efficiency across seven public benchmarks compared to channel-agnostic retrieval baselines.

## Open Questions & Future Work

- [[adaptive-retrieval-parameter-selection]]

## Key Concepts

- [[craft-channel-wise-retrieval-augmented-forecasting]]: A multivariate time series forecasting framework that performs retrieval independently for each channel to capture distinct spectral and periodic profiles.

## Archivist Review

The paper introduces an effective architectural pattern for multivariate forecasting by moving from channel-agnostic to channel-wise retrieval. I approved the framework name as a concept and generalized the open question regarding parameter tuning to be more broadly applicable to retrieval-augmented time series models. All other candidates were rejected as they were either too narrow or better captured by these primary entries.

### Approved Concepts
- CRAFT (Channel-wise Retrieval-Augmented Forecasting): It formalizes a shift from channel-agnostic to channel-specific retrieval in multivariate forecasting, addressing inter-variable heterogeneity.

### Approved Open Questions
- Adaptive Retrieval Parameter Selection: Static hyperparameters for retrieval limit the model's ability to effectively handle channels with varying noise levels or spectral characteristics.

### Rejected Candidates
- [open_question] Adaptive Channel-wise Retrieval Parameters (`adaptive-channel-wise-retrieval`) - duplicate_existing: Renamed for better generality and alignment with existing vault naming conventions.

## Links

- [Abstract](https://arxiv.org/abs/2604.05543)
- [PDF](https://arxiv.org/pdf/2604.05543)

