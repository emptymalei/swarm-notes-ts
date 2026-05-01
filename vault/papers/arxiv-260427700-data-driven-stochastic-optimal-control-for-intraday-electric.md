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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-01T05:22:54Z"
created_at: "2026-05-01T05:22:54Z"
---

# Data-Driven Stochastic Optimal Control for Intraday Electricity Trading by Renewable Producers

**Authors**: Chiheb Ben Hammouda, Michael Samet, Raúl Tempone
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27700](https://arxiv.org/abs/2604.27700)

## Summary

This paper presents a data-driven stochastic optimal control framework for intraday electricity trading, specifically designed to address the challenges posed by high volatility in renewable generation. By modeling production with Jacobi diffusion and electricity prices with asymmetric jump-diffusion, the framework captures realistic market behaviors and heavy-tailed price dynamics. The authors solve the associated Hamilton-Jacobi-Bellman equation using a novel monotone IMEX finite-difference method, demonstrating superior performance over standard TWAP benchmarks in numerical experiments.

## Key Contributions

- Develops a continuous-time stochastic optimal control framework for intraday electricity trading using Jacobi diffusion for production and jump-diffusion for prices.
- Handles path-dependent imbalance costs in a Markovian framework through state augmentation for intraday market constraints like gate closure.
- Introduces a monotone IMEX finite-difference scheme with operator splitting and semi-implicit linearization to solve the resulting HJB partial integro-differential equation.

## Links

- [Abstract](https://arxiv.org/abs/2604.27700)
- [PDF](https://arxiv.org/pdf/2604.27700)

