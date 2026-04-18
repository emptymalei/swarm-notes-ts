---
# CSL-compatible fields
title: "Generalized Autoregressive Multivariate Models: From Binary to Poisson"
author:
  - literal: "Anna Bykhovskaya"
  - literal: "Nour Meddahi"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.14394"

# Custom fields
paper_id: "2604.14394"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "binary-autoregressive-time-series-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:53:07Z"
created_at: "2026-04-18T04:53:07Z"
---

# Generalized Autoregressive Multivariate Models: From Binary to Poisson

**Authors**: Anna Bykhovskaya, Nour Meddahi
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.14394](https://arxiv.org/abs/2604.14394)

## Summary

This paper introduces a GARCH-type framework for modeling binary autoregressive time series where Bernoulli success probabilities evolve based on past information. The authors establish the existence and uniqueness of stationary solutions, even under the discontinuities characteristic of binary data. Crucially, they derive a theoretical connection showing that aggregates of these binary processes converge to a Poisson autoregression, providing a formal micro-foundation for count-based models. Empirical effectiveness is demonstrated through maximum likelihood estimation on S&P 100 data.

## Key Contributions

- Introduces a GARCH-type autoregressive framework for binary data that handles nonlinearity, network effects, and cross-sectional dependence.
- Proves existence and uniqueness of stationary solutions for binary processes using a coupling argument that addresses data discontinuities.
- Establishes a theoretical link showing that aggregates of these binary processes converge to a Poisson autoregression under rare-events scaling.

## Key Concepts

- [[binary-autoregressive-time-series-framework]]: A GARCH-like framework for binary time series where success probabilities depend on past outcomes and probabilities.

## Archivist Review

I approved the binary autoregressive framework as it provides a clear, reusable methodology for modeling discrete time-series dynamics using GARCH-type influences, which is a significant theoretical contribution. I rejected the S&P 100 dataset as it is a standard, widely used financial index that does not require a dedicated vault note. No open questions were proposed, so I did not add any.

### Approved Concepts
- Binary Autoregressive Time Series Framework: Establishes a GARCH-type dynamic framework specifically for Bernoulli variables, allowing for nonlinearities and network interactions in discrete time series.

### Rejected Candidates
- [dataset] S&P 100 (`s-p-100`) - low_impact: This is a standard market index frequently used in literature and does not warrant a standalone research vault note.

## Links

- [Abstract](https://arxiv.org/abs/2604.14394)
- [PDF](https://arxiv.org/pdf/2604.14394)

