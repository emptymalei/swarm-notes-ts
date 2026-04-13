---
# CSL-compatible fields
title: "Drift-Aware Online Dynamic Learning for Nonstationary Multivariate Time Series: Application to Sintering Quality Prediction"
author:
  - literal: "Yumeng Zhao"
  - literal: "Shengxiang Yang"
  - literal: "Xianpeng Wang"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.09358"

# Custom fields
paper_id: "2604.09358"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "adaptation"
  - "online-learning"
  - "spatiotemporal"
architectures:
  []
datasets:
  []
concept_slugs:
  - "drift-severity-guided-hierarchical-fine-tuning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-13T05:09:05Z"
created_at: "2026-04-13T05:09:05Z"
---

# Drift-Aware Online Dynamic Learning for Nonstationary Multivariate Time Series: Application to Sintering Quality Prediction

**Authors**: Yumeng Zhao, Shengxiang Yang, Xianpeng Wang
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.09358](https://arxiv.org/abs/2604.09358)

## Summary

DA-MSDL is an online dynamic learning framework designed for nonstationary multivariate time series in complex industrial systems like iron ore sintering. It utilizes a multi-scale bi-branch convolutional backbone to extract spatiotemporal features and incorporates unsupervised drift detection via Maximum Mean Discrepancy (MMD) to address label verification latency. By employing a drift-severity-guided hierarchical fine-tuning strategy and prioritized experience replay, the framework achieves robust performance and mitigates catastrophic forgetting during continuous adaptation. Evaluation on industrial sintering and public benchmark data confirms its superiority over existing methods under severe concept drift conditions.

## Key Contributions

- Proposes the Drift-Aware Multi-Scale Dynamic Learning (DA-MSDL) framework to handle nonstationary multivariate time series under label verification latency.
- Introduces an MMD-based unsupervised drift detection mechanism to trigger proactive model adaptation before label availability.
- Develops a drift-severity-guided hierarchical fine-tuning strategy coupled with prioritized experience replay to mitigate catastrophic forgetting and ensure rapid distribution alignment.

## Open Questions & Future Work

- [[resource-aware-online-adaptation-constraints]]

## Key Concepts

- [[drift-severity-guided-hierarchical-fine-tuning]]: A fine-tuning framework that modulates update intensity based on detected distribution drift severity to balance rapid adaptation with catastrophic forgetting prevention.

## Archivist Review

The framework's approach to hierarchical fine-tuning via drift-severity guidance represents a distinct and reusable mechanism for online learning in nonstationary environments. I have rejected the physics-integration open question as it is a broad research direction rather than a specific, trackable bottleneck. I have focused the resource-aware question specifically on the conflict between adaptation and edge constraints, which is a key barrier in industrial ML.

### Approved Concepts
- Drift-Severity-Guided Hierarchical Fine-Tuning: This provides a principled, reusable mechanism for managing the stability-plasticity dilemma in online learning by coupling drift detection with selective model updates.

### Approved Open Questions
- Resource-Aware Online Adaptation Constraints: The computational burden of continuous fine-tuning is a primary barrier to deploying adaptive models in distributed, real-time industrial environments.

### Rejected Candidates
- [open_question] Integrating Physics into Online Learning (`integrating-physics-into-online-learning`) - generic: Physics-informed ML is a well-established field; this is too broad and generic for a specific open-question note.

## Links

- [Abstract](https://arxiv.org/abs/2604.09358)
- [PDF](https://arxiv.org/pdf/2604.09358)

