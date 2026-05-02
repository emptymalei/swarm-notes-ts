---
# CSL-compatible fields
title: "A High Dimensional Wild Bootstrap Max-Test for Detecting the Presence of Significant Predictors"
author:
  - literal: "Jonathan B. Hill"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27813"

# Custom fields
paper_id: "2604.27813"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "statistical-inference"
  - "high-dimensional-data"
architectures:
  []
datasets:
  []
concept_slugs:
  - "high-dimensional-wild-bootstrap-max-test"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:08:05Z"
created_at: "2026-05-02T05:08:05Z"
---

# A High Dimensional Wild Bootstrap Max-Test for Detecting the Presence of Significant Predictors

**Authors**: Jonathan B. Hill
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27813](https://arxiv.org/abs/2604.27813)

## Summary

This paper introduces a high-dimensional block bootstrap max-test designed to detect significant predictors when the number of covariates p grows exponentially relative to sample size n. By utilizing a max-statistic approach, the method effectively accounts for weakly dependent and non-stationary time series data without requiring complex covariance matrix estimation or manual Bonferroni adjustments. The validity of the test is established under mild conditions on memory decay and moment growth, with performance validated through numerical experiments and an empirical analysis of the VIX volatility index.

## Key Contributions

- Proposes a block bootstrap max-test for significance detection in settings where p >> n with exponentially growing covariate counts.
- Demonstrates that the approach handles weakly dependent and non-stationary data by leveraging physical dependence measures.
- Eliminates the requirement for explicit covariance matrix estimation and post-estimation Bonferroni corrections in correlation screening.

## Open Questions & Future Work

- [[post-model-selection-weak-dependence]]

## Key Concepts

- [[high-dimensional-wild-bootstrap-max-test]]: A block bootstrap-based max-test for identifying significant predictors in high-dimensional settings (p >> n) with non-stationary, weakly dependent data.

## Archivist Review

The paper presents a significant contribution to high-dimensional time series inference. I approved the max-test concept as it represents a robust statistical methodology that addresses the high-dimensional setting without standard, computationally expensive requirements like covariance matrix inversion or Bonferroni corrections. The open question is approved because it articulates a clear limitation in existing post-model selection inference frameworks specifically for dependent data.

### Approved Concepts
- High-dimensional Wild Bootstrap Max-Test: Provides a method for high-dimensional significance testing in the presence of weakly dependent and heterogeneous data, avoiding the need for covariance matrix estimation or Bonferroni corrections.

### Approved Open Questions
- Post-model-selection under dependence: Developing post-model-selection inference that is valid for dependent time-series data is critical for accurate applications in fields like macroeconomics and finance, where traditional i.i.d. assumptions often do not hold.

## Links

- [Abstract](https://arxiv.org/abs/2604.27813)
- [PDF](https://arxiv.org/pdf/2604.27813)

