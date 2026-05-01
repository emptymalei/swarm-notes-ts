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
  - "circuits"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:22:44Z"
created_at: "2026-05-01T05:22:44Z"
---

# Probabilistic Circuits for Irregular Multivariate Time Series Forecasting

**Authors**: Christian Klötergens, Vijaya Krishna Yalavarthi, Lars Schmidt-Thieme
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27814](https://arxiv.org/abs/2604.27814)

## Summary

This paper presents CircuITS, an architecture designed for irregular multivariate time series (IMTS) forecasting that leverages probabilistic circuits to capture complex channel dependencies. By construction, the model guarantees consistent joint distributions, overcoming common challenges in balancing expressivity with valid marginalization. Empirical evaluations show that CircuITS outperforms existing state-of-the-art baselines in both joint and marginal density estimation tasks.

## Key Contributions

- Introduces CircuITS, a novel architecture for forecasting irregular multivariate time series using probabilistic circuits to ensure structural validity of joint distributions.
- Addresses the trade-off between model expressivity and consistent marginalization in joint probabilistic modeling.
- Demonstrates superior performance in joint and marginal density estimation on four real-world benchmark datasets compared to state-of-the-art methods.

## Open Questions & Future Work

- [[optimal-channel-ordering-spn]]

## Key Concepts

- [[circuits]]: A probabilistic circuit-based architecture for joint density estimation and forecasting of irregular multivariate time series.

## Archivist Review

I approved CircuITS as a representative architecture for probabilistic circuit-based time series modeling. I also approved the open question regarding channel ordering in SPNs because it identifies a fundamental structural bottleneck in recursive probabilistic models. No datasets were approved as the candidates listed were generic, non-specific descriptions.

### Approved Concepts
- CircuITS: The paper introduces CircuITS as the central methodological innovation for handling irregular multivariate time series via probabilistic circuits, providing a framework that ensures consistent joint marginalization.

### Approved Open Questions
- Optimal channel ordering in SPNs: Understanding how channel ordering affects the joint density approximation in recursive probabilistic circuits is vital for scaling these models to higher-dimensional datasets where correlations are highly non-uniform across channels.

## Links

- [Abstract](https://arxiv.org/abs/2604.27814)
- [PDF](https://arxiv.org/pdf/2604.27814)

