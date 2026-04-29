---
# CSL-compatible fields
title: "A Continuous-Time Ensemble Kalman-Bucy Smoother for Causal Inference and Model Discovery"
author:
  - literal: "Zhang Jiang"
  - literal: "Marios Andreou"
  - literal: "Sebastian Reich"
  - literal: "Nan Chen"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25157"

# Custom fields
paper_id: "2604.25157"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "data-assimilation"
  - "dynamical-systems"
  - "smoothing"
  - "causal-inference"
  - "model-discovery"
architectures:
  []
datasets:
  []
concept_slugs:
  - "ensemble-kalman-bucy-smoother"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:11:43Z"
created_at: "2026-04-29T05:11:43Z"
---

# A Continuous-Time Ensemble Kalman-Bucy Smoother for Causal Inference and Model Discovery

**Authors**: Zhang Jiang, Marios Andreou, Sebastian Reich, Nan Chen
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25157](https://arxiv.org/abs/2604.25157)

## Summary

This paper presents a continuous-time ensemble Kalman-Bucy smoother (EnKBS) for state estimation and parameter recovery in complex, nonlinear dynamical systems. By incorporating both past and future observations, the method improves upon standard filtering techniques, especially during rapid regime transitions. The framework is derivative-free, avoiding the need for tangent-linear or adjoint models, and is shown to be effective for both causal discovery and high-dimensional model parameter identification under partial observation constraints.

## Key Contributions

- Introduces a continuous-time ensemble Kalman-Bucy smoother (EnKBS) for nonlinear dynamical systems, enabling derivative-free state estimation.
- Demonstrates EnKBS effectiveness in Bayesian causal inference and parameter identification for high-dimensional, partially observed systems.
- Shows convergence to the exact smoother solution in the infinite-ensemble limit while maintaining performance with $O(10)$ ensemble sizes.

## Open Questions & Future Work

- [[enkbs-scalability-strongly-nonlinear-systems]]

## Key Concepts

- [[ensemble-kalman-bucy-smoother]]: A derivative-free data assimilation framework for continuous-time state estimation and parameter recovery in nonlinear dynamical systems using ensemble moments.

## Archivist Review

I approved the EnKBS concept as it provides a distinct, derivative-free methodology for continuous-time state estimation that is broadly applicable to scientific forecasting and discovery. The approved open question addresses the critical need to characterize the behavior of this estimator in high-dimensional, strongly nonlinear regimes, which is a fundamental limitation in data assimilation research. Other candidates were rejected for being redundant or overly speculative.

### Approved Concepts
- Ensemble Kalman-Bucy Smoother (EnKBS): Provides a derivative-free framework for continuous-time smoothing that is computationally efficient even with small ensemble sizes.

### Approved Open Questions
- EnKBS Scalability in Nonlinear Systems: Determining the scalability and robustness of EnKBS in strongly nonlinear scenarios is critical for its application to complex, large-scale physical modeling.

### Rejected Candidates
- [open_question] Scaling EnKBS to Highly Nonlinear Systems (`enkbs-scaling-highly-nonlinear-systems`) - duplicate_existing: Duplicate of the approved question; rephrased for conciseness.
- [open_question] Causal Information Flow Mechanisms (`mechanisms-causal-information-flow`) - low_impact: The question is overly broad and lacks the necessary technical grounding to be considered a distinct, trackable research problem at this stage.

## Links

- [Abstract](https://arxiv.org/abs/2604.25157)
- [PDF](https://arxiv.org/pdf/2604.25157)

