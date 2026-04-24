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
  - "foundation-models"
  - "dynamical-systems"
  - "physics-informed-machine-learning"
  - "autoregressive-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "shooting-based-mixed-finite-element-neural-integration"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:08:47Z"
created_at: "2026-04-24T05:08:47Z"
---

# A Hybridizable Neural Time Integrator for Stable Autoregressive Forecasting

**Authors**: Brooks Kinch, Xiaozhe Hu, Yilong Huang, Martine Dyring Hansen, Sunniva Meltzer, Nathaniel Donald Hamlin, David Sirajuddin, Eric C. Cyr, Nathaniel Trask
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.21101](https://arxiv.org/abs/2604.21101)

## Summary

This paper presents a hybrid neural integration technique that embeds autoregressive transformers within a shooting-based mixed finite element scheme to address stability issues in long-horizon forecasting. By enforcing topological structure through this integration, the model gains provable energy preservation and uniform gradient bounds, effectively mitigating exploding gradient problems. The framework demonstrates significant efficiency and performance gains, including substantial parameter reduction and massive acceleration of complex physics simulations.

## Key Contributions

- Introduces a shooting-based mixed finite element integration scheme for autoregressive transformers, ensuring provable energy preservation and uniform gradient bounds.
- Achieves superior long-horizon forecasting performance on chaotic systems with a 65x reduction in model parameter count compared to current foundation models.
- Demonstrates the creation of a 'mini-foundation' surrogate for fusion simulation, achieving a 9,000x speedup with only 12 training simulations.

## Open Questions & Future Work

- [[stability-structure-transformer-forecasting]]

## Key Concepts

- [[shooting-based-mixed-finite-element-neural-integration]]: A hybrid integration scheme that embeds neural autoregressive models within a mixed finite element framework to ensure provable energy preservation and gradient stability.

## Archivist Review

The approved concept captures a novel architectural approach to stability in dynamical system forecasting. The approved open question addresses the fundamental tension between the expressivity of deep learning models and the rigors of numerical analysis, which is central to current research in scientific machine learning. Both items are well-supported by the paper and demonstrate high potential for reusability across future scientific forecasting research.

### Approved Concepts
- Shooting-based Mixed Finite Element Neural Integration: It provides the theoretical foundation for stability and gradient control in neural forecasting models for dynamical systems by embedding transformers into a structure-preserving numerical framework.

### Approved Open Questions
- Stability in Transformer-Based Forecasting: The lack of mathematical grounding for transformer stability poses a significant barrier to their reliable application in high-stakes scientific simulation, where catastrophic failures during rollout are unacceptable.

## Links

- [Abstract](https://arxiv.org/abs/2604.21101)
- [PDF](https://arxiv.org/pdf/2604.21101)

