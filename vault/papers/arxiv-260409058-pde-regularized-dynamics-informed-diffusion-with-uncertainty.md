---
# CSL-compatible fields
title: "PDE-regularized Dynamics-informed Diffusion with Uncertainty-aware Filtering for Long-Horizon Dynamics"
author:
  - literal: "Min Young Baeg"
  - literal: "Yoon-Yeong Kim"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.09058"

# Custom fields
paper_id: "2604.09058"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "pdyffusion"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-13T05:09:54Z"
created_at: "2026-04-13T05:09:54Z"
---

# PDE-regularized Dynamics-informed Diffusion with Uncertainty-aware Filtering for Long-Horizon Dynamics

**Authors**: Min Young Baeg, Yoon-Yeong Kim
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.09058](https://arxiv.org/abs/2604.09058)

## Summary

Long-horizon spatiotemporal forecasting suffers from error accumulation and physical inconsistency in standard diffusion models. PDYffusion addresses these issues by combining a PDE-regularized interpolator, which ensures physically consistent intermediate states, with a UKF-based forecaster to manage uncertainty and mitigate error accumulation. Theoretical analysis guarantees PDE-constrained smoothness and model convergence. Empirical results show that PDYffusion achieves improved predictive accuracy and stable uncertainty quantification on complex dynamical systems.

## Key Contributions

- Introduced PDYffusion, a framework integrating PDE-regularized interpolation and UKF-based forecasting for stable long-horizon spatiotemporal prediction.
- Developed a PDE-regularized interpolator that enforces physical consistency in intermediate states through explicit differential operators.
- Demonstrated superior performance in CRPS, MSE, and stable uncertainty behavior (SSR) compared to conventional diffusion-based forecasting methods across dynamical datasets.

## Open Questions & Future Work

- [[extending-pde-diffusion-to-spde-dynamics]]

## Key Concepts

- [[pdyffusion]]: A dynamics-informed diffusion framework that integrates PDE-based regularization and uncertainty-aware filtering for stable long-horizon spatiotemporal prediction.

## Archivist Review

The paper introduces an architectural hybrid (PDYffusion) that combines three distinct paradigms (PDE, Diffusion, and Kalman filtering) to address the specific challenge of error accumulation in long-horizon spatiotemporal forecasting. I approved the framework as a concept due to its clear design pattern of integrating physical constraints with generative models. I approved one open question regarding the transition from deterministic to stochastic PDE regimes, as this is a fundamental theoretical barrier for the field. Other proposed concepts were rejected as subcomponents of the primary architecture.

### Approved Concepts
- PDYffusion: It proposes a novel hybrid architecture merging PDE-based physical constraints with diffusion-based generative models and Kalman filtering for spatiotemporal dynamics.

### Approved Open Questions
- Extending PDE-Diffusion to SPDEs: Many real-world dynamical systems are inherently stochastic; bridging the gap between deterministic PDE-constrained models and stochastic spatiotemporal evolution is essential for robust forecasting.

### Rejected Candidates
- [concept] PDE-regularized interpolator (`pde-regularized-interpolator`) - subcomponent_of_broader_mechanism: This is a submodule of the overarching PDYffusion framework.
- [concept] UKF-based forecaster (`ukf-based-forecaster`) - subcomponent_of_broader_mechanism: This is a specific application of a standard statistical method within the proposed architecture.

## Links

- [Abstract](https://arxiv.org/abs/2604.09058)
- [PDF](https://arxiv.org/pdf/2604.09058)

