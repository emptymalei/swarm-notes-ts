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
  - "stochastic-control"
  - "finance"
  - "time-series-forecasting"
  - "renewable-energy"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-02T05:08:07Z"
created_at: "2026-05-02T05:08:07Z"
---

# Data-Driven Stochastic Optimal Control for Intraday Electricity Trading by Renewable Producers

**Authors**: Chiheb Ben Hammouda, Michael Samet, Raúl Tempone
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27700](https://arxiv.org/abs/2604.27700)

## Summary

This paper introduces a continuous-time stochastic optimal control framework designed for intraday electricity trading by renewable producers. By modeling production using Jacobi diffusion and prices via asymmetric jump-diffusion, the authors account for both physical generation constraints and market price volatility. The framework incorporates path-dependent imbalance costs through state augmentation and solves the resulting HJB equation using a novel, efficient monotone IMEX finite-difference scheme. Numerical results demonstrate that this strategy effectively bridges the performance gap between simple benchmarks and theoretical perfect-foresight models.

## Key Contributions

- Develops a continuous-time stochastic optimal control framework for intraday electricity trading that models production via Jacobi diffusion and prices via asymmetric jump-diffusion.
- Handles complex market constraints such as gate closures and path-dependent imbalance costs through state augmentation to preserve the Markovian structure.
- Derives a three-stage solution consisting of two linear Kolmogorov backward equations and one nonlinear Hamilton-Jacobi-Bellman partial integro-differential equation.
- Introduces a monotone IMEX finite-difference scheme with operator splitting and semi-implicit linearization to solve the resulting high-dimensional control problem efficiently.

## Links

- [Abstract](https://arxiv.org/abs/2604.27700)
- [PDF](https://arxiv.org/pdf/2604.27700)

