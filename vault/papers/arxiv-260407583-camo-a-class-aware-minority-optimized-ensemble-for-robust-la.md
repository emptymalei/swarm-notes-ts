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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "camo-class-aware-minority-optimized-ensemble"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-11T04:46:23Z"
created_at: "2026-04-11T04:46:23Z"
---

# CAMO: A Class-Aware Minority-Optimized Ensemble for Robust Language Model Evaluation on Imbalanced Data

**Authors**: Mohamed Ehab, Ali Hamdi, Khaled Shaban
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07583](https://arxiv.org/abs/2604.07583)

## Summary

CAMO is a class-aware ensemble framework designed to address performance degradation on minority classes in imbalanced classification tasks. By integrating hierarchical vote distributions, confidence calibration, and inter-model uncertainty, the method dynamically boosts underrepresented classes without sacrificing overall model performance. Extensive experiments using eight language models across two highly imbalanced datasets show that CAMO consistently outperforms traditional ensemble methods, particularly under fine-tuned conditions.

## Key Contributions

- Introduces CAMO, an ensemble technique that dynamically prioritizes underrepresented classes through hierarchical vote distribution and confidence calibration.
- Achieves superior performance on the DIAR-AI/Emotion and BEA 2025 datasets compared to seven baseline ensemble algorithms across various LLMs and SLMs.
- Demonstrates that CAMO's performance gains are consistent in both zero-shot and fine-tuned settings, establishing a domain-neutral robust evaluation framework.

## Open Questions & Future Work

- [[autonomous-ensemble-parameter-adaptation]]

## Key Concepts

- [[camo-class-aware-minority-optimized-ensemble]]: An ensemble framework that dynamically boosts underrepresented classes using hierarchical vote distributions and confidence calibration to handle class imbalance.

## Archivist Review

I approved the CAMO ensemble framework as it offers a specific, modular approach to class imbalance that is conceptually distinct from general ensemble techniques. I also approved the open question regarding autonomous ensemble parameter adaptation, as it addresses a fundamental, recurring bottleneck in machine learning deployment. Both domain-specific datasets were rejected as they are not widely established benchmarks.

### Approved Concepts
- CAMO (Class-Aware Minority-Optimized Ensemble): It provides a novel mechanism for mitigating minority class degradation in ensemble learning by integrating hierarchical vote distributions, confidence calibration, and inter-model uncertainty.

### Approved Open Questions
- Autonomous Ensemble Parameter Adaptation: Automated hyperparameter adaptation is a critical bottleneck for deploying ensemble methods in dynamic, real-world classification systems where human-in-the-loop tuning is infeasible.

### Rejected Candidates
- [dataset] DIAR-AI/Emotion dataset (`diar-ai-emotion-dataset`) - not_reusable: Dataset is domain-specific and not a general benchmark.
- [dataset] BEA 2025 dataset (`bea-2025-dataset`) - not_reusable: Dataset is domain-specific and not a general benchmark.

## Links

- [Abstract](https://arxiv.org/abs/2604.07583)
- [PDF](https://arxiv.org/pdf/2604.07583)

