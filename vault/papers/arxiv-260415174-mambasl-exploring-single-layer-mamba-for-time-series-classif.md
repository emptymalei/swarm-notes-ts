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
  - "time-series-classification"
  - "state-space-models"
  - "benchmarking"
architectures:
  []
datasets:
  - "uea-dataset"
concept_slugs:
  - "mambasl"
dataset_slugs:
  - "uea-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:05:25Z"
created_at: "2026-04-19T05:05:25Z"
---

# MambaSL: Exploring Single-Layer Mamba for Time Series Classification

**Authors**: Yoo-Min Jung, Leekyung Kim
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.15174](https://arxiv.org/abs/2604.15174)

## Summary

This paper introduces MambaSL, a single-layer Mamba architecture designed to optimize state space model performance for time series classification (TSC). By identifying and implementing TSC-specific refinements to the selective SSM and projection components, the authors show that a minimal architecture can outperform existing complex models. Furthermore, the work addresses systemic issues in current TSC research by establishing a unified evaluation protocol across all 30 UEA datasets for 20 baseline models, providing a foundation for future reproducible research.

## Key Contributions

- Introduces MambaSL, a single-layer state space model architecture tailored for time series classification through targeted redesign of SSM and projection layers.
- Provides a comprehensive, unified re-evaluation of 20 baseline models across all 30 UEA datasets to address existing reproducibility and coverage gaps in the field.
- Demonstrates state-of-the-art performance on the full UEA benchmark, showing that simplified Mamba architectures can serve as robust backbones for TSC.

## Open Questions & Future Work

- [[mamba-tsc-backbone-optimization]]

## Key Concepts

- [[mambasl]]: A single-layer Mamba architecture optimized for time series classification through targeted redesign of selective SSM and projection layers.

## Archivist Review

I approved MambaSL as a concept because it represents a clear, reusable methodology for adapting SSMs to specific sequence classification constraints. I also included the UEA archive as a standard benchmark dataset, noting that the paper's contribution to consistent evaluation across this set is its secondary impact. The open question was approved for tracking the fundamental research gap between general sequence modeling and task-specific TSC backbones.

### Approved Concepts
- MambaSL: It establishes a design methodology for reducing the complexity of state space models while maintaining performance for time series classification, highlighting the potential of lightweight architectures as sequence backbones.

### Approved Open Questions
- Optimizing Mamba for TSC: Understanding these architectural trade-offs is crucial for establishing whether SSMs can become a robust, standard, and efficient choice for TSC backbones across diverse applications.

## Datasets

- [[uea-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.15174)
- [PDF](https://arxiv.org/pdf/2604.15174)

