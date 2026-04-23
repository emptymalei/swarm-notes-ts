---
# CSL-compatible fields
title: "Mechanistic Interpretability Tool for AI Weather Models"
author:
  - literal: "Kirsten I. Tempest"
  - literal: "Matthias Beylich"
  - literal: "George C. Craig"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20467"

# Custom fields
paper_id: "2604.20467"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "physics-informed-state-space-model"
  - "graph-neural-ode"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mechanistic-interpretability-for-ai-weather-models"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-23T05:06:36Z"
created_at: "2026-04-23T05:06:36Z"
---

# Mechanistic Interpretability Tool for AI Weather Models

**Authors**: Kirsten I. Tempest, Matthias Beylich, George C. Craig
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20467](https://arxiv.org/abs/2604.20467)

## Summary

The paper introduces an open-source mechanistic interpretability tool designed to demystify black-box AI weather models by analyzing their internal latent representations. By applying techniques such as cosine similarity and Principal Component Analysis, the authors identify specific directions within the model's latent space that correspond to physical meteorological phenomena. Using GraphCast as a case study, the tool successfully maps latent channel combinations to synoptic-scale waves and specific humidity, providing a pathway for building confidence in data-driven weather predictions.

## Key Contributions

- Developed an open-source toolkit for mechanistic interpretability specifically tailored for AI-based weather forecasting models.
- Demonstrated the extraction of interpretable meteorological features (e.g., synoptic-scale waves, humidity) from GraphCast by identifying specific directions in latent space.
- Enabled the application of standard interpretability techniques like PCA and cosine similarity to complex atmospheric latent representations.

## Open Questions & Future Work

- [[mechanistic-interpretability-weather-models-circuits]]

## Key Concepts

- [[mechanistic-interpretability-for-ai-weather-models]]: A framework for analyzing internal latent representations of AI weather models to map them to interpretable meteorological phenomena.

## Archivist Review

I have approved the core concept of mechanistic interpretability for AI weather models and its associated open question regarding circuit discovery. I rejected no candidates because the input only proposed one of each, both of which were high-quality and aligned with the vault's standards for long-term research tracking. The approval focuses on the methodology of mapping black-box latent spaces to physical meteorological features.

### Approved Concepts
- Mechanistic Interpretability for AI Weather Models: It bridges the gap between black-box AI weather models and physical interpretability by mapping latent channels to meteorological features, which is essential for institutional trust.

### Approved Open Questions
- Mechanistic circuits in weather models: Understanding these internal circuits is critical for building trust in operational weather forecasting and for potentially uncovering new physical insights modeled by AI.

## Links

- [Abstract](https://arxiv.org/abs/2604.20467)
- [PDF](https://arxiv.org/pdf/2604.20467)

