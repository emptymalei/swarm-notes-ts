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
  - "nlp"
  - "computer-vision"
architectures:
  []
datasets:
  []
concept_slugs:
  - "tree-of-evidence-toe"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-12T05:04:53Z"
created_at: "2026-04-12T05:04:53Z"
---

# Tree-of-Evidence: Efficient "System 2" Search for Faithful Multimodal Grounding

**Authors**: Micky C. Nnamdi, Benoit L. Marteau, Yishan Zhong, J. Ben Tamo, May D. Wang
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.07692](https://arxiv.org/abs/2604.07692)

## Summary

Tree-of-Evidence (ToE) addresses the lack of faithful interpretability in Large Multimodal Models (LMMs) by reframing multimodal grounding as a discrete optimization problem. Instead of relying on opaque attention weights, ToE employs lightweight Evidence Bottlenecks and beam search to identify a compact set of discrete data units (e.g., vital signs, text segments) sufficient for model prediction. Empirical evaluations across clinical and fault-detection tasks demonstrate that ToE generates auditable evidence traces while preserving predictive performance, even under extreme evidence constraints.

## Key Contributions

- Introduces Tree-of-Evidence (ToE), an inference-time search algorithm using Evidence Bottlenecks for discrete, interpretable multimodal grounding.
- ToE maintains >0.98 of full-model AUROC using only five evidence units across clinical and fault-detection tasks.
- Demonstrates superior decision agreement and lower probability fidelity error under sparse evidence constraints compared to post-hoc saliency methods.

## Open Questions & Future Work

- [[interpreting-early-fusion-multimodal-models]]

## Key Concepts

- [[tree-of-evidence-toe]]: An inference-time search algorithm that identifies a compact, discrete subset of multimodal input data to explain model predictions.

## Archivist Review

I approved Tree-of-Evidence (ToE) as a novel discrete interpretability framework that shifts the paradigm from continuous attention-based saliency to explicit evidence search. I also approved the open question regarding the extension of such discrete grounding techniques to dense, early-fusion model architectures, which is a major unresolved challenge for faithful multimodal interpretability. Existing datasets were not approved as they are common benchmarks rather than novel, domain-specific resources.

### Approved Concepts
- Tree-of-Evidence (ToE): It frames interpretability as a discrete optimization search problem rather than relying on standard soft attention mechanisms.

### Approved Open Questions
- Interpreting Early-Fusion Multimodal Models: Many modern state-of-the-art multimodal models rely on dense cross-modal fusion, which current discrete evidence-selection interpretability methods cannot directly handle.

## Links

- [Abstract](https://arxiv.org/abs/2604.07692)
- [PDF](https://arxiv.org/pdf/2604.07692)

