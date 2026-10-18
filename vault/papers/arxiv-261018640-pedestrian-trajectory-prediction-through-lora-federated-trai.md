---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Pedestrian Trajectory Prediction through LoRA Federated Training"
description: "This paper introduces a federated learning framework for pedestrian trajectory prediction in Intelligent Transport Systems (ITS). By employing Low-Rank Adaptation (LoRA) to fine-tune a foundation model at the edge, the system achieves high prediction accuracy while drastically reducing the communication payload between vehicles and infrastructure. The authors further optimize radio resource utilization by increasing the ratio of local training rounds to communication rounds and introduce a novel metric to evaluate communication efficiency in V2I scenarios."
resource: "https://arxiv.org/abs/2610.18640"
tags:
  - "Intelligent Transportation Systems"
  - "trajectory-prediction"
  - "federated-learning"
  - "foundation-models"
  - "time-series"
  - "edge-computing"
  - "computational-efficiency"
  - "spatio-temporal-modeling"
timestamp: "2026-10-18T00:55:57Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Simone Travagliati"
  - literal: "Maria Luisa Merani"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18640"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "lora-federated-training"
    description: "A federated learning paradigm that integrates Low-Rank Adaptation (LoRA) to minimize communication overhead by only transmitting low-rank update matrices between clients and the server."
datasets:
  []
open_questions:
  - name: "non-iid-peft-convergence"
    description: "How do parameter-efficient fine-tuning techniques like LoRA specifically interact with extreme spatial non-IID data distributions in dynamic environments like vehicular networks, and do they exhibit different convergence properties compared to full-parameter federated fine-tuning?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:55:57Z"
created_at: "2026-10-18T00:55:57Z"
---

# Pedestrian Trajectory Prediction through LoRA Federated Training

**Authors**: Simone Travagliati, Maria Luisa Merani
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18640](https://arxiv.org/abs/2610.18640)

## Summary

This paper introduces a federated learning framework for pedestrian trajectory prediction in Intelligent Transport Systems (ITS). By employing Low-Rank Adaptation (LoRA) to fine-tune a foundation model at the edge, the system achieves high prediction accuracy while drastically reducing the communication payload between vehicles and infrastructure. The authors further optimize radio resource utilization by increasing the ratio of local training rounds to communication rounds and introduce a novel metric to evaluate communication efficiency in V2I scenarios.

## Key Contributions

- Proposed a distributed federated learning architecture for V2I environments to fine-tune foundation models for pedestrian trajectory prediction.
- Integrated Low-Rank Adaptation (LoRA) into the federated training loop to significantly reduce the size of model updates and radio resource usage.
- Demonstrated that increasing local training iterations per communication round further reduces communication frequency without sacrificing prediction accuracy.
- Introduced a novel figure of merit to quantify and optimize the radio resource consumption of federated learning in cellular vehicular networks.

## Limitations

The paper does not explicitly address the impact of vehicle mobility patterns or variable connection quality (fading/interference) on the federated aggregation process.

## Open Questions & Future Work

- [[non-iid-peft-convergence]]

## Key Concepts

- [[lora-federated-training]]: A federated learning paradigm that integrates Low-Rank Adaptation (LoRA) to minimize communication overhead by only transmitting low-rank update matrices between clients and the server.

## Archivist Review

Approved 'LoRA Federated Training' as it represents a significant and recurring architectural trend for edge AI. The 'V2I Radio Resource Metric' was rejected as it is a local evaluation tool. For open questions, I approved a refined version of the Non-IID question, as it addresses a fundamental research bottleneck in the convergence of parameter-efficient methods in distributed settings.

### Approved Concepts
- LoRA Federated Training: The combination of Parameter-Efficient Fine-Tuning (PEFT) and Federated Learning (FL) is a critical paradigm for deploying large-scale models in bandwidth-constrained edge environments.

### Approved Open Questions
- Convergence of Federated PEFT under Extreme Heterogeneity: Understanding the robustness of low-rank updates to skewed data distributions is essential for ensuring reliable global model convergence in decentralized ITS applications.

### Rejected Candidates
- [concept] V2I Radio Resource Figure of Merit (`v2i-radio-resource-metric`) - paper_local: This is a paper-specific evaluation metric rather than a broadly applicable architectural or algorithmic concept.
- [open_question] Edge Inference Latency vs. Prediction Accuracy (`inference-latency-foundation-models-its`) - generic: This describes a standard engineering trade-off (accuracy vs. speed) rather than a novel or specific research bottleneck.
- [concept] Foundation Model for Pedestrian Trajectory Forecasting (`foundation-model-for-pedestrian-trajectory-forecasting`) - subcomponent_of_broader_mechanism: The paper treats the foundation model as a black-box component to be fine-tuned rather than proposing a new specific architecture.

## Links

- [Abstract](https://arxiv.org/abs/2610.18640)
- [PDF](https://arxiv.org/pdf/2610.18640)

