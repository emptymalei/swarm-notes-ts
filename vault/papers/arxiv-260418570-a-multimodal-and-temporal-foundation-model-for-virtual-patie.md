---
# CSL-compatible fields
title: "A multimodal and temporal foundation model for virtual patient representations at healthcare system scale"
author:
  - literal: "Andrew Zhang"
  - literal: "Tong Ding"
  - literal: "Sophia J. Wagner"
  - literal: "Caiwei Tian"
  - literal: "Ming Y. Lu"
  - literal: "Rowland Pettit"
  - literal: "Joshua E. Lewis"
  - literal: "Alexandre Misrahi"
  - literal: "Dandan Mo"
  - literal: "Long Phi Le"
  - literal: "Faisal Mahmood"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18570"

# Custom fields
paper_id: "2604.18570"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "healthcare"
  - "multimodal-learning"
  - "foundation-models"
  - "temporal-modeling"
  - "clinical-prediction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "virtual-patient-representations"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:05:39Z"
created_at: "2026-04-22T05:05:39Z"
---

# A multimodal and temporal foundation model for virtual patient representations at healthcare system scale

**Authors**: Andrew Zhang, Tong Ding, Sophia J. Wagner, Caiwei Tian, Ming Y. Lu, Rowland Pettit, Joshua E. Lewis, Alexandre Misrahi, Dandan Mo, Long Phi Le, Faisal Mahmood
**Date**: 2026-04-20
**Paper ID**: [arxiv:2604.18570](https://arxiv.org/abs/2604.18570)

## Summary

Apollo is a multimodal temporal foundation model that integrates three decades of longitudinal clinical data—including structured events, images, and text—into unified virtual patient representations. By encoding these diverse data into a shared embedding space, the model supports generalized clinical forecasting for long-term patient health outcomes and operational metrics. Performance was validated across 322 distinct prognosis and retrieval tasks on a massive held-out cohort of 1.4 million patients, demonstrating both predictive accuracy and clinical interpretability.

## Key Contributions

- Introduces Apollo, a multimodal temporal foundation model trained on 25 billion records from 7.2 million patients across 28 modalities.
- Establishes a unified representation space ('atlas of medical concepts') for longitudinal clinical journeys containing structured and unstructured data.
- Demonstrates generalized forecasting capabilities across 322 tasks including disease onset, progression, and treatment response, alongside multimodal medical search functionality.

## Open Questions & Future Work

- [[clinical-foundation-model-temporal-robustness]]

## Key Concepts

- [[virtual-patient-representations]]: A unified latent embedding space designed to capture the entire longitudinal care journey of a patient across multiple medical modalities.

## Archivist Review

I approved 'Virtual Patient Representations' as a conceptual contribution defining the unified embedding task for multi-modal patient data. I approved the open question regarding temporal robustness for clinical foundation models, as it captures the fundamental challenge of ensuring long-term predictive stability in the face of evolving medical systems. I rejected 'Apollo Foundation Model' as it is a specific model instance rather than a reusable concept.

### Approved Concepts
- Virtual Patient Representations: This is a foundational concept in the paper representing the goal of converting longitudinal, high-dimensional, multimodal clinical data into a compact, usable latent space.

### Approved Open Questions
- Foundation Model Temporal Robustness: This is a critical bottleneck for deploying foundation models in clinical settings where data distribution shifts significantly over time.

### Rejected Candidates
- [concept] Apollo Foundation Model (`apollo-foundation-model`) - paper_local: Specific model name is not a reusable architectural or methodology concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.18570)
- [PDF](https://arxiv.org/pdf/2604.18570)

