---
# CSL-compatible fields
title: "SeesawNet: Towards Non-stationary Time Series Forecasting with Balanced Modeling of Common and Specific Dependencies"
author:
  - literal: "Hao Li"
  - literal: "Lu Zhang"
  - literal: "Liu Chong"
  - literal: "Yankai Chen"
  - literal: "Pengyang Wang"
  - literal: "Yingjie Zhou"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14551"

# Custom fields
paper_id: "2605.14551"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "non-stationary"
  - "multivariate-time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-stationary-nonstationary-attention-asna"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:12:41Z"
created_at: "2026-05-16T05:12:41Z"
---

# SeesawNet: Towards Non-stationary Time Series Forecasting with Balanced Modeling of Common and Specific Dependencies

**Authors**: Hao Li, Lu Zhang, Liu Chong, Yankai Chen, Pengyang Wang, Yingjie Zhou
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14551](https://arxiv.org/abs/2605.14551)

## Summary

SeesawNet addresses the limitations of instance normalization in time series forecasting, which often obscures instance-specific structural information. The framework utilizes a novel Adaptive Stationary-Nonstationary Attention (ASNA) mechanism to dynamically fuse common patterns derived from normalized sequences with instance-specific dependencies from raw data. By alternating between dedicated temporal and channel modeling, SeesawNet effectively captures complex non-stationary dynamics and cross-variable dependencies.

## Key Contributions

- Proposes SeesawNet, a unified architecture for non-stationary multivariate time series forecasting that dynamically balances common and instance-specific dependencies.
- Introduces Adaptive Stationary-Nonstationary Attention (ASNA) to compute and fuse dependencies from both normalized and raw sequences based on instance non-stationarity.
- Achieves consistent state-of-the-art performance across multiple real-world time series forecasting benchmarks by alternating temporal and channel relationship modeling.

## Open Questions & Future Work

- [[non-stationary-dependency-modeling-balance]]

## Key Concepts

- [[adaptive-stationary-nonstationary-attention-asna]]: An attention mechanism that adaptively balances common and instance-specific dependencies by processing both normalized and raw sequences based on instance-level non-stationarity.

## Archivist Review

I approved the ASNA mechanism as a novel approach to the tension between global normalization and local instance-specific structure in non-stationary forecasting, which is a reusable architectural idea. I approved the open question on non-stationary dependency balance as a fundamental research challenge for the community that moves beyond standard performance benchmarking. No datasets were approved as they were described only as aggregate real-world benchmarks.

### Approved Concepts
- Adaptive Stationary-Nonstationary Attention (ASNA): It is the central technical innovation proposed to solve the tension between modeling common patterns and instance-specific dependencies in non-stationary time series.

### Approved Open Questions
- Non-stationary dependency modeling balance: Understanding the sensitivity of adaptive models to varying non-stationary regimes is critical for designing more robust forecasting architectures that can dynamically adjust to diverse temporal behaviors without relying on heuristic-driven design choices.

## Links

- [Abstract](https://arxiv.org/abs/2605.14551)
- [PDF](https://arxiv.org/pdf/2605.14551)

