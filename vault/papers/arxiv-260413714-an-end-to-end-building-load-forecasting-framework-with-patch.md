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
  []
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
processed_at: "2026-04-17T05:07:25Z"
created_at: "2026-04-17T05:07:25Z"
---

# An End-to-end Building Load Forecasting Framework with Patch-based Information Fusion Network and Error-weighted Adaptive Loss

**Authors**: Hang Fan, Ying Lu, Weican Liu, Dunnan Liu, Xiaotao Chen, Shengwei Mei
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13714](https://arxiv.org/abs/2604.13714)

## Summary

This paper introduces an end-to-end building load forecasting framework designed to handle high volatility and complex temporal dependencies. The approach features a robust preprocessing pipeline and a novel Patch-based Information Fusion Network (PIF-Net) that models temporal dynamics using gated, patch-wise GRU units. Furthermore, the framework employs an Error-weighted Adaptive Loss (EWAL) to dynamically manage penalty weights, significantly improving forecasting performance and robustness during extreme load events.

## Key Contributions

- Proposes a patch-based information fusion network (PIF-Net) that uses shared GRUs and dynamic gating to integrate multi-scale temporal dependencies for building load forecasting.
- Introduces an Error-weighted Adaptive Loss (EWAL) that dynamically adjusts penalty weights based on prediction error distributions to improve robustness under high-volatility scenarios.
- Develops a two-stage preprocessing pipeline incorporating LOF for anomaly detection and SVM-SHAP for feature selection, enhancing model interpretability and data quality.

## Open Questions & Future Work

- [[probabilistic-load-forecasting-uncertainty]]
- [[multi-source-data-integration-load-forecasting]]

## Key Concepts

- [[patch-based-information-fusion-network]]: An architecture that processes time-series input as local patches via GRUs and integrates them using a dynamic gating mechanism.
- [[error-weighted-adaptive-loss]]: A loss function that dynamically adjusts penalty weights based on real-time prediction error distributions using a combination of rational quadratic and logarithmic terms.

## Archivist Review

The paper introduces a patch-based architectural approach and a dynamic loss function, both of which represent reusable strategies in time-series forecasting. The proposed open questions address critical gaps in current load forecasting: the shift from deterministic to probabilistic models and the integration of heterogeneous, multi-source data. I have approved these as they align with the vault's standard for reusable methodologies and high-impact research questions.

### Approved Concepts
- Patch-based Information Fusion Network (PIF-Net): It is the core architectural contribution, combining local patch processing with a dynamic gating mechanism for temporal feature fusion.
- Error-weighted Adaptive Loss (EWAL): It provides a novel mechanism for improving model robustness in forecasting tasks prone to outliers or volatility.

### Approved Open Questions
- Probabilistic Building Load Forecasting: Probabilistic forecasting provides critical insights into the volatility of building loads, which is essential for effective demand response and reserve market participation.
- Multi-source Data Integration: Capturing the interplay between human activity and physical building characteristics is necessary to move beyond simple time-series extrapolation and improve prediction accuracy during non-routine operations.

## Links

- [Abstract](https://arxiv.org/abs/2604.13714)
- [PDF](https://arxiv.org/pdf/2604.13714)

