---
# CSL-compatible fields
title: "PAMod: Modeling Cyclical Shifts via Phase-Amplitude Modulation for Non-stationary Time Series Forecasting"
author:
  - literal: "Yingbo Zhou"
  - literal: "Yutong Ye"
  - literal: "Shuhao Li"
  - literal: "Rui Qian"
  - literal: "Qiang Huang"
  - literal: "Lemao Liu"
  - literal: "Li Sun"
  - literal: "Dejing Dou"
issued:
  date-parts:
    - [2026, 5, 1]
url: "https://arxiv.org/abs/2605.00466"

# Custom fields
paper_id: "2605.00466"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "non-stationary"
  - "dynamic-adaptation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "phase-amplitude-modulation-for-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-04T05:15:37Z"
created_at: "2026-05-04T05:15:37Z"
---

# PAMod: Modeling Cyclical Shifts via Phase-Amplitude Modulation for Non-stationary Time Series Forecasting

**Authors**: Yingbo Zhou, Yutong Ye, Shuhao Li, Rui Qian, Qiang Huang, Lemao Liu, Li Sun, Dejing Dou
**Date**: 2026-05-01
**Paper ID**: [arxiv:2605.00466](https://arxiv.org/abs/2605.00466)

## Summary

PAMod addresses the non-stationary nature of time series by moving beyond the static distribution assumptions of reversible normalization methods. Instead, it models cyclical mean and variance shifts using a lightweight phase-amplitude modulation mechanism applied to normalized representations. The framework effectively learns periodic embeddings to perform dynamic denormalization, achieving improved forecasting accuracy and computational efficiency across twelve benchmarks. The proposed modulation technique is modular and can be easily integrated into existing time-series models as a plug-and-play component.

## Key Contributions

- Introduces PAMod, a framework that models non-stationary cyclical shifts via phase-amplitude modulation in normalized feature space.
- Proves that modulation in normalized space is mathematically equivalent to dynamic denormalization of forecasts.
- Achieves state-of-the-art results on twelve standard time-series forecasting benchmarks while requiring fewer computational resources than existing methods.

## Open Questions & Future Work

- [[adaptive-periodicity-learning-for-forecasting]]

## Key Concepts

- [[phase-amplitude-modulation-for-forecasting]]: A technique that models cyclical distribution shifts by applying phase and amplitude adjustments to normalized feature representations.

## Archivist Review

I approved the core modulation mechanism as a reusable concept for adaptive time-series representation and the open question regarding periodicity learning. I rejected no candidates because only one of each category was proposed, and both met the high bar for novelty and architectural importance in time-series research. I ensured the nomenclature was updated to be more descriptive for the vault.

### Approved Concepts
- Phase-Amplitude Modulation for Forecasting: It provides a novel, mathematically grounded mechanism to handle non-stationary time series by learning periodic embeddings for dynamic denormalization, serving as a modular alternative to standard reversible normalization.

### Approved Open Questions
- Adaptive Periodicity Learning: This addresses a significant hyperparameter bottleneck that limits the robustness and generalizability of cycle-aware forecasting models in scenarios where periodicity is not constant or known a priori.

## Links

- [Abstract](https://arxiv.org/abs/2605.00466)
- [PDF](https://arxiv.org/pdf/2605.00466)

