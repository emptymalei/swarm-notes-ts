---
# CSL-compatible fields
title: "Information bottleneck for learning the phase space of dynamics from high-dimensional experimental data"
author:
  - literal: "K. Michael Martini"
  - literal: "Eslam Abdelaleem"
  - literal: "Paarth Gulati"
  - literal: "Ilya Nemenman"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24662"

# Custom fields
paper_id: "2604.24662"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dysib"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:12:59Z"
created_at: "2026-04-29T05:12:59Z"
---

# Information bottleneck for learning the phase space of dynamics from high-dimensional experimental data

**Authors**: K. Michael Martini, Eslam Abdelaleem, Paarth Gulati, Ilya Nemenman
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24662](https://arxiv.org/abs/2604.24662)

## Summary

The paper introduces DySIB (Dynamical Symmetric Information Bottleneck), an unsupervised framework for learning low-dimensional representations of dynamical systems from high-dimensional observations. By maximizing the predictive mutual information between past and future windows while penalizing latent representation complexity, DySIB avoids the need for explicit reconstruction of high-dimensional raw data. The method is validated on experimental video data of a physical pendulum, where it successfully reconstructs the underlying phase space geometry and physical state variables.

## Key Contributions

- Introduces DySIB (Dynamical Symmetric Information Bottleneck) to extract low-dimensional dynamical state variables from high-dimensional time-series data.
- Demonstrates that maximizing predictive mutual information in latent space, without raw data reconstruction, effectively recovers underlying physical phase space topology and geometry.
- Validates the method on a physical pendulum video dataset, showing learned coordinates recover canonical angle and angular velocity.

## Open Questions & Future Work

- [[canonical-latent-representation-form]]

## Key Concepts

- [[dysib]]: A dynamical symmetric information bottleneck method for unsupervised learning of low-dimensional state variables from high-dimensional time-series data.

## Archivist Review

The paper introduces an elegant information-theoretic approach to dynamics discovery. I approved the proposed DySIB method and the question of canonicalizing latent representations, as these address fundamental bottlenecks in unsupervised representation learning for physical systems. I maintained high standards by rejecting dataset candidates, as no specific experimental dataset was described as a standard, reusable benchmark resource.

### Approved Concepts
- DySIB: It provides an information-theoretic framework for latent-space dynamics discovery that bypasses the computational and noise-related burdens of raw data reconstruction.

### Approved Open Questions
- Canonicalizing Learned Latent Representations: Without a canonical representation, aggregating or comparing latent spaces across different training runs or architectures is fundamentally ambiguous, limiting the reproducibility and scientific utility of latent-space models.

## Links

- [Abstract](https://arxiv.org/abs/2604.24662)
- [PDF](https://arxiv.org/pdf/2604.24662)

