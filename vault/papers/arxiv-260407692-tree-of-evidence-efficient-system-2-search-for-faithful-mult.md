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
processed_at: "2026-04-10T15:29:10Z"
created_at: "2026-04-10T15:29:10Z"
---

# Tree-of-Evidence: Efficient "System 2" Search for Faithful Multimodal Grounding

**Authors**: Micky C. Nnamdi, Benoit L. Marteau, Yishan Zhong, J. Ben Tamo, May D. Wang
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.07692](https://arxiv.org/abs/2604.07692)

## Summary

Large Multimodal Models often lack transparency in complex, high-stakes reasoning tasks involving heterogeneous data like time-series and text. The authors introduce Tree-of-Evidence (ToE), an inference-time search algorithm that frames interpretability as a discrete optimization problem, utilizing Evidence Bottlenecks to select compact data subsets that reproduce model predictions. Evaluation across clinical and industrial datasets confirms that ToE maintains predictive performance while providing auditable evidence traces, significantly outperforming existing saliency-based methods in sparse-budget scenarios.

## Key Contributions

- Introduces Tree-of-Evidence (ToE), a beam search algorithm that interprets multimodal model decisions by identifying compact, discrete evidence sets.
- Demonstrates that ToE retains >0.98 of full-model AUROC using only five evidence units across healthcare and industrial fault detection tasks.
- Shows superior decision agreement and lower probability fidelity error compared to standard saliency-based interpretability methods in sparse budget regimes.

## Open Questions & Future Work

- [[toe-architecture-extensibility]]

## Key Concepts

- [[tree-of-evidence-toe]]: An inference-time beam search algorithm that identifies minimal, discrete subsets of multimodal evidence required to reproduce a Large Multimodal Model's prediction.

## Archivist Review

I approved the Tree-of-Evidence algorithm as it provides a distinct, search-based paradigm for multimodal interpretability, moving beyond traditional saliency or soft-attention methods. I also approved the open question regarding architecture extensibility because the transition from late-fusion to deep cross-attention is a known bottleneck for discrete interpretability techniques. MIMIC-IV and eICU were rejected as they are routine, widely used clinical benchmarks rather than novel research datasets.

### Approved Concepts
- Tree-of-Evidence (ToE): Provides a novel search-based approach to multimodal interpretability that treats evidence selection as a discrete optimization problem rather than relying on soft-attention weights.

### Approved Open Questions
- ToE Cross-Architecture Extensibility: As LMMs increasingly utilize deep cross-attention, developing interpretability methods that maintain auditability across these architectures is critical for high-stakes deployment.

## Links

- [Abstract](https://arxiv.org/abs/2604.07692)
- [PDF](https://arxiv.org/pdf/2604.07692)

