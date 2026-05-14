---
# CSL-compatible fields
title: "Yield Curves Dynamics Using Variational Autoencoders Under No-arbitrage"
author:
  - literal: "Fusheng Luo"
  - literal: "H'elyette Geman"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12764"

# Custom fields
paper_id: "2605.12764"
paper_source: "arxiv"
domain: "finance-time-series"
tags:
  - "probabilistic-forecasting"
  - "physics-informed-machine-learning"
  - "generative-modeling"
  - "yield-curve-modeling"
  - "stochastic-differential-equations"
architectures:
  []
datasets:
  []
concept_slugs:
  - "cvaest-ls"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:25:47Z"
created_at: "2026-05-14T05:25:47Z"
---

# Yield Curves Dynamics Using Variational Autoencoders Under No-arbitrage

**Authors**: Fusheng Luo, H'elyette Geman
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12764](https://arxiv.org/abs/2605.12764)

## Summary

This paper addresses the conflict between statistical flexibility and no-arbitrage constraints in term structure modeling by proposing a physics-informed two-stage generative framework. The model utilizes a Student-t CVAE with dynamic level injection (CVAEsT+LS) to capture robust manifold dynamics, which are subsequently evolved via a Neural SDE constrained by no-arbitrage PDE penalties. Evaluated on sovereign currency yield curves, the method significantly reduces forecasting errors and eliminates arbitrage violations, such as parallel drift, common in traditional models.

## Key Contributions

- Introduces a two-stage CVAEsT+LS architecture that decouples macroeconomic shape dynamics from absolute base rates.
- Integrates a continuous-time Neural SDE with a No-Arbitrage PDE penalty to ensure theoretical consistency in yield curve forecasting.
- Achieves 6.58 bps Mean Tenor RMSE across USD, GBP, and JPY currencies, outperforming classical HJM models in extreme environments.

## Open Questions & Future Work

- [[macroeconomic-covariate-integration-sde]]

## Key Concepts

- [[cvaest-ls]]: A heavy-tailed CVAE variant with dynamic level injection for decoupling term structure shapes from base rate volatility.

## Archivist Review

The paper proposes a novel way to combine physics-informed constraints (No-Arbitrage PDE) with deep generative models (CVAEsT+LS) for yield curve dynamics. The concept CVAEsT+LS captures a reusable pattern for decoupling level and shape dynamics in financial manifold learning, while the open question regarding covariate integration highlights a fundamental challenge in bridging statistical SDEs with structural economic factors. I rejected the benchmarking proposal as it focuses on model comparison rather than addressing a latent scientific bottleneck.

### Approved Concepts
- CVAEsT+LS: Central architectural component for separating shape dynamics from base rate levels.

### Approved Open Questions
- Macroeconomic Covariate Integration: This is technically important because it bridges the gap between purely statistical generative models and economic structural models, providing a pathway toward more interpretable and policy-responsive term structure dynamics.

### Rejected Candidates
- [open_question] Benchmarking Generative Finance Frameworks (`benchmarking-generative-finance-frameworks`) - low_impact: This is a generic recommendation for empirical model comparison rather than a fundamental scientific bottleneck in forecasting mechanisms.

## Links

- [Abstract](https://arxiv.org/abs/2605.12764)
- [PDF](https://arxiv.org/pdf/2605.12764)

