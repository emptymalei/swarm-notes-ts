---
# CSL-compatible fields
title: "Feature Anchors for Time-Series Sensor-Based Human Activity Recognition"
author:
  - literal: "Ruijie Yao"
  - literal: "Chenhang Li"
  - literal: "Danyang Zhuo"
  - literal: "Tingjun Chen"
  - literal: "Xiaoyue Ni"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25092"

# Custom fields
paper_id: "2604.25092"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "sensor-based-har"
  - "feature-engineering"
  - "model-interpretability"
architectures:
  []
datasets:
  []
concept_slugs:
  - "feature-anchors"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:11:55Z"
created_at: "2026-04-29T05:11:55Z"
---

# Feature Anchors for Time-Series Sensor-Based Human Activity Recognition

**Authors**: Ruijie Yao, Chenhang Li, Danyang Zhuo, Tingjun Chen, Xiaoyue Ni
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25092](https://arxiv.org/abs/2604.25092)

## Summary

This paper addresses the limitations of purely latent deep learning models in Human Activity Recognition by introducing 'Feature Anchors', which allow handcrafted time-series features (TSFs) to remain explicit and adaptable within the model. The proposed Temporal Conditioning Network for Feature Anchors (TCNet) uses raw IMU signal context to modulate these anchors via dynamic scaling, bias, and gating in feature space. The approach bridges the interpretability of handcrafted features with the flexibility of deep learning, resulting in significant performance gains across multiple benchmark datasets compared to existing methods.

## Key Contributions

- Introduces TCNet, an architecture that modulates handcrafted time-series feature anchors via context-dependent gating and scaling parameters.
- Demonstrates superior performance across five HAR datasets, including significant mF1 improvements over rTsfNet (e.g., +14.6 points on Daphnet).
- Shows through ablation that maintaining explicit anchor semantics provides more discriminative power than standard latent-only representations.

## Open Questions & Future Work

- [[learning-adaptive-anchor-vocabulary]]

## Key Concepts

- [[feature-anchors]]: Handcrafted time-series features that remain explicit within a neural network and are dynamically modulated by context-aware parameters.

## Archivist Review

I approved the core concept of 'Feature Anchors' and the corresponding open question regarding the automation of their selection. I rejected TCNet as it is a specific architectural implementation of the broader Feature Anchors mechanism. No datasets were approved as they are standard benchmarks in the HAR field and do not constitute novel scientific artifacts in the context of the vault.

### Approved Concepts
- Feature Anchors: This is the core contribution; it bridges the gap between interpretable handcrafted features and adaptable deep latent representations.

### Approved Open Questions
- Learning Adaptive Anchor Vocabularies: Automatically learning the most discriminative feature anchors could eliminate the need for manual feature engineering, making the TCNet framework more generalizable across different sensing domains.

### Rejected Candidates
- [concept] TCNet (`tcnet`) - subcomponent_of_broader_mechanism: TCNet is a specific implementation of the Feature Anchors concept, and per the review policy, we favor the overarching mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.25092)
- [PDF](https://arxiv.org/pdf/2604.25092)

