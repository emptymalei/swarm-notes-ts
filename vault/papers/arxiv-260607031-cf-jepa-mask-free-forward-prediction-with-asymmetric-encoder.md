---
# CSL-compatible fields
title: "CF-JEPA: Mask-free forward prediction with asymmetric encoder utilization for time-series representation learning"
author:
  - literal: "Jaehoon Lee"
  - literal: "Sunghyun Sim"
issued:
  date-parts:
    - [2026, 6, 5]
url: "https://arxiv.org/abs/2606.07031"

# Custom fields
paper_id: "2606.07031"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "crop-based-forward-jepa-cf-jepa"
  - "asymmetric-encoder-utilization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-08T05:48:28Z"
created_at: "2026-06-08T05:48:28Z"
---

# CF-JEPA: Mask-free forward prediction with asymmetric encoder utilization for time-series representation learning

**Authors**: Jaehoon Lee, Sunghyun Sim
**Date**: 2026-06-05
**Paper ID**: [arxiv:2606.07031](https://arxiv.org/abs/2606.07031)

## Summary

CF-JEPA is a mask-free self-supervised framework that avoids the temporal continuity disruption common in masking-based methods by predicting future representations from random context crops. The method leverages the intrinsic temporal ordering of time-series as a learning signal for multi-horizon prediction. By observing the rank-based asymmetry between online and EMA encoders, the authors demonstrate that routing tasks based on encoder properties—classification to the online encoder and forecasting/anomaly detection to the EMA target—significantly improves performance without increasing training costs.

## Key Contributions

- Introduces CF-JEPA, a mask-free self-supervised learning framework that uses multi-horizon forward prediction on random crops.
- Identifies and exploits rank-based asymmetry between online and EMA encoders to specialize representations for different downstream tasks.
- Achieves a 27% reduction in multivariate forecasting MSE while reaching state-of-the-art performance across UCR/UEA classification, electricity forecasting, and anomaly detection benchmarks.

## Key Concepts

- [[crop-based-forward-jepa-cf-jepa]]: A self-supervised framework for time-series representation learning that avoids data corruption by predicting future representations from random context crops instead of using masking.
- [[asymmetric-encoder-utilization]]: A task-routing strategy that assigns downstream tasks to specific encoders based on their distinct latent rank properties (online for discriminative, EMA for temporal smoothness).

## Archivist Review

The submission presents a novel self-supervised learning paradigm for time-series that avoids the continuity-breaking nature of masking. The two approved concepts (CF-JEPA and Asymmetric Encoder Utilization) capture a distinct, reusable methodology that is likely to impact future time-series representation learning research. General dataset names like UCR/UEA were rejected as they are aggregate categories rather than specific, novel benchmarks.

### Approved Concepts
- Crop-based Forward JEPA (CF-JEPA): Introduces a mask-free alternative to current SSL paradigms, avoiding temporal continuity issues in time-series learning.
- Asymmetric Encoder Utilization: Provides a systematic method for leveraging distinct rank properties in twin encoder architectures for improved downstream performance.

### Rejected Candidates
- [dataset] UCR (`ucr`) - generic: UCR is an umbrella collection of datasets rather than a specific singular benchmark dataset.
- [dataset] UEA (`uea`) - generic: UEA is an umbrella collection of datasets rather than a specific singular benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2606.07031)
- [PDF](https://arxiv.org/pdf/2606.07031)

