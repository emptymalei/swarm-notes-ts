---
# CSL-compatible fields
title: "Geometric structure of ideal data-driven dynamical model using RfR method"
author:
  - literal: "Natsuki Tsutsumi"
  - literal: "Kengo Nakai"
  - literal: "Yoshitaka Saiki"
issued:
  date-parts:
    - [2026, 4, 12]
url: "https://arxiv.org/abs/2604.10550"

# Custom fields
paper_id: "2604.10550"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "gaussian-radial-function-based-regression-rfr"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:05:22Z"
created_at: "2026-04-14T05:05:22Z"
---

# Geometric structure of ideal data-driven dynamical model using RfR method

**Authors**: Natsuki Tsutsumi, Kengo Nakai, Yoshitaka Saiki
**Date**: 2026-04-12
**Paper ID**: [arxiv:2604.10550](https://arxiv.org/abs/2604.10550)

## Summary

This paper investigates the geometric limitations of data-driven models constructed using the Gaussian radial function-based Regression (RfR) method. While these models can approximate chaotic trajectories, they often fail to recover the system's negative Lyapunov exponents, which are essential for characterizing the attractor's geometry. By comparing 'ideal' models against non-ideal ones, the authors analyze Lyapunov vectors and propose a method for constructing models that faithfully reconstruct the original system's dynamical structure.

## Key Contributions

- Identifies that typical data-driven models struggle to reconstruct the negative Lyapunov exponents of chaotic dynamical systems despite tracking trajectories.
- Demonstrates that an 'ideal' model must reconstruct the system's geometric structure, including negative Lyapunov exponents, to correctly represent the underlying chaotic attractor.
- Proposes a diagnostic framework based on Lyapunov exponents and vectors to evaluate and construct 'ideal' data-driven models that remain robust to hyperparameter changes.

## Open Questions & Future Work

- [[scaling-ideal-chaotic-dynamical-models]]

## Key Concepts

- [[gaussian-radial-function-based-regression-rfr]]: A data-driven modeling technique for dynamical systems identification that uses delay-coordinate embeddings and Gaussian radial basis functions to construct state-space representations.

## Archivist Review

I approved the Gaussian Radial Function-based Regression (RfR) concept as it represents a specific, identifiable methodology for dynamical systems modeling distinct from standard black-box forecasting. I also approved the open question regarding the scaling of 'ideal' chaotic models, as it targets the fundamental trade-off between trajectory approximation and the preservation of long-term geometric properties like negative Lyapunov exponents. The rejected candidate from the original analysis was simply a duplicate of the main concept in a different phrasing.

### Approved Concepts
- Gaussian Radial Function-based Regression (RfR): The paper establishes RfR as a framework for testing whether data-driven models capture the true geometric structure (specifically negative Lyapunov exponents) of a chaotic attractor, rather than just matching trajectory data.

### Approved Open Questions
- Scaling Ideal Chaotic Models: This identifies a structural limitation where trajectory-level accuracy is insufficient to guarantee dynamical fidelity, a key issue for physical-system modeling.

## Links

- [Abstract](https://arxiv.org/abs/2604.10550)
- [PDF](https://arxiv.org/pdf/2604.10550)

