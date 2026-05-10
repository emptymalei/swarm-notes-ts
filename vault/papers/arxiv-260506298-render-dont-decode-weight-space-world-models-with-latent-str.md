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
domain: "computer-vision"
tags:
  - "generative-models"
  - "world-models"
  - "representation-learning"
  - "implicit-neural-representations"
  - "video-generation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "weight-space-world-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:19:06Z"
created_at: "2026-05-10T05:19:06Z"
---

# Render, Don't Decode: Weight-Space World Models with Latent Structural Disentanglement

**Authors**: Roussel Desmond Nzoyem, Mauro Comi
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06298](https://arxiv.org/abs/2605.06298)

## Summary

NOVA is a novel world modeling framework that replaces traditional opaque latent spaces with weight-space representations using coordinate-based implicit neural representations (INRs). By analytically rendering these weights, the model avoids costly decoders while maintaining high efficiency, portability, and zero-shot super-resolution capabilities. Experimental results show that NOVA naturally disentangles structural scene components and dynamics without auxiliary losses, achieving state-of-the-art controllable forecasting on consumer-grade hardware.

## Key Contributions

- Introduces NOVA, a weight-space world model framework that represents environment states using coordinate-based implicit neural representations (INRs).
- Eliminates the decoder bottleneck through analytical rendering of weight-space representations, supporting zero-shot super-resolution.
- Demonstrates emergence of structural disentanglement (background, foreground, motion) without adversarial objectives, enabling targeted scene editing.

## Key Concepts

- [[weight-space-world-model]]: A world modelling approach that parameterizes environment states as the weights of an implicit neural representation, enabling analytical rendering and disentangled dynamics.

## Archivist Review

The paper introduces a significant shift in world modeling by moving from opaque latent spaces to weight-space representations via coordinate-based INRs. I have approved 'Weight-Space World Models' as it constitutes the core, reusable methodological contribution. No other candidates were provided, and I maintained a strict threshold to avoid premature inclusion of sub-modules or general generative terminology.

### Approved Concepts
- Weight-Space World Models: Represents a paradigm shift from pixel-space latent variables to weight-space representations for world models, offering high interpretability and efficiency.

## Links

- [Abstract](https://arxiv.org/abs/2605.06298)
- [PDF](https://arxiv.org/pdf/2605.06298)

