---
# CSL-compatible fields
title: "Efficient and Adaptive Human Activity Recognition via LLM Backbones"
author:
  - literal: "Aleksandr Bredikhin"
  - literal: "Philippe Lalanda"
  - literal: "German Vega"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12019"

# Custom fields
paper_id: "2605.12019"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "structured-convolutional-projection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:23:59Z"
created_at: "2026-05-13T05:23:59Z"
---

# Efficient and Adaptive Human Activity Recognition via LLM Backbones

**Authors**: Aleksandr Bredikhin, Philippe Lalanda, German Vega
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12019](https://arxiv.org/abs/2605.12019)

## Summary

This paper proposes repurposing pretrained large language models (LLMs) as efficient, scalable backbones for human activity recognition (HAR). By introducing a structured convolutional projection, the authors map raw accelerometer and gyroscope signals into the LLM's latent space while keeping the backbone frozen and applying LoRA for task adaptation. This method achieves high performance in low-data and few-shot scenarios, proving that LLMs can function as foundation models for sensor-based time-series tasks while minimizing training overhead.

## Key Contributions

- Introduces a paradigm for reusing frozen LLM backbones as generic temporal feature extractors for inertial sensor-based HAR.
- Develops a structured convolutional projection mechanism to bridge the modality gap between raw time-series sensor data and LLM token spaces.
- Demonstrates significant reductions in training cost and improved few-shot performance using parameter-efficient fine-tuning (LoRA) compared to training domain-specific Transformers from scratch.

## Key Concepts

- [[structured-convolutional-projection]]: A mapping layer that aligns multivariate sensor signals with the latent embedding space of pretrained models.

## Archivist Review

I approved the 'Structured Convolutional Projection' as it represents a generalizable architectural design for cross-modal adaptation between sensor time series and frozen transformer backbones. I rejected the broader concept of using LLMs for HAR as it is an application-specific realization of the emerging field of foundation models for time series, which is already well-represented in the vault.

### Approved Concepts
- Structured Convolutional Projection: Acts as the critical bridge enabling the use of frozen text-based LLM architectures for non-linguistic sensor time series data.

### Rejected Candidates
- [concept] LLM as Temporal Backbone for HAR (`llm-as-temporal-backbone-for-har`) - subcomponent_of_broader_mechanism: This is a specific application instance of the broader 'foundation model for time series' trend.

## Links

- [Abstract](https://arxiv.org/abs/2605.12019)
- [PDF](https://arxiv.org/pdf/2605.12019)

