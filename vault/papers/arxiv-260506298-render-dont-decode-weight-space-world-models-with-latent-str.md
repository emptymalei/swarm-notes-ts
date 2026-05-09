---
# CSL-compatible fields
title: "Render, Don't Decode: Weight-Space World Models with Latent Structural Disentanglement"
author:
  - literal: "Roussel Desmond Nzoyem"
  - literal: "Mauro Comi"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06298"

# Custom fields
paper_id: "2605.06298"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "weight-space-world-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:11:00Z"
created_at: "2026-05-09T05:11:00Z"
---

# Render, Don't Decode: Weight-Space World Models with Latent Structural Disentanglement

**Authors**: Roussel Desmond Nzoyem, Mauro Comi
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06298](https://arxiv.org/abs/2605.06298)

## Summary

NOVA addresses the inefficiency and lack of interpretability in standard pixel-based world models by representing system states as the weights of implicit neural representations (INRs). Instead of relying on costly decoders, the model uses analytical rendering, allowing for efficient generation and zero-shot super-resolution. Experimental results show that NOVA naturally disentangles scene components like background and foreground, enabling flexible editing of content and dynamics on consumer-grade hardware.

## Key Contributions

- Introduces NOVA, a framework that represents system states as weight parameters of coordinate-based INRs, replacing traditional opaque latents.
- Eliminates the decoder bottleneck by using analytical rendering, resulting in high compactness and zero-shot super-resolution capabilities.
- Achieves emergent disentanglement of background, foreground, and motion dynamics without auxiliary losses or adversarial training.

## Key Concepts

- [[weight-space-world-model]]: A framework for world modeling that defines system states as weights of an implicit neural representation rather than standard vector-based latents.

## Archivist Review

I approved the 'weight-space-world-model' concept as it represents a significant architectural shift in world modeling that is likely to be reused. The specific implementation name 'NOVA' was rejected in favor of the more descriptive concept slug. No datasets or open questions from the provided analysis met the threshold for standalone archival.

### Approved Concepts
- Weight-Space World Model: It shifts the world model paradigm from opaque vector-based latents to weight-space coordinate representations, enabling structural disentanglement and decoder-free inference.

### Rejected Candidates
- [concept] NOVA (`nova-weight-space-world-model`) - subcomponent_of_broader_mechanism: The model name 'NOVA' is a paper-specific implementation name; it is subsumed by the more descriptive 'weight-space-world-model' concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.06298)
- [PDF](https://arxiv.org/pdf/2605.06298)

