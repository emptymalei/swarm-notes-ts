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
  - "robust-statistics"
  - "cyclostationary-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "fractional-lower-order-covariance-floc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:07:44Z"
created_at: "2026-04-17T05:07:44Z"
---

# Fractional lower-order covariance-based measures for cyclostationary time series with heavy-tailed distributions: application to dependence testing and model order identification

**Authors**: Wojciech Żuławiński, Agnieszka Wyłomańska
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13689](https://arxiv.org/abs/2604.13689)

## Summary

This paper introduces a robust framework for cyclostationary time series analysis specifically designed for data with infinite variance, where traditional autocovariance methods fail. By leveraging fractional lower-order covariance (FLOC), the authors derive new periodic autocorrelation and partial autocorrelation measures that remain stable under heavy-tailed distributions. These tools enable reliable dependence testing and model order identification for periodic autoregressive and moving average processes. The effectiveness of the proposed methodology is validated through simulations and applied to real-world air pollution data.

## Key Contributions

- Introduces the fractional lower-order covariance (FLOC) framework for cyclostationary analysis, extending dependence measures to infinite-variance processes.
- Develops periodic fractional lower-order autocorrelation (peFLOACF) and partial autocorrelation (peFLOPACF) functions as robust alternatives to classical periodic measures.
- Demonstrates superior utility in dependence testing and model order identification for periodic autoregressive and moving average models under heavy-tailed conditions.

## Open Questions & Future Work

- [[asymptotic-distribution-pefloacf-peflopacf]]

## Key Concepts

- [[fractional-lower-order-covariance-floc]]: A robust alternative to classical covariance for cyclostationary analysis of heavy-tailed time series.

## Archivist Review

The proposed concept (FLOC) is a fundamental, reusable tool for non-Gaussian time series analysis. The identified open question accurately targets the lack of asymptotic theory, which is a common and significant bottleneck in robust statistical time series methods. No other concepts or datasets met the strict threshold for standalone vault inclusion.

### Approved Concepts
- Fractional Lower-Order Covariance (FLOC): Addresses the limitations of standard autocovariance in cyclostationary analysis when dealing with heavy-tailed, infinite-variance data.

### Approved Open Questions
- Asymptotic Distribution of FLOC-based Measures: Analytical asymptotic results would eliminate the reliance on computationally expensive simulation-based methods for setting significance thresholds and confidence intervals, providing more robust theoretical guarantees for the proposed tests and order identification procedures.

## Links

- [Abstract](https://arxiv.org/abs/2604.13689)
- [PDF](https://arxiv.org/pdf/2604.13689)

