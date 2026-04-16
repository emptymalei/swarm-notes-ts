---
# CSL-compatible fields
title: "An End-to-end Building Load Forecasting Framework with Patch-based Information Fusion Network and Error-weighted Adaptive Loss"
author:
  - literal: "Hang Fan"
  - literal: "Ying Lu"
  - literal: "Weican Liu"
  - literal: "Dunnan Liu"
  - literal: "Xiaotao Chen"
  - literal: "Shengwei Mei"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13714"

# Custom fields
paper_id: "2604.13714"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series-forecasting"
  - "energy-management"
  - "feature-selection"
architectures:
  []
datasets:
  []
concept_slugs:
  - "patch-based-information-fusion-network"
  - "error-weighted-adaptive-loss"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:06:18Z"
created_at: "2026-04-16T05:06:18Z"
---

# An End-to-end Building Load Forecasting Framework with Patch-based Information Fusion Network and Error-weighted Adaptive Loss

**Authors**: Hang Fan, Ying Lu, Weican Liu, Dunnan Liu, Xiaotao Chen, Shengwei Mei
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13714](https://arxiv.org/abs/2604.13714)

## Summary

This paper presents an end-to-end building load forecasting framework designed to handle the complexity and volatility of energy demand data. The framework features a two-stage preprocessing pipeline for robust anomaly detection and feature selection, followed by a Patch-based Information Fusion Network (PIF-Net) that effectively extracts temporal features using a gating mechanism. To improve resilience against extreme load conditions, the authors propose an Error-weighted Adaptive Loss (EWAL) function that adjusts penalties according to real-time error distributions. Experimental results confirm the framework's superior performance compared to traditional forecasting baselines.

## Key Contributions

- Introduces PIF-Net, a patch-based architecture that utilizes shared GRUs and a gated fusion mechanism to improve temporal dependency modeling in building load data.
- Develops Error-weighted Adaptive Loss (EWAL), which dynamically adjusts penalties based on error distribution to improve forecasting robustness under extreme load fluctuations.
- Implements a two-stage preprocessing pipeline incorporating LOF for anomaly detection and SVM-SHAP for feature selection to reduce redundancy and improve data quality.

## Open Questions & Future Work

- [[multi-source-data-integration-load-forecasting]]
- [[probabilistic-load-forecasting-uncertainty-quantification]]

## Key Concepts

- [[patch-based-information-fusion-network]]: A deep learning framework for time series forecasting that processes input data as local patches to improve feature extraction and temporal integration.
- [[error-weighted-adaptive-loss]]: A loss function for time-series forecasting that combines rational quadratic and logarithmic components to dynamically penalize errors based on their distribution.

## Archivist Review

The approved concepts represent reusable methodological contributions to time-series forecasting (patch-based gating and robust loss functions). The open questions address core structural limitations in current load forecasting, specifically the challenge of feature integration and the shift toward probabilistic modeling, both of which are standard, important research directions for this domain.

### Approved Concepts
- Patch-based Information Fusion Network (PIF-Net): PIF-Net introduces a patching mechanism for building load forecasting that leverages shared GRU blocks and dynamic weighting for temporal features.
- Error-weighted Adaptive Loss (EWAL): EWAL addresses model robustness under extreme load conditions by dynamically adjusting loss penalties.

### Approved Open Questions
- Integrating Multi-source Data for Forecasting: Expanding input features is a critical step to moving beyond simple time-series forecasting and capturing the underlying physical and social drivers of energy consumption.
- Transitioning to Probabilistic Forecasting: Quantifying uncertainty is essential for risk-aware decision-making in demand response and energy management systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.13714)
- [PDF](https://arxiv.org/pdf/2604.13714)

