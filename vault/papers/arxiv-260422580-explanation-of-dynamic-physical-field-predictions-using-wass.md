---
# CSL-compatible fields
title: "Explanation of Dynamic Physical Field Predictions using WassersteinGrad: Application to Autoregressive Weather Forecasting"
author:
  - literal: "Younes Essafouri"
  - literal: "Laure Raynaud"
  - literal: "Luciano Drozda"
  - literal: "Laurent Risser"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2604.22580"

# Custom fields
paper_id: "2604.22580"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "weather-forecasting"
  - "explainability"
  - "autoregressive-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "wassersteingrad"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T05:11:00Z"
created_at: "2026-04-27T05:11:00Z"
---

# Explanation of Dynamic Physical Field Predictions using WassersteinGrad: Application to Autoregressive Weather Forecasting

**Authors**: Younes Essafouri, Laure Raynaud, Luciano Drozda, Laurent Risser
**Date**: 2026-04-24
**Paper ID**: [arxiv:2604.22580](https://arxiv.org/abs/2604.22580)

## Summary

This paper addresses the challenge of explaining neural network predictions for dynamic physical fields, such as weather forecasting, where traditional pointwise averaging of attribution maps fails due to spatial misalignment. The authors identify that stochastic perturbations in these fields cause geometric displacements rather than stationary noise. To solve this, they propose WassersteinGrad, which utilizes entropic Wasserstein barycenters to aggregate perturbed maps while preserving spatial features. Experiments on regional weather data demonstrate that this approach yields more robust and interpretable explanations compared to traditional gradient-based attribution baselines.

## Key Contributions

- Identifies that pointwise averaging of perturbed attribution maps on dynamic physical fields suffers from geometric displacement-induced blurring.
- Introduces WassersteinGrad, an explainability method that computes the entropic Wasserstein barycenter of perturbed attribution maps for geometric consensus.
- Demonstrates the superior explainability of WassersteinGrad over standard gradient-based baselines in both single-step and autoregressive regional weather forecasting scenarios.

## Open Questions & Future Work

- [[physically-informed-perturbation-xai]]

## Key Concepts

- [[wassersteingrad]]: An explainability method for dynamic physical fields that computes the entropic Wasserstein barycenter of perturbed attribution maps to achieve geometric consensus.

## Archivist Review

I approved the WassersteinGrad concept as a novel, reusable solution for explainability in spatially correlated dynamic fields. I also approved the open question regarding physically informed perturbations, as it identifies a major limitation in current XAI methodology where generic noise fails to respect underlying physical dynamics. No datasets were approved as they were not specific or central enough to the work.

### Approved Concepts
- WassersteinGrad: It provides a novel solution to the geometric misalignment of attribution maps in dynamic physical fields, which is a significant limitation of existing pointwise averaging techniques.

### Approved Open Questions
- Physically Informed Input Perturbations: Current XAI perturbation methods often ignore the structural properties of physical fields, leading to potentially incoherent explanations that do not align with the underlying dynamics of the modeled domain.

## Links

- [Abstract](https://arxiv.org/abs/2604.22580)
- [PDF](https://arxiv.org/pdf/2604.22580)

