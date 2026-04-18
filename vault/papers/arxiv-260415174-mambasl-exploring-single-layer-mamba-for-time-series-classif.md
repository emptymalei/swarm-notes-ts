---
# CSL-compatible fields
title: "MambaSL: Exploring Single-Layer Mamba for Time Series Classification"
author:
  - literal: "Yoo-Min Jung"
  - literal: "Leekyung Kim"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.15174"

# Custom fields
paper_id: "2604.15174"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "uea-dataset"
concept_slugs:
  - "mambasl"
dataset_slugs:
  - "uea-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:51:32Z"
created_at: "2026-04-18T04:51:32Z"
---

# MambaSL: Exploring Single-Layer Mamba for Time Series Classification

**Authors**: Yoo-Min Jung, Leekyung Kim
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.15174](https://arxiv.org/abs/2604.15174)

## Summary

MambaSL explores the potential of single-layer State Space Models (SSMs) for time series classification (TSC) by redesigning the selective SSM and projection layers. The authors identify TSC-specific limitations in existing research and introduce a unified evaluation protocol across all 30 UEA datasets. Their results demonstrate that MambaSL achieves state-of-the-art performance compared to 20 strong baselines, providing a more efficient and reproducible backbone for future TSC tasks.

## Key Contributions

- Introduces MambaSL, a single-layer SSM-based framework specifically optimized for time series classification.
- Redesigns selective SSM and projection layers based on four hypotheses tailored to time series data characteristics.
- Establishes a unified, reproducible benchmarking protocol across all 30 UEA datasets for 20 baseline models, setting a new standard for TSC evaluation.

## Open Questions & Future Work

- [[ssm-time-variance-optimization]]

## Key Concepts

- [[mambasl]]: A single-layer Mamba-based framework that optimizes selective SSM and projection layers specifically for time series classification.

## Archivist Review

The paper offers a compelling case for minimalist architectural design in SSMs for time series classification. I approved the MambaSL concept and the UEA dataset as they constitute the core framework and evaluation standard presented. The open question regarding SSM time variance was approved as it reflects a fundamental, unresolved architectural trade-off identified by the authors.

### Approved Concepts
- MambaSL: It challenges the assumption that deep stacking is necessary for state-space performance, demonstrating that a carefully redesigned single layer can outperform complex baselines in TSC.

### Approved Open Questions
- Optimizing SSM Time Variance: As SSMs gain traction in time series, determining when to enforce stationarity (TI) versus when to allow adaptability (TV) is fundamental to reducing architectural search spaces and improving transferability.

## Datasets

- [[uea-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.15174)
- [PDF](https://arxiv.org/pdf/2604.15174)

