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
processed_at: "2026-04-12T05:02:51Z"
created_at: "2026-04-12T05:02:51Z"
---

# ADAPTive Input Training for Many-to-One Pre-Training on Time-Series Classification

**Authors**: Paul Quinlan, Qingguo Li, Xiaodan Zhu
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08398](https://arxiv.org/abs/2604.08398)

## Summary

The paper addresses the scalability challenge in time-series foundation models, where conventional pre-training struggles to integrate diverse datasets with varying input dimensions. The authors propose ADAPT (ADAPTive Input Training), a pre-training paradigm that dynamically aligns disparate time-series input structures to facilitate efficient mixed-batch learning. By training on 162 diverse classification datasets, the proposed method achieves state-of-the-art results, representing a significant advancement toward generalist foundation models for time-series data.

## Key Contributions

- Introduces ADAPT, a pre-training paradigm for time-series foundation models that aligns varying input sizes and channel dimensions to enable simultaneous mixed-batch pre-training.
- Demonstrates that ADAPT enables effective training on a large-scale collection of 162 time-series classification datasets.
- Sets new state-of-the-art performance on time-series classification benchmarks by overcoming the limitations of previous one-to-many pre-training approaches.

## Open Questions & Future Work

- [[adaptive-pooling-fidelity-impact]]
- [[scaling-diversity-in-time-series-pretraining]]

## Key Concepts

- [[adaptive-input-training]]: A pre-training paradigm for time-series foundation models that aligns disparate physical data properties to enable efficient mixed-batch training.

## Archivist Review

The approved concepts and questions focus on the core contribution of handling heterogeneous time-series input structures and the fundamental challenges associated with scaling data diversity. I renamed one open question to match existing vault nomenclature styles ('adaptive-pooling-fidelity-impact'). No datasets were approved as none were specifically named or identified as distinct, canonical benchmarks worth tracking.

### Approved Concepts
- Adaptive Input Training: It addresses the fundamental challenge of discrepancy in input sizes and channel dimensions in time-series pre-training, which is critical for scaling to many datasets.

### Approved Open Questions
- Adaptive Pooling Fidelity Impact: This is critical for understanding the theoretical limitations of current alignment strategies and ensuring that pre-trained models do not discard nuances essential for specialized downstream tasks.
- Scaling Data Diversity for Time-Series Foundation Models: Understanding the scaling laws of time-series pre-training is essential for building robust, generalist foundation models that can consistently benefit from increasingly diverse data sources.

## Links

- [Abstract](https://arxiv.org/abs/2604.08398)
- [PDF](https://arxiv.org/pdf/2604.08398)

