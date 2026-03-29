---
# CSL-compatible fields
title: "A Distribution-to-Distribution Neural Probabilistic Forecasting Framework for Dynamical Systems"
author:
  - literal: "Tianlin Yang"
  - literal: "Hailiang Du"
  - literal: "Louis J. M. Aslett"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25370"

# Custom fields
paper_id: "2603.25370"
paper_source: "openalex"
domain: "time-series"
tags:
  - "probabilistic forecasting"
  - "dynamical systems"
  - "uncertainty quantification"
  - "kernel methods"
architectures:
  []
datasets:
  []
concept_slugs:
  - "distribution-to-distribution-forecasting"
  - "kernel-mean-embedding-distribution-encoding"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:15:34Z"
created_at: "2026-03-29T20:15:34Z"
---

# A Distribution-to-Distribution Neural Probabilistic Forecasting Framework for Dynamical Systems

**Authors**: Tianlin Yang, Hailiang Du, Louis J. M. Aslett
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25370](https://arxiv.org/abs/2603.25370)

## Summary

This paper introduces a novel Distribution-to-Distribution (D2D) neural probabilistic forecasting framework designed to evolve predictive probability distributions directly, moving beyond traditional trajectory-based ensemble or sampling methods. The architecture integrates a distributional encoding step using Kernel Mean Embeddings (KME) to represent input distributions, feeding into a replaceable neural forecasting module parameterized by Mixture Density Networks (MDNs) for output distributions. This enables the recursive, end-to-end propagation of uncertainty within a unified network structure, evaluated using probabilistic forecast skill measures. Experiments on the Lorenz63 chaotic system confirm that the D2D model accurately captures nontrivial distributional evolution and yields skillful forecasts competitive with established benchmarks. The work proposes a paradigm shift towards learning and evolving distributions directly in probabilistic forecasting.

## Key Contributions

- Development of a Distribution-to-Distribution (D2D) neural forecasting framework that operates directly on predictive probability distributions rather than ensembles or deterministic trajectories.
- Introduction of a unified end-to-end architecture utilizing kernel mean embeddings for input distribution encoding and Mixture Density Networks (MDNs) for output distribution parameterization.
- Demonstration that the D2D framework can capture the distributional evolution of complex, chaotic systems like Lorenz63 without explicit ensemble simulation.
- Evaluation methodology based directly on probabilistic forecast skill metrics, showing competitive or superior performance against simplified perfect model benchmarks.

## Limitations

The framework's performance is demonstrated specifically on the Lorenz63 chaotic dynamical system, suggesting further validation is needed across a wider variety of systems with known seasonality or complex dependencies.

## Open Questions & Future Work

- [[joint-distribution-parameterization-for-d2d-forecasting]]

## Key Concepts

- [[distribution-to-distribution-forecasting]]: A neural framework that learns to map an input predictive distribution directly to an output predictive distribution for sequential forecasting tasks.
- [[kernel-mean-embedding-distribution-encoding]]: The use of Kernel Mean Embeddings (KME) to non-parametrically encode an input probability distribution into a fixed-dimensional vector space suitable for neural processing.

## Archivist Review

Two core concepts were approved: the overarching Distribution-to-Distribution (D2D) forecasting paradigm and the specific technique, Kernel Mean Embeddings (KME), used for input distribution representation. One substantial open question regarding the generalization to joint distribution forecasting was approved, as this highlights a clear, unresolved technical hurdle for the novel framework. The 'Lorenz63' dataset was rejected as it is a standard benchmark system and not a reusable, central dataset itself.

### Approved Concepts
- Distribution-to-Distribution (D2D) Forecasting Framework: This is the core novel methodology proposed for handling predictive uncertainty in dynamical systems by operating directly on distributions rather than trajectories.
- Kernel Mean Embeddings for Distribution Representation: KME is the specific mechanism chosen to represent the input probability distributions in a way that is differentiable and usable by the neural network.

### Approved Open Questions
- Scalable joint distribution parameterization: The joint distribution captures essential cross-variable dependencies, and a scalable method for its representation would be crucial for applying the D2D framework to complex, multivariate dynamical systems where correlation structure is important for accurate uncertainty propagation.

### Rejected Candidates
- [dataset] Lorenz63 (`lorenz63`) - low_impact: Lorenz63 is an extremely common and well-known test system for chaos theory and dynamical systems forecasting, not a novel or critical named dataset deserving a vault note.

## Links

- [Abstract](https://arxiv.org/abs/2603.25370)
- [PDF](https://arxiv.org/pdf/2603.25370)

