---
# CSL-compatible fields
title: "Dynamic Regret for Online Regression in RKHS via Discounted VAW and Subspace Approximation"
author:
  - literal: "Dmitry B. Rokhlin"
  - literal: "Georgiy A. Karapetyants"
  - literal: "Jacobsen & Cutkosky (2024)"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.25021"

# Custom fields
paper_id: "2604.25021"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "online-learning"
  - "regression"
  - "kernel-methods"
architectures:
  []
datasets:
  []
concept_slugs:
  - "discounted-vovk-azoury-warmuth"
  - "orthogonal-truncation-method"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-29T05:12:20Z"
created_at: "2026-04-29T05:12:20Z"
---

# Dynamic Regret for Online Regression in RKHS via Discounted VAW and Subspace Approximation

**Authors**: Dmitry B. Rokhlin, Georgiy A. Karapetyants, Jacobsen & Cutkosky (2024)
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.25021](https://arxiv.org/abs/2604.25021)

## Summary

This paper presents a framework for online regression in reproducing kernel Hilbert spaces (RKHS) under a dynamic regret criterion. By adapting the finite-dimensional discounted Vovk-Azoury-Warmuth (VAW) method, the authors employ finite-dimensional subspace approximations to manage the complexity of the RKHS. Through orthogonal truncation techniques and diverse kernel-specific expansion strategies, the approach provides rigorous dynamic regret bounds across both fast and slow regimes.

## Key Contributions

- Extends the discounted Vovk-Azoury-Warmuth (VAW) approach to RKHS settings using finite-dimensional subspace approximations.
- Introduces an orthogonal truncation method for constructing finite-dimensional approximation spaces in RKHS based on feature expansions.
- Derives dynamic regret bounds for Gaussian, analytic dot-product, Mercer-truncated, and Matérn kernels.

## Open Questions & Future Work

- [[dynamic-regret-kaar-improvement]]

## Key Concepts

- [[discounted-vovk-azoury-warmuth]]: An ensemble-based online learning approach utilizing a geometric grid of discount factors for dynamic regret minimization.
- [[orthogonal-truncation-method]]: A technique for constructing finite-dimensional approximation spaces in an RKHS by defining an inner product that makes feature expansion functions orthonormal.

## Archivist Review

The paper introduces a systematic framework for extending discounted Vovk-Azoury-Warmuth approaches to infinite-dimensional spaces. I approved the core VAW mechanism and the orthogonal truncation method as they are reusable architectural patterns for online learning in kernel spaces. I also included a high-level theoretical question regarding regret bound convergence between static and dynamic regimes as it represents a key bottleneck in the field.

### Approved Concepts
- Discounted Vovk-Azoury-Warmuth (VAW): It serves as the core algorithmic mechanism for achieving dynamic regret bounds in an infinite-dimensional RKHS setting.
- Orthogonal Truncation Method: This provides a robust, systematic way to reduce infinite-dimensional RKHS problems to finite-dimensional subspaces, enabling the application of standard online learning algorithms.

### Approved Open Questions
- KAAR dynamic regret improvement: Bridging the gap between static and dynamic regret performance in nonparametric settings is a fundamental theoretical challenge in online learning.

## Links

- [Abstract](https://arxiv.org/abs/2604.25021)
- [PDF](https://arxiv.org/pdf/2604.25021)

