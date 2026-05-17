---
# CSL-compatible fields
title: "Adaptive Long-Run Variance Thresholding for Sparse Covariance Estimation in High-Dimensional Time Series"
author:
  - literal: "Wenhao Zhang"
  - literal: "Zhaoxing Gao"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14491"

# Custom fields
paper_id: "2605.14491"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-long-run-variance-thresholding"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:24:30Z"
created_at: "2026-05-17T05:24:30Z"
---

# Adaptive Long-Run Variance Thresholding for Sparse Covariance Estimation in High-Dimensional Time Series

**Authors**: Wenhao Zhang, Zhaoxing Gao
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14491](https://arxiv.org/abs/2605.14491)

## Summary

This paper addresses the challenge of sparse covariance matrix estimation in high-dimensional time series, where standard thresholding methods designed for independent data fail due to temporal dependence. The authors introduce an adaptive thresholding procedure that incorporates long-run variance into entry-specific thresholds to handle autocorrelation. Theoretical analysis proves the estimator's consistency under the spectral norm and confirms its optimal convergence rate and support recovery capabilities. Empirical results on synthetic and real-world datasets, including gene expression and stock returns, validate the method's effectiveness over existing techniques.

## Key Contributions

- Proposes a thresholding procedure for sparse covariance estimation that accounts for temporal dependence using long-run variance.
- Proves consistency under the spectral norm and optimal convergence rates for the proposed estimator.
- Establishes support recovery consistency and demonstrates superiority over standard independent-data thresholding methods in simulations and real-world applications.

## Open Questions & Future Work

- [[theoretical-justification-tuning-parameter-selection-time-series]]

## Key Concepts

- [[adaptive-long-run-variance-thresholding]]: A thresholding procedure for sparse covariance estimation in high-dimensional time series that adapts to temporal dependence by incorporating long-run variance.

## Archivist Review

The submitted candidates directly address the foundational statistical challenge of adapting sparse covariance estimation for dependent time series. The approved concept and open question are technically precise, address a clear methodological gap, and are highly reusable for future high-dimensional time series research. No datasets were approved as the ones mentioned in the paper were generic applications rather than core benchmarks defined by the authors.

### Approved Concepts
- Adaptive Long-Run Variance Thresholding: Provides a novel mechanism to adapt covariance thresholding specifically for high-dimensional time series, overcoming failures of methods designed for independent data.

### Approved Open Questions
- Theoretical justification for parameter selection: Reliable tuning parameter selection is critical for the practical utility and statistical consistency of thresholding estimators in high-dimensional settings.

## Links

- [Abstract](https://arxiv.org/abs/2605.14491)
- [PDF](https://arxiv.org/pdf/2605.14491)

