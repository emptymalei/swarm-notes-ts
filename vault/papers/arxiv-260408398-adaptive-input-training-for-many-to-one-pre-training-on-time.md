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
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-input-training"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:27:10Z"
created_at: "2026-04-10T15:27:10Z"
---

# ADAPTive Input Training for Many-to-One Pre-Training on Time-Series Classification

**Authors**: Paul Quinlan, Qingguo Li, Xiaodan Zhu
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08398](https://arxiv.org/abs/2604.08398)

## Summary

This paper introduces ADAPT, a novel pre-training paradigm designed to overcome the limitations of scaling time-series foundation models across diverse datasets. By efficiently aligning the physical properties of input data, ADAPT enables effective mixed-batch pre-training despite significant variations in sequence lengths and channel dimensions. The method is validated by training on 162 time-series classification datasets, achieving new state-of-the-art results and providing a robust framework for building generalist foundation models in the time-series domain.

## Key Contributions

- Introduces ADAPT, a pre-training paradigm for time-series that enables mixed-batch training on datasets with extreme discrepancies in input sizes and channel dimensions.
- Demonstrates the efficacy of mixed-batch pre-training by training on 162 distinct time-series classification datasets simultaneously.
- Achieves new state-of-the-art performance on time-series classification benchmarks, establishing a foundation for generalist time-series models.

## Open Questions & Future Work

- [[adaptive-pooling-fidelity-impact]]

## Key Concepts

- [[adaptive-input-training]]: A pre-training paradigm that enables efficient mixed-batch training on heterogeneous time-series data by aligning physical properties across disparate input sizes and dimensions.

## Archivist Review

I approved the ADAPTive Input Training concept as a novel paradigm for handling heterogeneous time-series during pre-training, which is critical for future foundation model development. The open question regarding the fidelity of adaptive pooling was also approved, as it addresses a fundamental trade-off in architectural design for time-series foundation models that will be widely applicable. No datasets were approved, as the paper relies on a collection of 162 datasets rather than introducing a single, critical, and distinct dataset that warrants a standalone note.

### Approved Concepts
- ADAPTive Input Training: Provides a novel paradigm to address the challenge of mixed-batch pre-training across time-series datasets with varying input sizes and dimensions.

### Approved Open Questions
- Fidelity of Adaptive Pooling: As time-series foundation models move toward larger scale and more diverse data, understanding the trade-offs between input normalization (via pooling) and signal fidelity is essential for ensuring that pre-trained models do not suffer from latent feature degradation.

## Links

- [Abstract](https://arxiv.org/abs/2604.08398)
- [PDF](https://arxiv.org/pdf/2604.08398)

