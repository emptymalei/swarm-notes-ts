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
processed_at: "2026-04-18T04:54:03Z"
created_at: "2026-04-18T04:54:03Z"
---

# An End-to-end Building Load Forecasting Framework with Patch-based Information Fusion Network and Error-weighted Adaptive Loss

**Authors**: Hang Fan, Ying Lu, Weican Liu, Dunnan Liu, Xiaotao Chen, Shengwei Mei
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13714](https://arxiv.org/abs/2604.13714)

## Summary

This paper introduces an end-to-end building load forecasting framework that addresses high temporal volatility through a two-stage approach. The framework features an anomaly-corrected preprocessing module and the Patch-based Information Fusion Network (PIF-Net), which uses gated temporal patch integration to capture local and global dependencies. To enhance robustness under extreme conditions, the authors implement an Error-weighted Adaptive Loss (EWAL) function that dynamically reweights penalties based on the real-time prediction error distribution.

## Key Contributions

- Introduces the Patch-based Information Fusion Network (PIF-Net), which utilizes patching and a gating mechanism to improve temporal feature extraction for building load forecasting.
- Proposes an Error-weighted Adaptive Loss (EWAL) function that improves model robustness during extreme load volatility by dynamically adjusting penalties based on error distribution.
- Develops a two-stage preprocessing pipeline incorporating LOF for anomaly detection and SVM-SHAP for feature selection to reduce data redundancy and improve signal quality.

## Open Questions & Future Work

- [[probabilistic-load-forecasting-uncertainty]]
- [[multimodal-data-integration-load-forecasting]]

## Key Concepts

- [[patch-based-information-fusion-network]]: A time-series forecasting architecture that segments inputs into patches and dynamically fuses them using a gating mechanism.
- [[error-weighted-adaptive-loss]]: A loss function that dynamically adjusts penalty weights based on prediction error distributions to improve robustness under extreme conditions.

## Archivist Review

I have approved the proposed concepts and open questions as they represent reusable methodology in the domain of volatile time-series forecasting. The PIF-Net and EWAL concepts provide modular, generalizable techniques, and the open questions correctly highlight significant, non-boilerplate research challenges in load forecasting. I rejected no candidates, as all provided candidates met the archival threshold.

### Approved Concepts
- Patch-based Information Fusion Network: The core architectural contribution of the paper, utilizing patch-based processing and a gating mechanism for temporal feature integration.
- Error-weighted Adaptive Loss: A novel loss function designed to handle high volatility and extreme values in building load forecasting.

### Approved Open Questions
- Probabilistic Building Load Forecasting: Probabilistic forecasting is critical for risk-aware decision-making in demand response markets and grid management, moving beyond point-estimation to provide confidence intervals.
- Integrating Heterogeneous Building Data: Accounting for the underlying drivers of building energy usage improves model explainability and performance, especially in environments with high occupancy-driven volatility.

## Links

- [Abstract](https://arxiv.org/abs/2604.13714)
- [PDF](https://arxiv.org/pdf/2604.13714)

