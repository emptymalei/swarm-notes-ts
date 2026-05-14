---
# CSL-compatible fields
title: "Amortized Neural Clustering of Time Series based on Statistical Features"
author:
  - literal: "Ángel López-Oriona"
  - literal: "Ying Sun"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13128"

# Custom fields
paper_id: "2605.13128"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "amortized-neural-clustering-of-time-series"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:24:54Z"
created_at: "2026-05-14T05:24:54Z"
---

# Amortized Neural Clustering of Time Series based on Statistical Features

**Authors**: Ángel López-Oriona, Ying Sun
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13128](https://arxiv.org/abs/2605.13128)

## Summary

This paper presents an amortized neural inference framework for time series clustering that learns to partition data based on statistical features like autocorrelations. By training on simulated data to approximate optimal partitioning rules, the method avoids the limitations of traditional, heuristic-based clustering algorithms. The approach allows for automated determination of the number of clusters and demonstrates superior empirical accuracy compared to classical methods on both synthetic and real-world financial time series.

## Key Contributions

- Introduces an algorithm-agnostic neural framework that approximates optimal clustering rules directly from statistical feature representations.
- Eliminates the necessity for explicit prior specification of cluster shapes or manual selection of clustering objective functions and heuristics.
- Outperforms traditional methods like K-means and K-medoids in clustering accuracy while offering an optional automated mechanism for cluster count determination.

## Open Questions & Future Work

- [[fuzzy-amortized-clustering]]

## Key Concepts

- [[amortized-neural-clustering-of-time-series]]: An approach that trains neural networks to approximate optimal clustering partitions using time series statistical features.

## Archivist Review

I approved the concept of amortized neural clustering because it represents a distinct departure from traditional iterative heuristics in time series grouping. The open question regarding fuzzy extensions was approved because it addresses a fundamental limitation in mapping ambiguous or overlapping temporal regimes that hard partitioning methods struggle to resolve. I rejected the hybrid training question as it borders on boilerplate improvement for simulation-based models.

### Approved Concepts
- Amortized Neural Clustering of Time Series: Shifts the paradigm of time series clustering from iterative heuristics to a learned, amortized inference framework that avoids manual objective function specification.

### Approved Open Questions
- Fuzzy Amortized Neural Clustering: Fuzzy clustering provides a richer and more realistic representation of data where boundaries between clusters are not well-defined, which is a common occurrence in time series analysis.

## Links

- [Abstract](https://arxiv.org/abs/2605.13128)
- [PDF](https://arxiv.org/pdf/2605.13128)

