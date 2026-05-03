---
# CSL-compatible fields
title: "Data-Driven Stochastic Optimal Control for Intraday Electricity Trading by Renewable Producers"
author:
  - literal: "Chiheb Ben Hammouda"
  - literal: "Michael Samet"
  - literal: "Raúl Tempone"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27700"

# Custom fields
paper_id: "2604.27700"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-03T05:14:53Z"
created_at: "2026-05-03T05:14:53Z"
---

# Data-Driven Stochastic Optimal Control for Intraday Electricity Trading by Renewable Producers

**Authors**: Chiheb Ben Hammouda, Michael Samet, Raúl Tempone
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27700](https://arxiv.org/abs/2604.27700)

## Summary

This paper introduces a data-driven stochastic optimal control framework for intraday electricity trading by renewable producers facing price volatility and imbalance penalties. By modeling production with Jacobi diffusion and prices with asymmetric jump-diffusion, the authors account for market-specific dynamics like gate closure and path-dependent settlement costs. The framework is solved efficiently via a novel monotone IMEX finite-difference scheme applied to a system of Kolmogorov and Hamilton-Jacobi-Bellman equations. Numerical experiments on German market data demonstrate that the proposed strategy significantly improves performance over standard TWAP benchmarks.

## Key Contributions

- Developed a continuous-time stochastic optimal control framework for renewable electricity intraday trading using Jacobi diffusion for production and asymmetric jump-diffusion for prices.
- Formulated the intraday imbalance settlement problem using state augmentation to preserve Markovian structure, enabling characterization of the value function through a three-stage PDE system.
- Introduced a monotone IMEX finite-difference scheme with operator splitting and semi-implicit linearization to solve the resulting Hamilton-Jacobi-Bellman equation efficiently.

## Links

- [Abstract](https://arxiv.org/abs/2604.27700)
- [PDF](https://arxiv.org/pdf/2604.27700)

