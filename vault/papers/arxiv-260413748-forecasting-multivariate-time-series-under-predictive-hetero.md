---
# CSL-compatible fields
title: "Forecasting Multivariate Time Series under Predictive Heterogeneity: A Validation-Driven Clustering Framework"
author:
  - literal: "Ziling Ma"
  - literal: "Ángel López Oriona"
  - literal: "Hernando Ombao"
  - literal: "Ying Sun"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13748"

# Custom fields
paper_id: "2604.13748"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "multivariate-time-series"
  - "clustering"
  - "predictive-uncertainty"
architectures:
  []
datasets:
  []
concept_slugs:
  - "validation-driven-adaptive-pooling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:06:11Z"
created_at: "2026-04-16T05:06:11Z"
---

# Forecasting Multivariate Time Series under Predictive Heterogeneity: A Validation-Driven Clustering Framework

**Authors**: Ziling Ma, Ángel López Oriona, Hernando Ombao, Ying Sun
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13748](https://arxiv.org/abs/2604.13748)

## Summary

This paper addresses the challenge of predictive heterogeneity in multivariate time series forecasting by proposing a validation-driven adaptive pooling framework. Unlike traditional methods that rely on representation similarity, this approach partitions data based on out-of-sample validation loss, ensuring that cluster assignments directly correlate with predictive risk. The framework includes a leakage-free fallback mechanism that defaults to a global model when specialization fails to provide gains, effectively mitigating risks of negative transfer. Empirical results on large-scale traffic data demonstrate that the method achieves improved robustness and accuracy across varying degrees of heterogeneity.

## Key Contributions

- Introduces a validation-driven clustering framework that optimizes data partitions based on out-of-sample predictive risk rather than feature similarity.
- Implements a leakage-free fallback mechanism that dynamically switches between local and global models to prevent performance degradation.
- Demonstrates superior robustness and predictive accuracy on large-scale traffic datasets compared to existing adaptive pooling and global modeling baselines.

## Open Questions & Future Work

- [[soft-fuzzy-specialization-for-mts-forecasting]]

## Key Concepts

- [[validation-driven-adaptive-pooling]]: A framework for multivariate time series forecasting that clusters time series based on out-of-sample predictive performance rather than latent representation similarity.

## Archivist Review

The proposed validation-driven adaptive pooling framework is a valuable, reusable contribution that bridges the gap between clustering and predictive risk optimization. I approved the core concept and a related open question regarding fuzzy specialization to guide future work beyond hard partitioning. I rejected the proposal to integrate conformal prediction as it represents a standard methodological extension rather than a fundamental research bottleneck.

### Approved Concepts
- Validation-Driven Adaptive Pooling: It shifts the paradigm of clustering for time series from representation learning to predictive-risk alignment, offering a principled way to balance global model efficiency and local specialization.

### Approved Open Questions
- Soft or fuzzy specialization for MTS forecasting: Hard partitioning often misses the nuanced, overlapping predictive dynamics present in complex multivariate time series. Moving toward fuzzy clustering could lead to more nuanced model selection and potentially higher predictive accuracy in environments with fluid transitions between predictive regimes.

### Rejected Candidates
- [open_question] Conformal uncertainty quantification (`conformal-prediction-integration`) - other: Combining two established techniques is a standard research trajectory rather than a fundamental unresolved bottleneck in the forecasting field.

## Links

- [Abstract](https://arxiv.org/abs/2604.13748)
- [PDF](https://arxiv.org/pdf/2604.13748)

