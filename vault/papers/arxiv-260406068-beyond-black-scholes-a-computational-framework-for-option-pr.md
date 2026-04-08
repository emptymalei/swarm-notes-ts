---
# CSL-compatible fields
title: "Beyond Black-Scholes: A Computational Framework for Option Pricing Using Heston, GARCH, and Jump Diffusion Models"
author:
  - literal: "Karmanpartap Singh Sidhu"
  - literal: "Pranshi Saxena"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.06068"

# Custom fields
paper_id: "2604.06068"
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
processed_at: "2026-04-08T04:54:55Z"
created_at: "2026-04-08T04:54:55Z"
---

# Beyond Black-Scholes: A Computational Framework for Option Pricing Using Heston, GARCH, and Jump Diffusion Models

**Authors**: Karmanpartap Singh Sidhu, Pranshi Saxena
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.06068](https://arxiv.org/abs/2604.06068)

## Summary

This paper develops a computational framework for option pricing by moving beyond the Black-Scholes assumption of constant volatility and continuous price paths. By integrating the Heston stochastic volatility model, GARCH, and Merton jump-diffusion, the researchers perform Monte Carlo simulations to improve estimation accuracy. Empirical results using live market data demonstrate that the Heston model excels in capturing volatility clustering and skew, while jump-diffusion models better handle sudden market discontinuities.

## Key Contributions

- Evaluated three advanced option pricing frameworks (Heston, GARCH, and Merton Jump-Diffusion) using Monte Carlo simulation to address Black-Scholes limitations.
- Demonstrated that the Heston model provides the highest accuracy for market-price alignment compared to classical benchmarks.
- Validated the effectiveness of the Merton jump-diffusion model for pricing highly volatile assets characterized by discontinuous price movements.

## Open Questions & Future Work

- [[stochastic-model-parameter-optimization-bottlenecks]]

## Archivist Review

The paper provides a straightforward comparison of classic quantitative finance models (Heston, GARCH, Merton) rather than proposing novel ML methodologies or architectural breakthroughs that require permanent vault entries. I have approved a refined version of the open question regarding parameter optimization, as the integration of dynamic learning with classical stochastic systems is a recurring challenge in time-series finance.

### Approved Open Questions
- Stochastic Model Parameter Optimization: Developing more robust, adaptive, and computationally efficient simulation methods is crucial for precise derivative pricing and risk management in volatile environments where historical-only calibration often fails.

### Rejected Candidates
- [open_question] Advanced Optimization and Quantum Walks for Option Pricing (`next-gen-stochastic-modelling-and-quantum-finance`) - other: The title and content were too broad/aspirational; the slug was renamed to focus on the identified bottleneck of parameter optimization.

## Links

- [Abstract](https://arxiv.org/abs/2604.06068)
- [PDF](https://arxiv.org/pdf/2604.06068)

