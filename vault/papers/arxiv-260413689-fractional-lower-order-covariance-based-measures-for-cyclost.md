---
# CSL-compatible fields
title: "Fractional lower-order covariance-based measures for cyclostationary time series with heavy-tailed distributions: application to dependence testing and model order identification"
author:
  - literal: "Wojciech Żuławiński"
  - literal: "Agnieszka Wyłomańska"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13689"

# Custom fields
paper_id: "2604.13689"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "fractional-lower-order-covariance-floc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:54:19Z"
created_at: "2026-04-18T04:54:19Z"
---

# Fractional lower-order covariance-based measures for cyclostationary time series with heavy-tailed distributions: application to dependence testing and model order identification

**Authors**: Wojciech Żuławiński, Agnieszka Wyłomańska
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13689](https://arxiv.org/abs/2604.13689)

## Summary

This paper addresses the limitations of traditional cyclostationary analysis by introducing fractional lower-order covariance (FLOC) to handle heavy-tailed time series with infinite variance. The authors define new autodependence measures—the periodic fractional lower-order autocorrelation function (peFLOACF) and its partial counterpart (peFLOPACF)—which serve as robust alternatives to standard autocorrelation functions. These measures are applied to perform dependence testing and model order identification for Periodic Autoregressive and Moving Average processes. Numerical simulations and a practical case study involving air pollution data demonstrate the superior utility of these methods in non-Gaussian, infinite-variance scenarios.

## Key Contributions

- Introduces peFLOACF and peFLOPACF as robust generalizations of periodic autocorrelation for infinite-variance cyclostationary time series.
- Develops a portmanteau test for dependence and an order-identification method for Periodic Autoregressive/Moving Average (PAR/PMA) models under heavy-tailed conditions.
- Validates the methodology through simulation and application to air pollution time series data.

## Open Questions & Future Work

- [[frequency-domain-floc-cyclostationarity]]

## Key Concepts

- [[fractional-lower-order-covariance-floc]]: A statistical measure for analyzing heavy-tailed time series where traditional covariance is undefined due to infinite variance.

## Archivist Review

The paper provides a foundational robust method (FLOC) for analyzing heavy-tailed cyclostationary processes, which is a significant departure from standard covariance-based methods. I have approved FLOC as a core concept and noted the extension to frequency-domain analysis as a primary research bottleneck. These provide a robust, reusable framework for time-series analysis in non-Gaussian, infinite-variance regimes.

### Approved Concepts
- Fractional lower-order covariance (FLOC): Provides a robust alternative to traditional autocovariance for signals with infinite variance, which are common in real-world time series.

### Approved Open Questions
- Frequency-domain FLOC-cyclostationary analysis: Frequency-domain analysis is standard in cyclostationary processing for signal feature extraction and classification. Establishing a frequency-domain framework for FLOC-cyclostationary processes would provide essential tools for handling infinite-variance signals in spectral signal processing applications.

## Links

- [Abstract](https://arxiv.org/abs/2604.13689)
- [PDF](https://arxiv.org/pdf/2604.13689)

