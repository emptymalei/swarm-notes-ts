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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "mechanistic-interpretability-for-ai-weather-models"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-25T04:56:44Z"
created_at: "2026-04-25T04:56:44Z"
---

# Mechanistic Interpretability Tool for AI Weather Models

**Authors**: Kirsten I. Tempest, Matthias Beylich, George C. Craig
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20467](https://arxiv.org/abs/2604.20467)

## Summary

This paper presents a new open-source framework to facilitate mechanistic interpretability in AI-based weather prediction models, which are often treated as black boxes. By applying techniques such as Principal Component Analysis (PCA) and cosine similarity to latent representations, the tool enables researchers to map internal model states to known meteorological phenomena. The authors demonstrate the utility of this approach by identifying latent feature directions within the GraphCast model that correlate with specific atmospheric variables and synoptic-scale patterns.

## Key Contributions

- Introduces an open-source mechanistic interpretability tool designed for analyzing internal latent representations in AI weather forecasting models.
- Demonstrates the tool's efficacy by identifying latent space directions corresponding to meteorological features like mid-latitude synoptic-scale waves and specific humidity.
- Provides a framework for diagnosing black-box AI weather models using established ML interpretability techniques such as PCA and cosine similarity.

## Open Questions & Future Work

- [[mechanistic-circuits-weather-models]]

## Key Concepts

- [[mechanistic-interpretability-for-ai-weather-models]]: A framework and toolkit for analyzing internal latent states of weather emulation models to map model activations to physical atmospheric features.

## Archivist Review

The paper introduces a specialized toolkit for applying mechanistic interpretability to weather emulation, which is a significant and reusable contribution for the field of AI-assisted scientific discovery. I approved the framework as a concept and the problem of functional circuit identification as an open question, as these address the fundamental transparency bottleneck in high-stakes climate modeling. Other potential candidates were deemed too generic (e.g., PCA/cosine similarity) or were simply descriptive of the tool's implementation rather than foundational concepts.

### Approved Concepts
- Mechanistic Interpretability for AI Weather Models: As AI models replace traditional NWP, specialized interpretability tools are becoming critical for scientific validation. This framework provides a standard approach for mapping latent representations to physical meteorological phenomena.

### Approved Open Questions
- Mechanistic Circuits in AI Weather Models: Without identifying functional circuits, individual feature identification remains largely anecdotal; validating these pathways is necessary to bridge the gap between ML activations and physical causality.

## Links

- [Abstract](https://arxiv.org/abs/2604.20467)
- [PDF](https://arxiv.org/pdf/2604.20467)

