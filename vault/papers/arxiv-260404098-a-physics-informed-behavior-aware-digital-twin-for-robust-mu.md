---
# CSL-compatible fields
title: "A Physics-Informed, Behavior-Aware Digital Twin for Robust Multimodal Forecasting of Core Body Temperature in Precision Livestock Farming"
author:
  - literal: "Riasad Alvi"
  - literal: "Mohaimenul Azam Khan Raiaan"
  - literal: "Sadia Sultana Chowa"
  - literal: "Arefin Ittesafun Abian"
  - literal: "Reem E Mohamed"
  - literal: "Md Rafiqul Islam"
  - literal: "Yakub Sebastian"
  - literal: "Sheikh Izzal Azid"
  - literal: "Sami Azam"
issued:
  date-parts:
    - [2026, 4, 5]
url: "https://arxiv.org/abs/2604.04098"

# Custom fields
paper_id: "2604.04098"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "physics-informed-ml"
  - "digital-twin"
  - "ensemble-learning"
  - "uncertainty-quantification"
  - "precision-livestock-farming"
architectures:
  []
datasets:
  - "MmCows"
concept_slugs:
  []
dataset_slugs:
  - "mmcows"
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:54:45Z"
created_at: "2026-04-07T04:54:45Z"
---

# A Physics-Informed, Behavior-Aware Digital Twin for Robust Multimodal Forecasting of Core Body Temperature in Precision Livestock Farming

**Authors**: Riasad Alvi, Mohaimenul Azam Khan Raiaan, Sadia Sultana Chowa, Arefin Ittesafun Abian, Reem E Mohamed, Md Rafiqul Islam, Yakub Sebastian, Sheikh Izzal Azid, Sami Azam
**Date**: 2026-04-05
**Paper ID**: [arxiv:2604.04098](https://arxiv.org/abs/2604.04098)

## Summary

This paper presents a physics-informed digital twin framework for forecasting core body temperature in dairy cattle to support precision livestock farming. The system integrates ODE-based thermoregulation models, Gaussian processes, and behavioral Markov chains with real-time sensor data via a Kalman filter. By fusing these physics-based insights with raw sensor data in a three-stage stacked ensemble architecture, the framework enables accurate, uncertainty-aware heat stress prediction. Evaluation on the high-frequency MmCows dataset demonstrates significant performance gains over traditional approaches, particularly for 2-hour ahead forecasting.

## Key Contributions

- Introduces a physics-informed digital twin framework that integrates ODE-based thermoregulation models with Gaussian process and Kalman filter refinements for core body temperature forecasting.
- Develops a three-stage stacked ensemble model utilizing modality-specific LightGBM experts to fuse heterogeneous physiological and behavioral features.
- Achieves 2-hour ahead forecasting of core body temperature with a cross-validated R2 of 0.783 and PICP of 92.38% on the MmCows dataset.

## Open Questions & Future Work

- [[generalization-of-dt-livestock-models]]

## Archivist Review

The paper provides a strong application of physics-informed digital twins to livestock temperature monitoring. I have approved the MmCows dataset as a specific, named high-frequency physiological dataset and the open question regarding the generalizability of these digital twins across heterogeneous environments. I rejected the proposed architecture and ensemble method as they are domain-specific implementations of standard practices, which do not satisfy the criteria for a permanent, standalone concept note.

### Approved Open Questions
- Generalization of Digital Twin Livestock Models: Achieving cross-farm and cross-breed robustness is a critical bottleneck for deploying digital twins from small, controlled research environments to large-scale, heterogeneous commercial agricultural operations.

### Rejected Candidates
- [concept] Physics-informed digital twin framework (`physics-informed-digital-twin-framework`) - not_novel: The concept of physics-informed digital twins is broadly established; this specific integration of ODEs and Kalman filters for livestock is a domain-specific implementation rather than a foundational methodological concept.
- [concept] Three-stage stacked ensemble architecture (`three-stage-stacked-ensemble`) - not_novel: Stacked ensemble architectures are standard practice in machine learning and this specific variation is a routine application-level architectural choice rather than a reusable concept.

## Datasets

- [[mmcows]]

## Links

- [Abstract](https://arxiv.org/abs/2604.04098)
- [PDF](https://arxiv.org/pdf/2604.04098)

