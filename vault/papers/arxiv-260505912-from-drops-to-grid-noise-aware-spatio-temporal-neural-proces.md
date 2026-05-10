---
# CSL-compatible fields
title: "From Drops to Grid: Noise-Aware Spatio-Temporal Neural Process for Rainfall Estimation"
author:
  - literal: "Rafael Pablos Sarabia"
  - literal: "Joachim Nyborg"
  - literal: "Morten Birk"
  - literal: "Ira Assent"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05912"

# Custom fields
paper_id: "2605.05912"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "spatio-temporal"
  - "uncertainty-estimation"
  - "neural-processes"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dropstogrid"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:19:45Z"
created_at: "2026-05-10T05:19:45Z"
---

# From Drops to Grid: Noise-Aware Spatio-Temporal Neural Process for Rainfall Estimation

**Authors**: Rafael Pablos Sarabia, Joachim Nyborg, Morten Birk, Ira Assent
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05912](https://arxiv.org/abs/2605.05912)

## Summary

DropsToGrid is a Neural Process-based framework designed for high-resolution rainfall estimation by densifying sparse and noisy observations from private weather stations. The method integrates multi-scale temporal attention with spatial radar data to address the challenges of localized, skewed, and irregular precipitation patterns. Experimental results indicate that DropsToGrid achieves accurate, well-calibrated spatio-temporal estimates even in data-scarce and cross-regional scenarios, outperforming existing operational and deep learning baselines.

## Key Contributions

- Introduced DropsToGrid, a Neural Process-based model that generates dense, continuous rainfall maps from sparse, noisy private weather station inputs.
- Demonstrated superior performance in cross-regional rainfall estimation and uncertainty calibration compared to operational and deep learning benchmarks.
- Leveraged multi-scale feature extraction and temporal attention to successfully fuse irregular sensor data with spatial radar context.

## Open Questions & Future Work

- [[robust-radar-surface-rainfall-fusion]]
- [[multivariate-probabilistic-data-assimilation]]

## Key Concepts

- [[dropstogrid]]: A Neural Process-based framework for generating dense, uncertainty-aware rainfall fields by fusing irregular sensor data and spatial radar context.

## Archivist Review

The paper provides a distinct framework, DropsToGrid, for the challenging task of spatial densification of sparse and noisy time-series data using neural processes. The open questions approved address significant hurdles in multi-modal fusion of atmospheric data and the transition toward multivariate probabilistic assimilation, which are central themes in modern meteorological ML.

### Approved Concepts
- DropsToGrid: Central method proposed by the paper for high-resolution rainfall estimation from sparse, noisy inputs.

### Approved Open Questions
- Robust Radar-Surface Rainfall Fusion: The paper highlights that radar and station measurements capture complementary physical quantities and that the mapping is complex, non-local, and context-dependent. Improving this fusion is central to the performance of densification models.
- Multivariate Probabilistic Data Assimilation: This addresses the need for comprehensive, multivariate weather forecasting systems and leverages the existing architecture to handle more complex environmental modeling.

## Links

- [Abstract](https://arxiv.org/abs/2605.05912)
- [PDF](https://arxiv.org/pdf/2605.05912)

