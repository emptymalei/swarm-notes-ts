---
# CSL-compatible fields
title: "High-resolution probabilistic estimation of three-dimensional regional ocean dynamics from sparse surface observations"
author:
  - literal: "Niloofar Asefi"
  - literal: "Tianning Wu"
  - literal: "Ruoying He"
  - literal: "Ashesh Chattopadhyay"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.02850"

# Custom fields
paper_id: "2604.02850"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "depth-aware-generative-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-06T05:02:47Z"
created_at: "2026-04-06T05:02:47Z"
---

# High-resolution probabilistic estimation of three-dimensional regional ocean dynamics from sparse surface observations

**Authors**: Niloofar Asefi, Tianning Wu, Ruoying He, Ashesh Chattopadhyay
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.02850](https://arxiv.org/abs/2604.02850)

## Summary

This paper introduces a conditional denoising diffusion probabilistic model (DDPM) to reconstruct high-resolution 3D ocean dynamics from extremely sparse (99.9% missing) surface-only observations. By leveraging continuous depth embeddings, the framework learns a unified vertical representation that allows for accurate subsurface temperature, salinity, and velocity estimation without needing a background dynamical model. Evaluated on Gulf of Mexico data, the approach successfully captures both large-scale circulation and multiscale variability, highlighting its potential for data-limited climate monitoring.

## Key Contributions

- Introduces a conditional DDPM that reconstructs 3D ocean subsurface states (temperature, salinity, velocity) using only sparse (99.9% missing) surface observations.
- Demonstrates that continuous depth embeddings enable the model to learn a unified vertical representation and generalize to unobserved depths without a background dynamical model.
- Validated on the Gulf of Mexico, showing superior recovery of multiscale variability and heat transport compared to traditional interpolation methods.

## Open Questions & Future Work

- [[physics-constrained-generative-ocean-reconstruction]]

## Key Concepts

- [[depth-aware-generative-framework]]: A conditional diffusion-based approach for reconstructing 3D volumetric data from highly sparse surface observations using continuous depth embeddings.

## Archivist Review

Approved the 'Depth-aware Generative Framework' as it establishes a reusable paradigm for 3D reconstruction from 2D sparse signals via continuous embedding, which is highly relevant to geophysical forecasting. The open question was reframed to focus on the broader challenge of integrating physics constraints into generative ocean modeling, rather than being limited to just 'diffusion'. The regional dataset was rejected as it is not a primary community-standard benchmark.

### Approved Concepts
- Depth-aware Generative Framework: It provides a scalable method for reconstructing full 3D volumetric states from 2D sparse observations using learned continuous depth embeddings, useful for various geophysical modeling tasks.

### Approved Open Questions
- Physics-constrained generative ocean reconstruction: Improving the reliability of generative models for subsurface ocean velocity is critical for ensuring dynamical accuracy in climate monitoring and state estimation applications.

### Rejected Candidates
- [dataset] Gulf of Mexico regional ocean dataset (`gulf-of-mexico-regional-ocean-dataset`) - not_novel: This is a region-specific regional model output rather than a fundamental benchmark or landmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.02850)
- [PDF](https://arxiv.org/pdf/2604.02850)

