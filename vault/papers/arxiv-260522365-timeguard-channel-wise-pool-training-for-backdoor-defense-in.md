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
  []
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
processed_at: "2026-05-22T05:29:09Z"
created_at: "2026-05-22T05:29:09Z"
---

# TimeGuard: Channel-wise Pool Training for Backdoor Defense in Time Series Forecasting

**Authors**: Quang Duc Nguyen, Siyuan Liang, Yiming Li, Fushuo Huo, Dacheng Tao
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22365](https://arxiv.org/abs/2605.22365)

## Summary

TimeGuard is a novel training-time defense mechanism designed to mitigate backdoor attacks in time series forecasting, which are typically exacerbated by data entanglement and task-formulation shifts. The method employs a channel-wise pool training paradigm to alleviate channel-level signal dilution and integrates distance-regularized loss selection to prevent training-loss degeneration. Extensive benchmarking demonstrates superior robustness against backdoor attacks compared to existing defenses, significantly improving poisoned-data performance without compromising clean-data accuracy.

## Key Contributions

- Conducted a systematic evaluation of thirteen backdoor defenses in time series forecasting, identifying signal dilution and loss degeneration as key failure modes.
- Proposed TimeGuard, a training-time defense that utilizes channel-wise pool training and distance-regularized loss selection.
- Achieved a 1.96x improvement in poisoned MAE over current baselines while maintaining clean forecasting performance within 5%.

## Key Concepts

- [[channel-wise-pool-training]]: A training paradigm that isolates backdoor effects by partitioning time series into channel-specific pools.
- [[distance-regularized-loss-selection]]: A technique that uses distance-based metrics to dynamically filter and select reliable training samples, preventing loss landscape degradation.

## Archivist Review

The paper introduces a structured training-time defense mechanism for time series models. I have approved the two primary mechanisms as they provide reusable strategies for mitigating signal dilution and training loss degradation in adversarial contexts. Other candidates were rejected as they were either task-specific evaluations or lacked the potential for wider applicability.

### Approved Concepts
- Channel-wise Pool Training: It is the central mechanism introduced to address signal dilution in time series backdoor defense.
- Distance-regularized Loss Selection: Addresses the training-loss degeneration bottleneck caused by task-formulation shifts in time series.

### Rejected Candidates
- [concept] TSF backdoor defense evaluation (`time-series-backdoor-defense-evaluation`) - low_impact: This refers to an empirical benchmarking task rather than a reusable mechanistic concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.22365)
- [PDF](https://arxiv.org/pdf/2605.22365)

