---
# CSL-compatible fields
title: "Regime-Adaptive Weighted Ensemble Learning for Computing-Driven Dynamic Load Forecasting in AI Data Centers"
author:
  - literal: "Ziying Wang"
  - literal: "Ying Zhang"
  - literal: "Lei Wang"
  - literal: "Yuzhang Lin"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.27207"

# Custom fields
paper_id: "2604.27207"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "ensemble-learning"
  - "energy-informatics"
architectures:
  []
datasets:
  - "mit-supercloud-dataset"
concept_slugs:
  - "regime-adaptive-weighted-ensemble-learning"
dataset_slugs:
  - "mit-supercloud-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:08:58Z"
created_at: "2026-05-02T05:08:58Z"
---

# Regime-Adaptive Weighted Ensemble Learning for Computing-Driven Dynamic Load Forecasting in AI Data Centers

**Authors**: Ziying Wang, Ying Zhang, Lei Wang, Yuzhang Lin
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27207](https://arxiv.org/abs/2604.27207)

## Summary

This paper addresses the challenge of non-stationary, computing-driven load forecasting in AI data centers by proposing a regime-adaptive weighted ensemble learning framework. The approach leverages a weight-learned neural network to dynamically balance the contributions of multiple ML submodels, paired with an incremental feature engineering strategy to handle bursty, heterogeneous job dynamics. Evaluations on the MIT Supercloud dataset demonstrate superior accuracy and adaptability compared to existing models, achieving minute-class forecasting errors below 1%.

## Key Contributions

- Introduces a regime-adaptive ensemble learning algorithm that dynamically optimizes submodel contributions for computing-driven data center workloads.
- Develops a feature engineering strategy that enables incremental learning from non-stationary, bursty data streams.
- Achieves sub-1% minute-class load forecasting error on the MIT Supercloud dataset, outperforming baseline combinations for grid-interactive coordination.

## Open Questions & Future Work

- [[regime-adaptive-ensemble-forecasting-without-labeling]]

## Key Concepts

- [[regime-adaptive-weighted-ensemble-learning]]: An ensemble learning framework that uses a weight-learned neural network to dynamically calibrate submodel contributions across varying computing load regimes.

## Archivist Review

I have approved the core regime-adaptive ensemble concept and the critical open question regarding label-free regime adaptation. The MIT Supercloud dataset is approved as a key empirical benchmark used in the paper. Other candidates were not proposed, and I have maintained high selectivity by ensuring only the central mechanism and its most significant research challenge were included.

### Approved Concepts
- Regime-Adaptive Weighted Ensemble Learning: The method explicitly targets non-stationary, bursty computing workloads through dynamic weight optimization, which is central to the paper's contribution in AI data center load forecasting.

### Approved Open Questions
- Regime-Adaptive Forecasting Without Labeling: Robust load forecasting is critical for maintaining power grid stability; as AI data center loads become more volatile, the ability to adapt to unseen or rapidly shifting regimes is essential for effective demand response and grid-interactive coordination.

## Datasets

- [[mit-supercloud-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27207)
- [PDF](https://arxiv.org/pdf/2604.27207)

