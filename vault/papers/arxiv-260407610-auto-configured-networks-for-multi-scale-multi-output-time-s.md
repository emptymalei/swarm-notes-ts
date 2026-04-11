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
  - "automl"
  - "multi-objective-optimization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "ms-bcnn"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:46:14Z"
created_at: "2026-04-11T04:46:14Z"
---

# Auto-Configured Networks for Multi-Scale Multi-Output Time-Series Forecasting

**Authors**: Yumeng Zha, Shengxiang Yang, Xianpeng Wang
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07610](https://arxiv.org/abs/2604.07610)

## Summary

This paper addresses the challenge of designing time-series forecasting models that must balance prediction accuracy with computational complexity under constrained deployment settings. The authors introduce an auto-configuration framework that leverages the Multi-Scale Bi-Branch Convolutional Neural Network (MS-BCNN) and the Player-based Hybrid Multi-Objective Evolutionary Algorithm (PHMOEA). By unifying alignment, architecture, and hyperparameter search, the framework successfully identifies a Pareto-optimal set of models. Experimental results on synthetic benchmarks and a real-world sintering dataset confirm the superiority of this approach over existing static configuration methods.

## Key Contributions

- Introduces an auto-configuration framework that yields a Pareto-optimal set of models balancing prediction error and complexity.
- Proposes MS-BCNN, a multi-scale convolutional architecture that decouples short-term fluctuation and long-term trend modeling.
- Demonstrates that PHMOEA effectively searches a hierarchical configuration space, outperforming baselines under fixed computational budgets on synthetic and industrial sintering datasets.

## Open Questions & Future Work

- [[dynamic-learning-for-industrial-drift]]

## Key Concepts

- [[ms-bcnn]]: A neural network architecture featuring short- and long-kernel branches to simultaneously capture local fluctuations and long-term trends in multi-output time series.

## Archivist Review

I have approved the MS-BCNN concept for its reusable approach to multi-scale temporal modeling and the open question on dynamic drift learning because it addresses a critical, unresolved reliability bottleneck in industrial forecasting. I rejected the PHMOEA concept as it represents a generic hyperparameter optimization technique rather than a foundational concept specific to time-series forecasting advancement.

### Approved Concepts
- Multi-Scale Bi-Branch Convolutional Neural Network (MS-BCNN): The dual-branch architecture explicitly decouples local and global temporal dependencies, which is a recurring requirement in industrial time-series forecasting.

### Approved Open Questions
- Dynamic learning for drift: Mitigating performance degradation due to nonstationarity is a fundamental bottleneck for the reliability and long-term scalability of industrial machine learning deployments.

### Rejected Candidates
- [concept] Player-based Hybrid Multi-Objective Evolutionary Algorithm (PHMOEA) (`phmoea`) - generic: Evolutionary algorithms for hyperparameter optimization are generic in AutoML; this specific variant is an implementation detail rather than a broadly reusable concept for time-series architecture.

## Links

- [Abstract](https://arxiv.org/abs/2604.07610)
- [PDF](https://arxiv.org/pdf/2604.07610)

