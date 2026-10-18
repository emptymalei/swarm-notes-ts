---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Preliminary Exploration of Large Models Based on Self-Supervised Learning for Health Monitoring of Power Electronic Converters"
description: "This paper introduces PE-TSFM, a time-series foundation model designed for the health monitoring of power electronic converters. The authors utilize the PatchTST architecture and self-supervised learning to train on 143 million timestamps of operational data, where 98% is unlabeled, effectively bypassing the scarcity of labeled degradation samples. PE-TSFM achieves 87% accuracy in degradation classification, more than doubling the performance of conventional baselines. The results demonstrate that large-scale unlabeled operational data can be successfully leveraged to create robust, generalizable models for industrial hardware monitoring."
resource: "https://arxiv.org/abs/2610.18138"
tags:
  - "time-series"
  - "self-supervised-learning"
  - "foundation-models"
  - "industrial-applications"
  - "anomaly-detection"
  - "few-shot-learning"
  - "generalization"
  - "deep-learning"
timestamp: "2026-10-18T00:59:52Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xinyuan Liao"
  - literal: "Xiangtian Deng"
  - literal: "Yang Liu"
  - literal: "Zhaobing Cai"
  - literal: "Haoran Wang"
  - literal: "Yi Zhang"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18138"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "cross-topology-generalization-in-power-electronics"
    description: "Investigating the extent to which feature representations learned from specific power electronic systems (such as traction converters) can generalize to heterogeneous topologies, including solar inverters, EV chargers, or different manufacturers' hardware."
  - name: "interpretability-of-power-electronics-foundation-models"
    description: "Exploration of mechanistic interpretability techniques to map learned temporal patches in transformer-based foundation models back to specific physical degradation phenomena in industrial sensor data."
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:59:52Z"
created_at: "2026-10-18T00:59:52Z"
---

# Preliminary Exploration of Large Models Based on Self-Supervised Learning for Health Monitoring of Power Electronic Converters

**Authors**: Xinyuan Liao, Xiangtian Deng, Yang Liu, Zhaobing Cai, Haoran Wang, Yi Zhang
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18138](https://arxiv.org/abs/2610.18138)

## Summary

This paper introduces PE-TSFM, a time-series foundation model designed for the health monitoring of power electronic converters. The authors utilize the PatchTST architecture and self-supervised learning to train on 143 million timestamps of operational data, where 98% is unlabeled, effectively bypassing the scarcity of labeled degradation samples. PE-TSFM achieves 87% accuracy in degradation classification, more than doubling the performance of conventional baselines. The results demonstrate that large-scale unlabeled operational data can be successfully leveraged to create robust, generalizable models for industrial hardware monitoring.

## Key Contributions

- Developed PE-TSFM, a specialized time-series foundation model for health monitoring in power electronics using the PatchTST architecture.
- Curated and utilized a large-scale industrial dataset of 143 million timestamps from operating traction converters, with 98% of the data being unlabeled for self-supervised training.
- Achieved a classification accuracy of 87% for module degradation, significantly outperforming traditional time-series models which scored between 27% and 45%.
- Demonstrated the model's strong few-shot learning and generalization capabilities across different operational conditions in real-world power converter environments.

## Limitations

The study is described as a 'preliminary exploration,' and the evaluation is focused on a specific type of traction converter, which may limit immediate conclusions about universal applicability across all converter topologies.

## Open Questions & Future Work

- [[cross-topology-generalization-in-power-electronics]]
- [[interpretability-of-power-electronics-foundation-models]]

## Archivist Review

The paper explores the application of foundation models to power electronics health monitoring. PE-TSFM was rejected as a concept because it represents a specific model instance for a single application rather than a reusable architectural contribution. The open questions were approved as they address significant research bottlenecks in industrial AI, specifically concerning hardware generalization and interpretability of transformer patches in physical systems. No datasets were approved as the training data is proprietary and not presented as a reusable benchmark.

### Approved Open Questions
- Cross-Topology Model Generalization: Determining the limits of cross-topology generalization is critical for creating 'universal' industrial foundation models that do not require retraining for every specific piece of hardware.
- Interpretability of Industrial Foundation Models: Industrial adoption of AI models hinges on the ability to explain 'why' a failure is predicted, particularly in high-stakes environments like power electronics and transportation.

### Rejected Candidates
- [concept] PE-TSFM (`pe-tsfm`) - paper_local: PE-TSFM is a specific model instance named in this paper, applying existing architectures (PatchTST) to a niche domain, rather than a reusable architectural or algorithmic concept.
- [concept] PatchTST (`patchtst`) - duplicate_existing: PatchTST is an existing architecture (Nie et al.) and is already widely recognized in the time-series literature.
- [dataset] Traction Converter Dataset (`traction-converter-dataset`) - paper_local: The dataset appears to be a proprietary or specific operational dataset rather than a named, publicly available benchmark for the research community.

## Links

- [Abstract](https://arxiv.org/abs/2610.18138)
- [PDF](https://arxiv.org/pdf/2610.18138)

