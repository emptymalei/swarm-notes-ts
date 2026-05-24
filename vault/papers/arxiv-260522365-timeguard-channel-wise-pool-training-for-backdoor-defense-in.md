---
# CSL-compatible fields
title: "TimeGuard: Channel-wise Pool Training for Backdoor Defense in Time Series Forecasting"
author:
  - literal: "Quang Duc Nguyen"
  - literal: "Siyuan Liang"
  - literal: "Yiming Li"
  - literal: "Fushuo Huo"
  - literal: "Dacheng Tao"
issued:
  date-parts:
    - [2026, 5, 21]
url: "https://arxiv.org/abs/2605.22365"

# Custom fields
paper_id: "2605.22365"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "time-series"
  - "forecasting"
  - "robustness"
  - "adversarial-machine-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "channel-wise-pool-training"
  - "distance-regularized-loss-selection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-24T05:26:38Z"
created_at: "2026-05-24T05:26:38Z"
---

# TimeGuard: Channel-wise Pool Training for Backdoor Defense in Time Series Forecasting

**Authors**: Quang Duc Nguyen, Siyuan Liang, Yiming Li, Fushuo Huo, Dacheng Tao
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22365](https://arxiv.org/abs/2605.22365)

## Summary

This paper addresses the susceptibility of Time Series Forecasting (TSF) models to backdoor attacks, which has been largely overlooked due to unique challenges like data entanglement and task-formulation shifts. The authors analyze thirteen existing defenses and find that signal dilution and training-loss degeneration are critical failure modes in TSF contexts. To overcome these, they propose TimeGuard, a defense that utilizes channel-wise pool training and distance-regularized loss selection to robustly distinguish and exclude malicious triggers during the training process. Empirical results show significant improvements in backdoor robustness across diverse architectures without compromising prediction accuracy on clean data.

## Key Contributions

- Identifies that data entanglement in TSF causes channel-level signal dilution, rendering traditional sample-filtering and trigger-synthesis defenses ineffective.
- Demonstrates that task-formulation shift in TSF leads to training-loss degeneration, making it difficult to distinguish between poisoned and clean samples.
- Introduces TimeGuard, a backdoor defense that improves MAE_P by 1.96x over leading baselines while maintaining clean performance within a 5% margin.

## Key Concepts

- [[channel-wise-pool-training]]: A defensive training paradigm that isolates channels to prevent signal dilution and isolate triggers in time series forecasting models.
- [[distance-regularized-loss-selection]]: A training mechanism that uses distance constraints to identify and include reliable (unpoisoned) windows in a training pool.

## Archivist Review

The paper provides a formal analysis of failure modes in time series backdoor defense (signal dilution and loss degeneration) and proposes two coherent mechanisms to address them. These concepts, channel-wise pool training and distance-regularized loss selection, are sufficiently novel and reusable for robust time series learning. No datasets or open questions were qualified for standalone vault entry.

### Approved Concepts
- Channel-wise Pool Training: This is the core paradigm proposed to address channel-level signal dilution in time series backdoor defense.
- Distance-regularized loss selection: This technique directly addresses the training-loss degeneration issue identified by the authors.

## Links

- [Abstract](https://arxiv.org/abs/2605.22365)
- [PDF](https://arxiv.org/pdf/2605.22365)

