---
# CSL-compatible fields
title: "Auto-Configured Networks for Multi-Scale Multi-Output Time-Series Forecasting"
author:
  - literal: "Yumeng Zha"
  - literal: "Shengxiang Yang"
  - literal: "Xianpeng Wang"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07610"

# Custom fields
paper_id: "2604.07610"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series"
  - "multi-objective-optimization"
  - "neural-architecture-search"
architectures:
  []
datasets:
  []
concept_slugs:
  - "ms-bcnn"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:29:21Z"
created_at: "2026-04-10T15:29:21Z"
---

# Auto-Configured Networks for Multi-Scale Multi-Output Time-Series Forecasting

**Authors**: Yumeng Zha, Shengxiang Yang, Xianpeng Wang
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07610](https://arxiv.org/abs/2604.07610)

## Summary

This paper presents an auto-configuration framework for time-series forecasting that systematically co-optimizes preprocessing, architecture, and hyperparameters to produce a Pareto set of models balancing error and complexity. The approach centers on a Multi-Scale Bi-Branch Convolutional Neural Network (MS-BCNN) designed for multi-output regression and a Player-based Hybrid Multi-Objective Evolutionary Algorithm (PHMOEA) for efficient search. By operating within a hierarchical-conditional mixed configuration space, the framework allows for flexible model selection suitable for budget-constrained industrial deployments. Experimental results on synthetic and real-world sintering data demonstrate the framework's effectiveness against competitive baselines.

## Key Contributions

- Introduces an auto-configuration framework that generates a Pareto frontier of forecasting models, balancing prediction error against model complexity.
- Develops the Multi-Scale Bi-Branch Convolutional Neural Network (MS-BCNN) to capture local fluctuations and long-term trends for multi-output regression.
- Implements a hierarchical-conditional mixed configuration space optimized by a Player-based Hybrid Multi-Objective Evolutionary Algorithm (PHMOEA) to enable efficient deployment-ready model selection.

## Open Questions & Future Work

- [[nonstationary-industrial-forecasting-adaptation]]

## Key Concepts

- [[ms-bcnn]]: A CNN architecture with short- and long-kernel branches designed for extracting distinct local and long-term temporal dependencies in multi-output forecasting.

## Archivist Review

I approved the MS-BCNN as a modular architectural concept for multiscale forecasting and a targeted open question regarding the integration of static Pareto-optimal model selection with dynamic, drift-aware adaptation. Other candidates were rejected as implementation-specific details or routine optimization wrappers that lack sufficient reusability in the forecasting domain.

### Approved Concepts
- Multi-Scale Bi-Branch Convolutional Neural Network (MS-BCNN): The MS-BCNN provides a modular architectural inductive bias for capturing multiscale temporal features in multi-output forecasting scenarios.

### Approved Open Questions
- Dynamic non-stationary forecasting adaptation: Bridging the gap between static model selection (Pareto frontiers) and continuous adaptation is essential for long-term industrial ML viability.

### Rejected Candidates
- [concept] Player-based Hybrid Multi-Objective Evolutionary Algorithm (`phmoea`) - not_reusable: This is an evolutionary optimization routine rather than a reusable time-series forecasting mechanism.
- [concept] Hierarchical-conditional mixed configuration space (`hierarchical-conditional-mixed-configuration-space`) - subcomponent_of_broader_mechanism: This is a specific formulation of the search space for the optimization algorithm rather than a core forecasting paradigm.

## Links

- [Abstract](https://arxiv.org/abs/2604.07610)
- [PDF](https://arxiv.org/pdf/2604.07610)

