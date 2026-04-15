---
# CSL-compatible fields
title: "Representations Before Pixels: Semantics-Guided Hierarchical Video Prediction"
author:
  - literal: "Efstathios Karypidis"
  - literal: "Spyros Gidaris"
  - literal: "Nikos Komodakis"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11707"

# Custom fields
paper_id: "2604.11707"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "video-prediction"
  - "diffusion-models"
  - "semantic-representation-learning"
  - "autonomous-driving"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mixed-supervision-conditioning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:06:46Z"
created_at: "2026-04-15T05:06:46Z"
---

# Representations Before Pixels: Semantics-Guided Hierarchical Video Prediction

**Authors**: Efstathios Karypidis, Spyros Gidaris, Nikos Komodakis
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11707](https://arxiv.org/abs/2604.11707)

## Summary

Re2Pix is a hierarchical video prediction framework designed to handle the complexity of dynamic environments by forecasting semantic representations before synthesizing RGB pixels. By performing prediction in the feature space of a frozen vision foundation model and conditioning a latent diffusion model on these features, the approach effectively separates scene dynamics from appearance generation. To resolve the train-test mismatch inherent in autoregressive feature forecasting, the authors propose nested dropout and mixed supervision as robust conditioning strategies. This decomposition yields significant improvements in temporal semantic consistency and visual fidelity on challenging autonomous driving datasets.

## Key Contributions

- Proposes Re2Pix, a hierarchical framework that decouples video forecasting into semantic representation prediction followed by representation-guided latent diffusion synthesis.
- Introduces nested dropout and mixed supervision strategies to mitigate train-test mismatch errors during autoregressive representation forecasting.
- Demonstrates improved temporal semantic consistency and perceptual quality on complex autonomous driving benchmarks compared to standard diffusion-based video prediction baselines.

## Open Questions & Future Work

- [[hierarchical-semantic-priors-video-prediction]]

## Key Concepts

- [[mixed-supervision-conditioning]]: A training strategy that improves generative model robustness to noise in autoregressively predicted latent conditions by blending ground-truth and inferred representation sequences.

## Archivist Review

The review process focused on identifying reusable forecasting mechanisms and fundamental unresolved bottlenecks. The concept 'mixed-supervision-conditioning' was approved as a robust technique for managing train-test distribution shifts in hierarchical forecasting. 'nested-dropout' was rejected as it is a subcomponent of this mechanism. The open question regarding semantic priors was approved for its importance in advancing towards more grounded, structured world models.

### Approved Concepts
- Mixed Supervision Conditioning: It directly addresses the fundamental distribution shift problem in hierarchical generative forecasting where intermediate representations are autoregressively predicted.

### Approved Open Questions
- Advancing Hierarchical Semantic Priors: This direction is critical for moving beyond current VFM feature representations towards more physically grounded and controllable world modeling.

### Rejected Candidates
- [concept] nested-dropout (`nested-dropout`) - subcomponent_of_broader_mechanism: This is a specific training heuristic and a subcomponent of the broader mixed supervision conditioning approach.

## Links

- [Abstract](https://arxiv.org/abs/2604.11707)
- [PDF](https://arxiv.org/pdf/2604.11707)

