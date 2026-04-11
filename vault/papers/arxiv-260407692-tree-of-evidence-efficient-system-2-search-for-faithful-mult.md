---
# CSL-compatible fields
title: "Tree-of-Evidence: Efficient \"System 2\" Search for Faithful Multimodal Grounding"
author:
  - literal: "Micky C. Nnamdi"
  - literal: "Benoit L. Marteau"
  - literal: "Yishan Zhong"
  - literal: "J. Ben Tamo"
  - literal: "May D. Wang"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.07692"

# Custom fields
paper_id: "2604.07692"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "tree-of-evidence-toe"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:46:01Z"
created_at: "2026-04-11T04:46:01Z"
---

# Tree-of-Evidence: Efficient "System 2" Search for Faithful Multimodal Grounding

**Authors**: Micky C. Nnamdi, Benoit L. Marteau, Yishan Zhong, J. Ben Tamo, May D. Wang
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.07692](https://arxiv.org/abs/2604.07692)

## Summary

The paper introduces Tree-of-Evidence (ToE), an inference-time search algorithm designed to improve the transparency of Large Multimodal Models (LMMs). By replacing traditional soft attention with discrete Evidence Bottlenecks, ToE identifies compact, auditable sets of data units that justify a model's prediction. The method demonstrates robust performance across healthcare and fault detection tasks, maintaining high predictive accuracy while offering significantly better fidelity and interpretability than existing post-hoc saliency methods.

## Key Contributions

- Introduces Tree-of-Evidence (ToE), an inference-time search algorithm that identifies compact evidence sets for multimodal LMM predictions.
- Demonstrates ToE retains over 98% of full-model AUROC using only five evidence units across diverse clinical and fault detection tasks.
- Provides superior decision agreement and lower fidelity error compared to attention-based interpretability methods under sparse evidence constraints.

## Open Questions & Future Work

- [[toe-grounding-in-complex-fusions]]

## Key Concepts

- [[tree-of-evidence-toe]]: An inference-time search algorithm that frames model interpretability as a discrete optimization problem using Evidence Bottlenecks.

## Archivist Review

I approved the Tree-of-Evidence concept as a novel, reusable inference-time interpretability strategy. I also approved a refined version of the open question regarding the extension of discrete interpretability methods to modern, tightly coupled multimodal architectures. Other datasets were rejected as they are standard, established benchmarks in clinical and fault-detection literature.

### Approved Concepts
- Tree-of-Evidence (ToE): Provides a novel inference-time discrete search strategy for multimodal interpretability, offering a scalable alternative to opaque soft attention mechanisms.

### Approved Open Questions
- ToE grounding in complex fusions: As LMMs shift towards deeper cross-modal interaction, maintaining auditable grounding is essential for deployment in high-stakes domains.

## Links

- [Abstract](https://arxiv.org/abs/2604.07692)
- [PDF](https://arxiv.org/pdf/2604.07692)

