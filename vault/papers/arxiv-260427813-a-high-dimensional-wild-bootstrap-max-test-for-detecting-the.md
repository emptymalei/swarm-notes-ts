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
  - "time-series"
  - "statistics"
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
processed_at: "2026-05-03T05:14:51Z"
created_at: "2026-05-03T05:14:51Z"
---

# A High Dimensional Wild Bootstrap Max-Test for Detecting the Presence of Significant Predictors

**Authors**: Jonathan B. Hill
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27813](https://arxiv.org/abs/2604.27813)

## Summary

This paper introduces a high-dimensional wild block bootstrap max-test for identifying significant predictors in time series where the number of covariates grows exponentially with the sample size ($p \gg n$). By utilizing a max-statistic over computed parameters, the method bypasses the need for explicit covariance matrix estimation and adaptive re-sampling techniques. This approach simplifies inference by avoiding non-uniform asymptotics and the necessity for post-estimation Bonferroni corrections, while remaining robust to weak or sparse signals in non-stationary data.

## Key Contributions

- Proposes a block bootstrap max-test for detecting significant predictors in $p \gg n$ time series environments.
- Demonstrates consistent performance under non-stationary and heterogeneous data conditions without requiring covariance matrix estimation.
- Evaluates the test's efficacy on VIX volatility index data and shows robustness against weak or sparse signals compared to standard methods.

## Open Questions & Future Work

- [[adaptive-post-selection-inference-weak-dependence]]

## Key Concepts

- [[high-dimensional-wild-bootstrap-max-test]]: A statistical test for high-dimensional correlation screening that avoids covariance estimation and Bonferroni corrections by using a wild block bootstrap.

## Archivist Review

I approved the high-dimensional wild bootstrap max-test concept as it presents a novel statistical framework for correlation screening in p >> n time series that avoids common issues like Bonferroni corrections. I also approved the open question regarding adaptive post-model-selection inference as it addresses a fundamental methodological challenge in statistics that remains unresolved for weakly dependent time series data.

### Approved Concepts
- High-dimensional wild bootstrap max-test: It provides a framework for correlation screening in p >> n settings for time series without requiring covariance matrix estimation or Bonferroni corrections.

### Approved Open Questions
- Adaptive post-model-selection inference: Adaptive post-model-selection inference is a central problem in statistics, as practitioners frequently require both detection of significant predictors and valid post-selection inference, which currently remains computationally and theoretically complex for dependent, high-dimensional data.

## Links

- [Abstract](https://arxiv.org/abs/2604.27813)
- [PDF](https://arxiv.org/pdf/2604.27813)

