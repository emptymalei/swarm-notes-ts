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
processed_at: "2026-04-28T05:13:22Z"
created_at: "2026-04-28T05:13:22Z"
---

# Information bottleneck for learning the phase space of dynamics from high-dimensional experimental data

**Authors**: K. Michael Martini, Eslam Abdelaleem, Paarth Gulati, Ilya Nemenman
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24662](https://arxiv.org/abs/2604.24662)

## Summary

The paper introduces DySIB, a method that leverages the information bottleneck principle to learn interpretable low-dimensional latent representations of complex dynamical systems from high-dimensional observational data. By maximizing predictive mutual information between past and future time windows, the approach avoids explicit data reconstruction while recovering the underlying phase space geometry. Applied to experimental pendulum video data, DySIB successfully identifies the system's dimensionality and aligns latent coordinates with canonical physical variables like angle and velocity.

## Key Contributions

- Introduces DySIB (Dynamical Symmetric Information Bottleneck) to extract low-dimensional dynamical state variables from high-dimensional time-series data without reconstruction.
- Demonstrates that maximizing predictive mutual information between past and future windows while penalizing representation complexity recovers the true phase space of a physical pendulum.
- Enables self-consistent hyperparameter selection, allowing the method to automatically identify the latent dimensionality and topology of dynamical systems.

## Open Questions & Future Work

- [[canonical-latent-representation-form]]

## Key Concepts

- [[dysib]]: An information-bottleneck-based method for learning interpretable, low-dimensional phase space representations of dynamical systems by maximizing predictive information without reconstructing raw observations.

## Archivist Review

I approved the DySIB method as it offers a distinct, non-reconstructive approach to latent dynamics discovery that likely impacts future physical-science-aware time-series modeling. I also approved the open question regarding canonical latent forms because the ambiguity of latent representations (gauge freedom) is a significant bottleneck for the general evaluation and cross-comparison of latent-space discovery models in physical systems. Other candidates were not proposed in the provided input.

### Approved Concepts
- Dynamical Symmetric Information Bottleneck (DySIB): It provides a reconstruction-free, information-theoretic approach to latent representation learning for physical dynamical systems, which is a significant paradigm shift from standard autoencoder-based approaches.

### Approved Open Questions
- Canonical form for latent representations: This is fundamental for the scalability of latent-space discovery methods, as it would enable validation and cross-comparison of learned physical models without needing external ground-truth supervisory signals.

## Links

- [Abstract](https://arxiv.org/abs/2604.24662)
- [PDF](https://arxiv.org/pdf/2604.24662)

