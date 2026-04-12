---
# CSL-compatible fields
title: "Zero-shot Multivariate Time Series Forecasting Using Tabular Prior Fitted Networks"
author:
  - literal: "Mayuka Jayawardhana"
  - literal: "Nihal Sharma"
  - literal: "Kazem Meidani"
  - literal: "Bayan Bruss"
  - literal: "Tom Goldstein"
  - literal: "Doron Bergman"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08400"

# Custom fields
paper_id: "2604.08400"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "tabular-prior-fitted-networks-for-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-12T05:02:41Z"
created_at: "2026-04-12T05:02:41Z"
---

# Zero-shot Multivariate Time Series Forecasting Using Tabular Prior Fitted Networks

**Authors**: Mayuka Jayawardhana, Nihal Sharma, Kazem Meidani, Bayan Bruss, Tom Goldstein, Doron Bergman
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08400](https://arxiv.org/abs/2604.08400)

## Summary

This paper addresses the limitations of applying tabular foundation models to multivariate time series, which often default to independent univariate modeling. The authors propose a framework that recasts multivariate time series forecasting as a series of scalar regression problems, allowing tabular foundation models to solve them in a zero-shot manner. By utilizing the TabPFN-TS backbone, the approach effectively accounts for inter-channel interactions while leveraging the predictive power of tabular foundation models. Experimental results demonstrate that this method achieves state-of-the-art performance compared to existing tabular forecasting approaches.

## Key Contributions

- Introduces a framework that recasts multivariate time series forecasting as a series of scalar regression problems.
- Enables zero-shot multivariate forecasting using tabular foundation models like TabPFN while capturing inter-channel interactions.
- Demonstrates competitive performance against state-of-the-art tabular methods on multivariate time series forecasting benchmarks.

## Open Questions & Future Work

- [[ci-vs-cd-forecasting-superiority]]

## Key Concepts

- [[tabular-prior-fitted-networks-for-forecasting]]: A zero-shot forecasting framework that transforms multivariate time series into a sequence of scalar regression problems solvable by tabular foundation models.

## Archivist Review

Approved the core conceptual framework for bridging tabular foundation models and multivariate time series, as well as a fundamental open question regarding the trade-offs of channel-independent versus channel-dependent forecasting strategies. Rejected the probabilistic calibration question as it is currently too generic and overlaps with existing broader concerns about uncertainty quantification in time series.

### Approved Concepts
- Tabular-Prior-Fitted Networks for Forecasting: Proposes a novel bridge between tabular foundation models and multivariate forecasting by recasting the time series problem into scalar regression tasks.

### Approved Open Questions
- CI vs CD Forecasting Superiority: This is a fundamental methodological trade-off in multivariate time series forecasting that directly impacts model selection and performance optimization across diverse domains.

## Links

- [Abstract](https://arxiv.org/abs/2604.08400)
- [PDF](https://arxiv.org/pdf/2604.08400)

