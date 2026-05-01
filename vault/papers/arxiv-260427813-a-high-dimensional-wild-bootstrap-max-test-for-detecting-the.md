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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "block-bootstrap-max-test"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:22:52Z"
created_at: "2026-05-01T05:22:52Z"
---

# A High Dimensional Wild Bootstrap Max-Test for Detecting the Presence of Significant Predictors

**Authors**: Jonathan B. Hill
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27813](https://arxiv.org/abs/2604.27813)

## Summary

This paper introduces a block bootstrap max-test for detecting significant predictors in high-dimensional regression scenarios where the number of covariates grows exponentially relative to the sample size. The method specifically addresses the challenges of weakly dependent and heterogeneous, potentially non-stationary time series data. By leveraging a max-statistic over computed parameters, the framework avoids complex covariance matrix estimation and ad-hoc corrections like Bonferroni. The resulting non-standard limit distribution is effectively approximated via a multiplier block bootstrap, ensuring reliable performance even with weak or sparse signals.

## Key Contributions

- Introduces a block bootstrap max-test for identifying significant predictors in high-dimensional settings where p >> n, supporting exponential growth of covariates relative to sample size.
- Eliminates the requirement for explicit covariance matrix estimation or post-estimation Bonferroni corrections by utilizing a max-statistic approach under physical dependence conditions.
- Demonstrates robust size control and performance against weak signals through theoretical analysis and empirical validation on VIX volatility index data.

## Open Questions & Future Work

- [[endogenous-predictor-selection-weak-dependence]]

## Key Concepts

- [[block-bootstrap-max-test]]: A statistical test for high-dimensional predictor significance that uses a multiplier block bootstrap to handle non-standard limit distributions of max-statistics.

## Archivist Review

The paper provides a rigorous statistical framework for high-dimensional inference in time series. The block bootstrap max-test is approved as a reusable method for high-dimensional predictor detection. The open question regarding endogenous predictor selection is approved as it addresses a fundamental, unresolved theoretical bottleneck in high-dimensional time-series inference. VIX is rejected as a dataset because it is a broad economic indicator, not a specialized machine learning benchmark.

### Approved Concepts
- Block bootstrap max-test: It provides a method to detect significant predictors in high-dimensional, non-stationary time series without needing covariance matrix estimation or Bonferroni corrections.

### Approved Open Questions
- Optimal predictor index selection: Adaptive post-model-selection inference is a central challenge in high-dimensional statistics, and extending existing methods to handle temporal or cross-sectional dependence is crucial for their application in fields like macroeconomics and finance.

### Rejected Candidates
- [dataset] VIX volatility index (`vix-volatility-index`) - low_impact: This is a general economic indicator rather than a specific research dataset for benchmarking models.

## Links

- [Abstract](https://arxiv.org/abs/2604.27813)
- [PDF](https://arxiv.org/pdf/2604.27813)

