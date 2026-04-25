---
# CSL-compatible fields
title: "A Hybridizable Neural Time Integrator for Stable Autoregressive Forecasting"
author:
  - literal: "Brooks Kinch"
  - literal: "Xiaozhe Hu"
  - literal: "Yilong Huang"
  - literal: "Martine Dyring Hansen"
  - literal: "Sunniva Meltzer"
  - literal: "Nathaniel Donald Hamlin"
  - literal: "David Sirajuddin"
  - literal: "Eric C. Cyr"
  - literal: "Nathaniel Trask"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.21101"

# Custom fields
paper_id: "2604.21101"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "dynamical-systems"
  - "stability"
  - "scientific-ml"
architectures:
  []
datasets:
  []
concept_slugs:
  - "shooting-based-mixed-finite-element-neural-integration"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:55:18Z"
created_at: "2026-04-25T04:55:18Z"
---

# A Hybridizable Neural Time Integrator for Stable Autoregressive Forecasting

**Authors**: Brooks Kinch, Xiaozhe Hu, Yilong Huang, Martine Dyring Hansen, Sunniva Meltzer, Nathaniel Donald Hamlin, David Sirajuddin, Eric C. Cyr, Nathaniel Trask
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.21101](https://arxiv.org/abs/2604.21101)

## Summary

This paper addresses the instability issues inherent in autoregressive forecasting of chaotic dynamical systems by introducing a hybrid neural time integrator. By embedding an autoregressive transformer within a shooting-based mixed finite element structure, the method provides theoretical guarantees for both discrete energy conservation and bounded training gradients. Empirical evaluations demonstrate that this approach significantly outperforms existing foundation models in long-horizon forecasting efficiency and data-efficient surrogate modeling.

## Key Contributions

- Introduces a hybrid integration framework that embeds transformer architectures into a shooting-based mixed finite element scheme to guarantee discrete energy preservation and stable gradients.
- Achieves state-of-the-art long-horizon forecasting for chaotic systems while reducing parameter requirements by 65x compared to existing foundation models.
- Demonstrates a 'mini-foundation' model for fusion plasma simulations that enables a 9,000x speedup over traditional particle-in-cell simulations using only 12 training samples.

## Open Questions & Future Work

- [[extrapolating-to-unseen-regimes]]

## Key Concepts

- [[shooting-based-mixed-finite-element-neural-integration]]: A hybrid integration framework that embeds neural autoregressive models into a mixed finite element scheme to enforce stability in chaotic system forecasting.

## Archivist Review

I approved the core architectural concept, as it provides a generalizable framework for embedding deep learning components into numerical integrators to guarantee stability. I also approved the identified limitation regarding extrapolation to unseen regimes, as it captures a critical bottleneck in autoregressive scientific forecasting. I maintained strict scarcity and focused on the primary innovations rather than implementation details.

### Approved Concepts
- Shooting-based Mixed Finite Element Neural Integration: This is the core architectural innovation that enables long-horizon stability and gradient bounding.

### Approved Open Questions
- Extrapolation to Unseen Regimes: This defines the fundamental limit of the current architecture and identifies the transition from autoregressive surrogate modeling to explicit PDE learning as the next necessary step for broader scientific application.

## Links

- [Abstract](https://arxiv.org/abs/2604.21101)
- [PDF](https://arxiv.org/pdf/2604.21101)

