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
  - "forecasting"
  - "time-series"
  - "ensemble-learning"
  - "load-forecasting"
  - "non-stationary-time-series"
architectures:
  []
datasets:
  - "mit-supercloud-dataset"
concept_slugs:
  - "regime-adaptive-weighted-ensemble-learning"
dataset_slugs:
  - "mit-supercloud-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:23:56Z"
created_at: "2026-05-01T05:23:56Z"
---

# Regime-Adaptive Weighted Ensemble Learning for Computing-Driven Dynamic Load Forecasting in AI Data Centers

**Authors**: Ziying Wang, Ying Zhang, Lei Wang, Yuzhang Lin
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27207](https://arxiv.org/abs/2604.27207)

## Summary

This paper introduces a regime-adaptive ensemble learning framework designed to address the non-stationary, bursty nature of power demand in AI data centers. The method utilizes a weight-learned neural network to dynamically calibrate contributions from different submodels, supported by a novel feature engineering strategy for streaming data. Evaluation on the MIT Supercloud dataset demonstrates superior accuracy, with the proposed approach achieving sub-1% minute-class forecasting error, facilitating better grid-interactive load management.

## Key Contributions

- Proposes a regime-adaptive ensemble learning forecasting framework that optimizes submodel contributions for non-stationary computing-driven workloads.
- Introduces a feature engineering strategy that enables incremental learning from streaming, bursty AI data center power demand data.
- Achieves minute-class forecasting errors below 1% on the MIT Supercloud dataset, outperforming baseline model combinations for data center load prediction.

## Open Questions & Future Work

- [[generalizability-of-ensemble-model-pairs]]

## Key Concepts

- [[regime-adaptive-weighted-ensemble-learning]]: An ensemble learning forecasting method that dynamically optimizes weights between submodels based on detected operating regimes.

## Archivist Review

The approved concept captures a reusable framework for dynamic regime-based ensemble weight calibration, which is highly relevant for non-stationary load forecasting. The dataset and open question were approved for their focus on specific benchmarking bottlenecks in the emerging field of computing-driven grid load management. Other candidates were rejected as implementation-level details.

### Approved Concepts
- Regime-Adaptive Weighted Ensemble Learning: Provides a mechanism for dynamic recalibration of model contributions in highly non-stationary environments, specifically addressing the volatility of computing-driven loads.

### Approved Open Questions
- Generalizability of ensemble model-pairs: Understanding the robustness of ensemble structures beyond individual case studies is essential for reliable deployment in grid-interactive applications.

### Rejected Candidates
- [concept] Incremental Feature Engineering Strategy (`incremental-learning-feature-engineering`) - subcomponent_of_broader_mechanism: This is an implementation-specific technique for streaming data rather than a foundational forecasting concept.

## Datasets

- [[mit-supercloud-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27207)
- [PDF](https://arxiv.org/pdf/2604.27207)

