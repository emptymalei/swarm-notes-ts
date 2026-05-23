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
processed_at: "2026-05-23T05:21:34Z"
created_at: "2026-05-23T05:21:34Z"
---

# TimeGuard: Channel-wise Pool Training for Backdoor Defense in Time Series Forecasting

**Authors**: Quang Duc Nguyen, Siyuan Liang, Yiming Li, Fushuo Huo, Dacheng Tao
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22365](https://arxiv.org/abs/2605.22365)

## Summary

TimeGuard is a training-time defense mechanism designed to protect time series forecasting models from backdoor attacks. By addressing the challenges of channel-level signal dilution and training-loss degeneration, the method employs channel-wise pool training and distance-regularized loss selection to reliably distinguish between clean and poisoned data. Extensive empirical validation shows that TimeGuard significantly enhances model robustness against various backdoor threats without compromising performance on clean data.

## Key Contributions

- Systematically analyzes failure modes of thirteen existing backdoor defenses in time series forecasting, identifying data entanglement and task-formulation shift as primary limitations.
- Introduces TimeGuard, a novel training-time defense that utilizes channel-wise pool training and distance-regularized loss selection to improve model robustness.
- Demonstrates that TimeGuard outperforms state-of-the-art baselines, achieving a 1.96x improvement in MAE_P while maintaining clean performance within a 5% margin.

## Key Concepts

- [[channel-wise-pool-training]]: A robust training paradigm for multi-channel time series models that segregates training pools by channel to reduce the impact of entangled backdoor triggers.
- [[distance-regularized-loss-selection]]: A training strategy that dynamically updates a reliable dataset using distance-based constraints to prevent model exposure to contaminated samples.

## Archivist Review

I approved the two proposed concepts because they address fundamental stability issues (signal dilution and loss degeneration) in robust time-series forecasting. These methods represent reusable paradigms for training-time defense that are distinct from standard dataset-level filtering or input-synthesis techniques. I did not find any specific open questions or datasets worthy of individual notes based on the provided text.

### Approved Concepts
- Channel-wise Pool Training: Addresses the specific vulnerability of channel-level signal dilution in multi-channel time series forecasting under backdoor attacks.
- Distance-regularized Loss Selection: Provides a robust mechanism for maintaining a 'clean' data set during training in the presence of noise and poisoning, mitigating loss degeneration.

## Links

- [Abstract](https://arxiv.org/abs/2605.22365)
- [PDF](https://arxiv.org/pdf/2605.22365)

