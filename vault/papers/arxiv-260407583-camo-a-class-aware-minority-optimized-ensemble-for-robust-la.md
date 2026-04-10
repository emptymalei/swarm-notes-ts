---
# CSL-compatible fields
title: "CAMO: A Class-Aware Minority-Optimized Ensemble for Robust Language Model Evaluation on Imbalanced Data"
author:
  - literal: "Mohamed Ehab"
  - literal: "Ali Hamdi"
  - literal: "Khaled Shaban"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07583"

# Custom fields
paper_id: "2604.07583"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "ensemble-learning"
  - "class-imbalance"
  - "language-models"
  - "evaluation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "camo-class-aware-minority-optimized-ensemble"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-10T15:29:30Z"
created_at: "2026-04-10T15:29:30Z"
---

# CAMO: A Class-Aware Minority-Optimized Ensemble for Robust Language Model Evaluation on Imbalanced Data

**Authors**: Mohamed Ehab, Ali Hamdi, Khaled Shaban
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07583](https://arxiv.org/abs/2604.07583)

## Summary

CAMO is a novel ensemble framework designed to address the performance degradation of language models on imbalanced datasets. By leveraging a hierarchical approach that integrates vote distributions, confidence calibration, and inter-model uncertainty, it dynamically boosts minority class predictions. The authors demonstrate consistent improvements in macro F1-score across both zero-shot and fine-tuned settings using various LLMs and SLMs on two domain-specific benchmarks.

## Key Contributions

- Proposed CAMO, a hierarchical ensemble technique that dynamically prioritizes underrepresented classes via confidence calibration and inter-model uncertainty.
- Achieved state-of-the-art performance in strict macro F1-score across 8 language models on highly imbalanced, domain-specific classification tasks.
- Demonstrated that CAMO's effectiveness is complementary to model fine-tuning, providing a robust, domain-neutral evaluation framework for imbalanced data.

## Open Questions & Future Work

- [[automated-dynamic-ensemble-parameter-tuning]]

## Key Concepts

- [[camo-class-aware-minority-optimized-ensemble]]: A hierarchical ensemble technique that dynamically boosts minority class predictions by integrating vote distributions, confidence calibration, and inter-model uncertainty.

## Archivist Review

I approved the CAMO ensemble framework as a reusable architectural pattern for addressing class imbalance. I also approved the open question regarding automated parameter tuning for ensembles, as it addresses a significant barrier to the real-world deployment of such models. I rejected the datasets as they are domain-specific and not broadly reusable across different fields of machine learning.

### Approved Concepts
- CAMO (Class-Aware Minority-Optimized): It provides a hierarchical approach to ensemble classification that integrates confidence calibration and inter-model uncertainty specifically to address minority class under-representation.

### Approved Open Questions
- Automated Dynamic Ensemble Parameter Tuning: Addressing manual hyperparameter optimization is a significant bottleneck for scaling ensemble methods to real-world, dynamic classification tasks.

### Rejected Candidates
- [dataset] DIAR-AI/Emotion (`diar-ai-emotion`) - low_impact: These are domain-specific evaluation benchmarks and do not qualify as foundational or highly reusable datasets for the broader research community.
- [dataset] BEA 2025 (`bea-2025`) - low_impact: These are domain-specific evaluation benchmarks and do not qualify as foundational or highly reusable datasets for the broader research community.

## Links

- [Abstract](https://arxiv.org/abs/2604.07583)
- [PDF](https://arxiv.org/pdf/2604.07583)

