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
  - "video-prediction"
  - "diffusion-models"
  - "hierarchical-modeling"
  - "foundation-models"
  - "autonomous-driving"
architectures:
  []
datasets:
  []
concept_slugs:
  - "semantics-first-hierarchical-forecasting"
  - "mixed-supervision-conditioning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:02:20Z"
created_at: "2026-04-14T05:02:20Z"
---

# Representations Before Pixels: Semantics-Guided Hierarchical Video Prediction

**Authors**: Efstathios Karypidis, Spyros Gidaris, Nikos Komodakis
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11707](https://arxiv.org/abs/2604.11707)

## Summary

Re2Pix is a hierarchical video prediction framework that decouples the forecasting process into two distinct stages: predicting future semantic representations in a frozen vision foundation model's feature space and conditioning a latent diffusion model on those representations to synthesize final RGB frames. By prioritizing scene semantics before appearance, the approach significantly improves temporal consistency and visual quality in dynamic environments like autonomous driving. To handle the inevitable errors in autoregressive semantic predictions during inference, the authors introduce nested dropout and mixed supervision, which effectively bridge the train-test distribution gap.

## Key Contributions

- Introduced Re2Pix, a hierarchical framework that decomposes video prediction into semantic representation forecasting followed by conditional visual synthesis.
- Leveraged features from frozen vision foundation models to improve scene dynamics modeling and temporal consistency.
- Developed nested dropout and mixed supervision strategies to mitigate the train-test mismatch in autoregressive generation and enhance robustness against prediction errors.

## Open Questions & Future Work

- [[long-horizon-temporal-coherence-in-hierarchical-world-models]]

## Key Concepts

- [[semantics-first-hierarchical-forecasting]]: A hierarchical framework that predicts future scene representations in a frozen vision foundation model's feature space before synthesizing RGB frames.
- [[mixed-supervision-conditioning]]: A training strategy for hierarchical models that interleaves ground-truth and predicted latent representations to improve robustness to autoregressive error accumulation.

## Archivist Review

I approved a core concept for the hierarchical framework and a critical training technique for mitigating train-test mismatch. I also defined an open question regarding the specific challenge of temporal coherence in these multi-stage models, which is the core obstacle to their long-term viability. I rejected the paper-specific model name and generic future work suggestions in favor of more technically precise, reusable abstractions.

### Approved Concepts
- Semantics-First Hierarchical Forecasting: It introduces a modular paradigm for video prediction, decoupling semantic dynamic modeling in a frozen feature space from pixel-level synthesis, which is a major shift from end-to-end approaches.
- Mixed Supervision Conditioning: It addresses the critical train-test distribution shift inherent in multi-stage autoregressive forecasting models where downstream modules are trained on ground-truth priors but evaluated on model-generated ones.

### Approved Open Questions
- Hierarchical Temporal Coherence Bottlenecks: This bottleneck is central to the viability of hierarchical generative modeling for real-world robotics and autonomous navigation tasks.

### Rejected Candidates
- [concept] Re2Pix (`re2pix`) - paper_local: Re2Pix is the paper-specific name for a broader framework; I have approved 'Semantics-First Hierarchical Forecasting' as the more descriptive, reusable concept.
- [concept] Nested Dropout and Mixed Supervision (`nested-dropout-and-mixed-supervision`) - subcomponent_of_broader_mechanism: These are two distinct strategies grouped into one; I have extracted 'Mixed Supervision' as the more conceptually central mechanism and rejected the combined label.
- [open_question] Expanding Hierarchical Video Prediction (`broadening-semantic-priors-controllability`) - low_impact: This candidate is too broad and resembles a generic call for more research; I have replaced it with a focused question on the specific bottleneck of temporal coherence in hierarchical models.

## Links

- [Abstract](https://arxiv.org/abs/2604.11707)
- [PDF](https://arxiv.org/pdf/2604.11707)

