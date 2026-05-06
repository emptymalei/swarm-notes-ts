---
# CSL-compatible fields
title: "Predicting and controlling nonlinear neuro-mechanical locomotion dynamics"
author:
  - literal: "Alexander E. Cohen"
  - literal: "Jörn Dunkel"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03362"

# Custom fields
paper_id: "2605.03362"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "probabilistic-modeling"
  - "control-theory"
  - "biomedical-signal-processing"
architectures:
  []
datasets:
  []
concept_slugs:
  - "multiscale-neuromechanical-modeling-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:12:35Z"
created_at: "2026-05-06T05:12:35Z"
---

# Predicting and controlling nonlinear neuro-mechanical locomotion dynamics

**Authors**: Alexander E. Cohen, Jörn Dunkel
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03362](https://arxiv.org/abs/2605.03362)

## Summary

This paper addresses the challenge of connecting high-dimensional neural activity to physical behavior by developing a multiscale modeling framework. By integrating spectral mode representations with Helmholtz-Nambu decompositions and Bayesian inference, the model provides an interpretable and data-efficient method for predicting locomotion dynamics. The approach is validated on C. elegans recordings and shows potential for real-time control of locomotion through inferred neural activation patterns.

## Key Contributions

- Introduces a multiscale neuromechanical modeling framework combining spectral mode representations, Helmholtz-Nambu decompositions, and Bayesian inference.
- Demonstrates accurate prediction of C. elegans locomotion dynamics from neural activity time series.
- Enables real-time prediction of neural activation patterns for controlling locomotion, providing a basis for optogenetic experiments.

## Open Questions & Future Work

- [[generalized-neuromechanical-manifold-inference]]

## Key Concepts

- [[multiscale-neuromechanical-modeling-framework]]: A computational framework for mapping neural activity to behavioral locomotion using spectral mode representations and Helmholtz-Nambu decompositions.

## Archivist Review

I approved the core framework concept because it provides a reusable, domain-agnostic approach to linking neural signals with physical behavior. I also included the open question regarding automated manifold inference, as it addresses a key limitation in the scaling of such dynamical models. The dataset candidate was rejected as it refers to a standard biological experimental paradigm rather than a novel, reusable benchmarking set.

### Approved Concepts
- Multiscale Neuromechanical Modeling Framework: The framework provides an interpretable bridge between high-dimensional neural time series and mechanical behavioral outcomes, using spectral decomposition to manage complexity.

### Approved Open Questions
- Generalized Neuromechanical Manifold Inference: Removing the need for manual constraint selection is essential for scaling neuromechanical analysis to novel species where the underlying dynamical manifold is not known a priori.

### Rejected Candidates
- [dataset] Caenorhabditis elegans locomotion dataset (`caenorhabditis-elegans-locomotion-dataset`) - not_novel: This is a widely used, standard experimental dataset rather than a novel or highly unique benchmark suite requiring a standalone record.

## Links

- [Abstract](https://arxiv.org/abs/2605.03362)
- [PDF](https://arxiv.org/pdf/2605.03362)

