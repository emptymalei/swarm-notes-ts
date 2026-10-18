---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Stochastic Gradient Descent: A Nonlinear Time Series Perspective"
description: "This paper analyzes the statistical properties of constant-step-size Stochastic Gradient Descent (SGD) through the lens of nonlinear time series and iterated random functions. By establishing Geometric Moment Contraction (GMC), the authors prove convergence in Euclidean distance, allowing for a more granular asymptotic analysis than traditional probability measure approaches. They derive quenched central limit theorems and invariance principles for averaged SGD and introduce a Richardson-Romberg extrapolation technique using multiple step sizes to minimize bias. Finally, they present an online inference method for the resulting extrapolated estimates, demonstrating its efficacy via empirical confidence intervals."
resource: "https://arxiv.org/abs/2610.20894"
tags:
  - "time-series-analysis"
  - "stochastic-processes"
  - "stochastic-optimization"
  - "statistics"
  - "convergence"
  - "asymptotic-analysis"
timestamp: "2026-10-18T00:28:56Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jiaqi Li"
  - literal: "Zhipeng Lou"
  - literal: "Stefan Richter"
  - literal: "Wei Biao Wu"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20894"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "geometric-moment-contraction-sgd"
    description: "A property from nonlinear time series theory used to prove that SGD iterates converge geometrically in Euclidean distance toward a stationary distribution."
  - name: "richardson-romberg-extrapolation-asgd"
    description: "A bias-reduction technique that cancels out the leading-order bias in ASGD by linearly combining estimates obtained from multiple different constant step sizes."
datasets:
  []
open_questions:
  - name: "gmc-for-adaptive-optimizers"
    description: "Can the GMC framework be extended to analyze adaptive gradient methods (e.g., Adam, RMSProp) where the step size is not only non-constant but also depends on the historical trajectory of the gradients?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:28:56Z"
created_at: "2026-10-18T00:28:56Z"
---

# Stochastic Gradient Descent: A Nonlinear Time Series Perspective

**Authors**: Jiaqi Li, Zhipeng Lou, Stefan Richter, Wei Biao Wu
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20894](https://arxiv.org/abs/2610.20894)

## Summary

This paper analyzes the statistical properties of constant-step-size Stochastic Gradient Descent (SGD) through the lens of nonlinear time series and iterated random functions. By establishing Geometric Moment Contraction (GMC), the authors prove convergence in Euclidean distance, allowing for a more granular asymptotic analysis than traditional probability measure approaches. They derive quenched central limit theorems and invariance principles for averaged SGD and introduce a Richardson-Romberg extrapolation technique using multiple step sizes to minimize bias. Finally, they present an online inference method for the resulting extrapolated estimates, demonstrating its efficacy via empirical confidence intervals.

## Key Contributions

- Established Geometric Moment Contraction (GMC) for constant-step-size SGD, ensuring convergence in Euclidean distance and addressing initialization-induced non-stationarity.
- Proved quenched central limit theorems (CLT), invariance principles, and α-stable convergence for averaged SGD (ASGD) regardless of the starting point.
- Introduced a Richardson-Romberg extrapolation framework using multiple step sizes to significantly reduce bias in ASGD estimates.
- Proposed a new online inference method and bias-reduced variant for extrapolated ASGD, enabling the construction of valid empirical confidence intervals.

## Limitations

The analysis focuses on constant step sizes; extending these results to more complex adaptive step size regimes (like Adam) remains a challenge.

## Open Questions & Future Work

- [[gmc-for-adaptive-optimizers]]

## Key Concepts

- [[geometric-moment-contraction-sgd]]: A property from nonlinear time series theory used to prove that SGD iterates converge geometrically in Euclidean distance toward a stationary distribution.
- [[richardson-romberg-extrapolation-asgd]]: A bias-reduction technique that cancels out the leading-order bias in ASGD by linearly combining estimates obtained from multiple different constant step sizes.

## Archivist Review

The approved candidates focus on the paper's core innovation: treating the SGD process as a nonlinear time series. 'Geometric Moment Contraction for SGD' is approved as the primary theoretical mechanism for establishing Euclidean convergence. 'Richardson-Romberg Extrapolation for ASGD' is approved as a reusable algorithmic technique for bias reduction in stochastic optimization. The open question identifies a critical research gap in applying these rigorous time-series tools to the adaptive optimizers prevalent in modern machine learning.

### Approved Concepts
- Geometric Moment Contraction for SGD: It shifts the analysis of SGD convergence from probability measures (like Wasserstein distance) to Euclidean distance, which is necessary for proving stronger asymptotic results like quenched central limit theorems.
- Richardson-Romberg Extrapolation for ASGD: It addresses the inherent bias in constant-step-size Averaged SGD (ASGD) without requiring a decaying step size, which often slows down convergence.

### Approved Open Questions
- Extension of GMC to Adaptive Optimizers: Bridging the theoretical gap between constant-step-size SGD and popular adaptive optimizers would provide a more rigorous foundation for deep learning optimization.

## Links

- [Abstract](https://arxiv.org/abs/2610.20894)
- [PDF](https://arxiv.org/pdf/2610.20894)

