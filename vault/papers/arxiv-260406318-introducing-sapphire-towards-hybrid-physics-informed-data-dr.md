---
# CSL-compatible fields
title: "Introducing sapphire: Towards Hybrid Physics-Informed, Data-Driven Modeling of Galaxy Formation"
author:
  - literal: "Viraj Pandya"
  - literal: "Greg L. Bryan"
  - literal: "T. Lucas Makinen"
  - literal: "Austen Gabrielpillai"
  - literal: "Christopher Carr"
  - literal: "Drummond B. Fielding"
  - literal: "Lars Hernquist"
  - literal: "Matthew Ho"
  - literal: "Kartheik Iyer"
  - literal: "Christian Kragh Jespersen"
  - literal: "Sophie Koudmani"
  - literal: "Marta Laska"
  - literal: "Pablo Lemos"
  - literal: "Christopher C. Lovell"
  - literal: "Lucia A. Perez"
  - literal: "William F. Robinson"
  - literal: "Rachel S. Somerville"
  - literal: "Tjitske K. Starkenburg"
  - literal: "Richard Stiskalek"
  - literal: "Bryan Terrazas"
  - literal: "G. Mark Voit"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.06318"

# Custom fields
paper_id: "2604.06318"
paper_source: "arxiv"
domain: "physics-informed-ml"
tags:
  []
architectures:
  []
datasets:
  - "manga"
concept_slugs:
  - "differentiable-semi-analytic-modeling"
dataset_slugs:
  - "manga"
skill: "GeneralMLSkill"
processed_at: "2026-04-09T04:56:34Z"
created_at: "2026-04-09T04:56:34Z"
---

# Introducing sapphire: Towards Hybrid Physics-Informed, Data-Driven Modeling of Galaxy Formation

**Authors**: Viraj Pandya, Greg L. Bryan, T. Lucas Makinen, Austen Gabrielpillai, Christopher Carr, Drummond B. Fielding, Lars Hernquist, Matthew Ho, Kartheik Iyer, Christian Kragh Jespersen, Sophie Koudmani, Marta Laska, Pablo Lemos, Christopher C. Lovell, Lucia A. Perez, William F. Robinson, Rachel S. Somerville, Tjitske K. Starkenburg, Richard Stiskalek, Bryan Terrazas, G. Mark Voit
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.06318](https://arxiv.org/abs/2604.06318)

## Summary

The paper introduces 'sapphire', a novel, automatically differentiable, and GPU-accelerated semi-analytic model (SAM) for simulating galaxy formation in JAX. By enabling the computation of exact Jacobians for nonlinear dynamical equations, the tool facilitates high-performance gradient-based parameter inference and sensitivity analysis. Experiments using MaNGA survey data and HMC sampling demonstrate that galaxy self-regulation is dominated by preventative feedback, offering a scalable framework for hybrid physics-informed discovery in astrophysics.

## Key Contributions

- Introduced sapphire, a JAX-based, automatically differentiable, and GPU-accelerated semi-analytic model for galaxy formation.
- Enabled gradient-based inference in galaxy formation modeling by computing exact Jacobian matrices of nonlinear evolution equations.
- Demonstrated through Fisher and HMC forecasts that star-formation self-regulation is primarily driven by preventative feedback rather than ejective mechanisms.

## Limitations

The current model relies on an initial physical example; expanding the library of integrated physical sub-models is necessary for broader astrophysical applicability.

## Open Questions & Future Work

- [[minimal-state-variables-galaxy-evolution-modeling]]

## Key Concepts

- [[differentiable-semi-analytic-modeling]]: The application of automatic differentiation and GPU acceleration to semi-analytic models for galaxy formation, enabling gradient-based parameter optimization.

## Archivist Review

The paper presents a significant advancement in astrophysics by enabling gradient-based inference on complex dynamical models through automatic differentiation. I approved the methodological concept 'Differentiable Semi-Analytic Modeling' as it represents a broader trend in physics-informed ML, and the MaNGA dataset as it is a core evaluation standard in this field. I also approved a refined open question regarding the identification of minimal state variables for galaxy evolution to address the fundamental theoretical uncertainty identified by the authors.

### Approved Concepts
- Differentiable Semi-Analytic Modeling: This represents the shift toward JAX-based, differentiable physics models in astrophysics, allowing for gradient-based inference in previously intractable simulations.

### Approved Open Questions
- Minimal state variables in galaxy formation: This is a fundamental theoretical bottleneck that limits the predictive power of current physics-informed modeling efforts in astrophysics.

### Rejected Candidates
- [concept] sapphire (`sapphire-sam`) - paper_local: This is a specific tool name rather than a broader reusable methodological concept; 'Differentiable Semi-Analytic Modeling' captures the reusable architectural paradigm.
- [open_question] Defining minimal state variables (`independent-state-variables-galaxy-formation`) - other: The background was overly verbose and specific to the SAM vs Hydro dichotomy; a refined version with a clearer, more universal title was provided.

## Datasets

- [[manga]]

## Links

- [Abstract](https://arxiv.org/abs/2604.06318)
- [PDF](https://arxiv.org/pdf/2604.06318)

