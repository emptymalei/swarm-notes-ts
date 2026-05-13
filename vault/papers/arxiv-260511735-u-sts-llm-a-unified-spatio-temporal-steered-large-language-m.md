---
# CSL-compatible fields
title: "U-STS-LLM A Unified Spatio-Temporal Steered Large Language Model for Traffic Prediction and Imputation"
author:
  - literal: "Yichen Zhang"
  - literal: "Jun Li"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11735"

# Custom fields
paper_id: "2605.11735"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "traffic-prediction"
  - "llm-adaptation"
  - "spatio-temporal-learning"
  - "imputation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dynamic-spatio-temporal-attention-bias-generator"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:24:39Z"
created_at: "2026-05-13T05:24:39Z"
---

# U-STS-LLM A Unified Spatio-Temporal Steered Large Language Model for Traffic Prediction and Imputation

**Authors**: Yichen Zhang, Jun Li
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11735](https://arxiv.org/abs/2605.11735)

## Summary

U-STS-LLM is a unified framework that adapts pre-trained LLMs for spatio-temporal traffic prediction and imputation tasks by leveraging a steering mechanism. The framework utilizes a Dynamic Spatio-Temporal Attention Bias Generator to guide the LLM's attention using structural graph knowledge, while employing LoRA and a Gated Adaptive Fusion mechanism for efficient, stable training. This approach demonstrates superior performance over specialized Spatio-Temporal Graph Neural Networks in both long-horizon forecasting and high-missing-rate imputation scenarios.

## Key Contributions

- Proposes U-STS-LLM, a unified framework for multi-task traffic forecasting and imputation using spatio-temporally steered LLMs.
- Introduces a Dynamic Spatio-Temporal Attention Bias Generator that integrates functional graph structures with transient nodal states to explicitly steer attention.
- Achieves state-of-the-art performance on cellular traffic datasets for both long-horizon forecasting and high-missing-rate imputation tasks.

## Open Questions & Future Work

- [[multimodal-urban-context-integration]]

## Key Concepts

- [[dynamic-spatio-temporal-attention-bias-generator]]: A module that generates attention biases by combining static functional graphs and transient nodal states to guide LLM behavior for non-linguistic spatio-temporal tasks.

## Archivist Review

The Dynamic Spatio-Temporal Attention Bias Generator is approved as a reusable mechanism for steering LLMs with graph priors, which is a significant architectural trend. The open question regarding multimodal urban context is approved as it addresses the core limitation of current signal-only spatio-temporal foundation models. Other proposed concepts were deemed either too generic or subcomponents of the primary steering mechanism.

### Approved Concepts
- Dynamic Spatio-Temporal Attention Bias Generator: Provides a novel, reusable mechanism for grounding pre-trained LLM attention mechanisms in external graph-structured data, crucial for non-linguistic spatio-temporal tasks.

### Approved Open Questions
- Multimodal Urban Context Integration: Moving beyond purely signal-based sequence modeling to incorporate heterogeneous urban context is essential for building comprehensive 'urban foundation models'.

### Rejected Candidates
- [concept] Unified multi-task objective for ST-LLM (`unified-multi-task-objective-st-llm`) - generic: "Unified multi-task training" is a generic methodology rather than a novel conceptual contribution.

## Links

- [Abstract](https://arxiv.org/abs/2605.11735)
- [PDF](https://arxiv.org/pdf/2605.11735)

