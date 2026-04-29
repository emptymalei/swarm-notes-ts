---
# CSL-compatible fields
title: "Functional Autoregression Without Truncation: A Continuous-Regularization Approach"
author:
  - literal: "Yao Zhao"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25205"

# Custom fields
paper_id: "2604.25205"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "tikhonov-regularized-functional-autoregression"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:11:28Z"
created_at: "2026-04-29T05:11:28Z"
---

# Functional Autoregression Without Truncation: A Continuous-Regularization Approach

**Authors**: Yao Zhao
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25205](https://arxiv.org/abs/2604.25205)

## Summary

This paper addresses the limitations of functional autoregressive (FAR(1)) models, which typically rely on discrete truncation of principal components that is both regime-dependent and prone to sub-optimal forecast performance. The author introduces a continuous Tikhonov-regularized estimator that enables data-driven parameter selection, avoiding the instability of threshold-based truncation. Theoretical convergence rates are established, and the method demonstrates improved accuracy and stability in forecasting intraday PM10 curves compared to traditional projection-based approaches.

## Key Contributions

- Introduces a Tikhonov-regularized estimator for FAR(1) models that eliminates the need for ad-hoc discrete truncation.
- Establishes the theoretical convergence rate of $n^{-β/(2(β+1))}$ for the proposed estimator under smoothness parameter β.
- Demonstrates a 9.7% reduction in mean forecast error on intraday PM10 data compared to standard functional principal component projection methods.

## Open Questions & Future Work

- [[regularized-far-p-selection]]

## Key Concepts

- [[tikhonov-regularized-functional-autoregression]]: A functional autoregressive estimator that avoids arbitrary truncation by using a data-driven Tikhonov regularization parameter.

## Archivist Review

The paper introduces a mathematically elegant replacement for the standard, often ad-hoc, truncation approach in functional autoregressive models. The approved concept captures a reusable alternative for operator-based estimation, and the open question identifies the non-trivial challenge of extending this to higher-order lag structures (FAR(p)), which is a meaningful frontier in the field.

### Approved Concepts
- Tikhonov-regularized functional autoregression: It addresses the problem of regime-dependent truncation levels in FAR(1) models by replacing discrete truncation with continuous regularization, improving forecasting stability.

### Approved Open Questions
- Joint Regularization and Lag Selection: Generalizing the regularization framework to FAR(p) and FARX is critical for broader applicability in functional time series where dependencies often exceed a single lag or include external influences.

## Links

- [Abstract](https://arxiv.org/abs/2604.25205)
- [PDF](https://arxiv.org/pdf/2604.25205)

