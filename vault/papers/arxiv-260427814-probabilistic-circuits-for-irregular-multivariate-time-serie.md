---
# CSL-compatible fields
title: "Probabilistic Circuits for Irregular Multivariate Time Series Forecasting"
author:
  - literal: "Christian Klötergens"
  - literal: "Vijaya Krishna Yalavarthi"
  - literal: "Lars Schmidt-Thieme"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27814"

# Custom fields
paper_id: "2604.27814"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "circuits-imts"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:07:59Z"
created_at: "2026-05-02T05:07:59Z"
---

# Probabilistic Circuits for Irregular Multivariate Time Series Forecasting

**Authors**: Christian Klötergens, Vijaya Krishna Yalavarthi, Lars Schmidt-Thieme
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27814](https://arxiv.org/abs/2604.27814)

## Summary

This paper introduces CircuITS, a novel architecture designed for probabilistic forecasting of irregular multivariate time series (IMTS). By leveraging probabilistic circuits, the model effectively captures intricate channel dependencies while maintaining structural guarantees for valid joint distribution marginalization. Empirical evaluation across four real-world datasets shows that the proposed approach outperforms existing state-of-the-art methods in both joint and marginal density estimation tasks.

## Key Contributions

- Introduces CircuITS, an architecture based on probabilistic circuits that ensures valid joint distributions for irregular multivariate time series.
- Demonstrates that CircuITS provides superior joint and marginal density estimation compared to current state-of-the-art baselines on four real-world benchmarks.
- Addresses the trade-off between model expressivity and marginal consistency in irregular multivariate forecasting.

## Open Questions & Future Work

- [[dynamic-channel-ordering-pc-imts]]

## Key Concepts

- [[circuits-imts]]: A probabilistic circuit-based architecture for irregular multivariate time series forecasting that guarantees consistent marginalization.

## Archivist Review

I approved the CircuITS architecture as it represents a clear, reusable application of probabilistic circuits to the problem of maintaining marginal consistency in IMTS. I also approved the open question regarding dynamic channel ordering, as it highlights a fundamental architectural bottleneck (computational intractability of optimal ordering) inherent to this class of probabilistic models. No datasets were approved as the paper utilizes standard, non-unique benchmarks.

### Approved Concepts
- CircuITS: It introduces a specific application of Probabilistic Circuits to the structural consistency problem in irregular multivariate time series forecasting.

### Approved Open Questions
- Dynamic Channel Ordering in PCs: Channel ordering defines the inductive bias of the recursive decomposition in circuit-based models, and its optimization is a known bottleneck for capacity scaling in high-dimensional multivariate settings.

## Links

- [Abstract](https://arxiv.org/abs/2604.27814)
- [PDF](https://arxiv.org/pdf/2604.27814)

