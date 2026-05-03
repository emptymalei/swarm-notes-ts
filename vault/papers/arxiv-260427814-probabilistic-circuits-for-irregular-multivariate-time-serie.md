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
  - "probabilistic-forecasting"
  - "time-series-forecasting"
  - "multivariate-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "circuits-imts"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:14:44Z"
created_at: "2026-05-03T05:14:44Z"
---

# Probabilistic Circuits for Irregular Multivariate Time Series Forecasting

**Authors**: Christian Klötergens, Vijaya Krishna Yalavarthi, Lars Schmidt-Thieme
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27814](https://arxiv.org/abs/2604.27814)

## Summary

The paper introduces CircuITS, an architecture designed for forecasting irregular multivariate time series (IMTS) while maintaining consistent joint probability distributions. By utilizing probabilistic circuits, the model addresses common issues in multivariate forecasting, such as unreliable marginalization and poor handling of dependencies between channels. Empirical results demonstrate that CircuITS provides more reliable uncertainty quantification and superior density estimation compared to current baselines.

## Key Contributions

- Proposes CircuITS, an architecture that leverages probabilistic circuits to perform joint probabilistic modeling of irregular multivariate time series.
- Demonstrates that CircuITS structurally guarantees valid joint distributions and superior marginalization compared to existing baseline models.
- Achieves state-of-the-art performance in joint and marginal density estimation across four real-world irregular multivariate time series datasets.

## Open Questions & Future Work

- [[optimal-channel-ordering-spn]]

## Key Concepts

- [[circuits-imts]]: A probabilistic circuit-based architecture for irregular multivariate time series forecasting that guarantees valid joint distributions.

## Archivist Review

I approved CircuITS as a core mechanism for structural consistency in probabilistic time series modeling and included the open question regarding channel ordering in SPNs, as this reflects a fundamental complexity bottleneck for high-dimensional circuit-based architectures. No datasets were approved because the paper used generic datasets without proposing a specific new, named benchmark artifact.

### Approved Concepts
- CircuITS: CircuITS introduces a mechanism to enforce structural consistency in joint distributions for multivariate forecasting by utilizing probabilistic circuits, addressing a known gap in existing irregular time series models.

### Approved Open Questions
- Optimal channel ordering in SPNs: The order of channel aggregation significantly dictates the capacity of the model to capture inter-channel dependencies, representing a fundamental performance bottleneck for circuit-based forecasting models.

## Links

- [Abstract](https://arxiv.org/abs/2604.27814)
- [PDF](https://arxiv.org/pdf/2604.27814)

