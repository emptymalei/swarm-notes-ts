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
  - "time-series-forecasting"
  - "non-stationary"
  - "attention-mechanism"
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-stationary-nonstationary-attention-asna"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:24:23Z"
created_at: "2026-05-17T05:24:23Z"
---

# SeesawNet: Towards Non-stationary Time Series Forecasting with Balanced Modeling of Common and Specific Dependencies

**Authors**: Hao Li, Lu Zhang, Liu Chong, Yankai Chen, Pengyang Wang, Yingjie Zhou
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14551](https://arxiv.org/abs/2605.14551)

## Summary

SeesawNet is a unified architecture designed to mitigate the over-smoothing effects of instance normalization in non-stationary time series forecasting. It introduces the Adaptive Stationary-Nonstationary Attention (ASNA) module, which dynamically captures and fuses common dependencies from normalized data and instance-specific dependencies from raw sequences. By alternating between dedicated temporal and channel modeling, the model effectively balances heterogeneous dependencies to outperform current state-of-the-art forecasting methods.

## Key Contributions

- SeesawNet addresses the over-smoothing limitation of Instance Normalization by dynamically balancing common and instance-specific dependencies.
- The proposed ASNA module adaptively fuses features derived from normalized and raw sequences to handle instance-level non-stationarity.
- The architecture alternates between temporal and channel relationship modeling to capture cross-variable and long-range dependencies effectively.

## Open Questions & Future Work

- [[impact-of-non-stationary-patterns-on-dependency-balance]]

## Key Concepts

- [[adaptive-stationary-nonstationary-attention-asna]]: An attention mechanism that adaptively fuses common dependencies from normalized data and specific dependencies from raw data based on instance non-stationarity.

## Archivist Review

I approved the ASNA mechanism because it addresses a fundamental trade-off in non-stationary time series forecasting—the over-smoothing of instance-specific features by instance normalization—in a way that is highly modular and reusable. The open question was approved for its focus on the interaction between different types of non-stationarity and model adaptivity, which is a major research gap in the field. No other candidates were found to meet the high bar for permanent vault storage.

### Approved Concepts
- Adaptive Stationary-Nonstationary Attention (ASNA): ASNA is the central mechanism for balancing common and instance-specific dependencies in non-stationary forecasting.

### Approved Open Questions
- Non-stationary patterns and dependency balance: This is critical for developing more robust and interpretable time series forecasting models that can adaptively handle different types of distribution shifts encountered in real-world applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.14551)
- [PDF](https://arxiv.org/pdf/2605.14551)

