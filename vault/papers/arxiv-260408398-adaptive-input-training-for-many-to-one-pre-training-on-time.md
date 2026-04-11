---
# CSL-compatible fields
title: "ADAPTive Input Training for Many-to-One Pre-Training on Time-Series Classification"
author:
  - literal: "Paul Quinlan"
  - literal: "Qingguo Li"
  - literal: "Xiaodan Zhu"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08398"

# Custom fields
paper_id: "2604.08398"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series"
  - "foundation-models"
  - "self-supervised-learning"
  - "representation-learning"
  - "classification"
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-input-training"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:44:07Z"
created_at: "2026-04-11T04:44:07Z"
---

# ADAPTive Input Training for Many-to-One Pre-Training on Time-Series Classification

**Authors**: Paul Quinlan, Qingguo Li, Xiaodan Zhu
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08398](https://arxiv.org/abs/2604.08398)

## Summary

This paper addresses the challenge of generalizing time-series foundation models across diverse datasets with inconsistent input sizes and channel dimensions. The authors propose ADAPT (ADAPTive Input Training), a paradigm that aligns the physical properties of heterogeneous time-series data to allow for effective mixed-batch pre-training. By training on 162 classification datasets simultaneously, the model demonstrates significant improvements, setting new state-of-the-art performance on standard classification benchmarks.

## Key Contributions

- Introduced ADAPT (ADAPTive Input Training), a pre-training paradigm that enables mixed-batch training for time-series models across datasets with heterogeneous input and channel dimensions.
- Demonstrated the effectiveness of ADAPT by pre-training on a massive collection of 162 time-series classification datasets simultaneously.
- Achieved new state-of-the-art performance on various time-series classification benchmarks, establishing a scalable foundation for generalist time-series modeling.

## Open Questions & Future Work

- [[adaptive-pooling-fidelity-impact]]

## Key Concepts

- [[adaptive-input-training]]: A pre-training paradigm that aligns physical properties of heterogeneous time-series data to facilitate mixed-batch training.

## Archivist Review

I approved 'Adaptive Input Training' as it defines a novel and highly reusable paradigm for aligning heterogeneous time-series data at scale. The open question 'Adaptive pooling fidelity impact' was approved (using the existing vault slug 'adaptive-pooling-fidelity-impact') because it addresses a critical, unresolved trade-off in the development of time-series foundation models. No datasets were approved as none were specifically named or described as unique contributions.

### Approved Concepts
- Adaptive Input Training: Enables simultaneous pre-training on a diverse collection of time-series datasets with varying input dimensions, which is a fundamental requirement for time-series foundation models.

### Approved Open Questions
- Adaptive pooling fidelity impact: Adaptive pooling is a core component for scaling time-series models across diverse, heterogeneous datasets, but the trade-off between alignment efficiency and feature preservation is not yet well-quantified.

## Links

- [Abstract](https://arxiv.org/abs/2604.08398)
- [PDF](https://arxiv.org/pdf/2604.08398)

