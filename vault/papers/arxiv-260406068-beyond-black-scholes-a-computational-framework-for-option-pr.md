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
processed_at: "2026-04-09T04:57:04Z"
created_at: "2026-04-09T04:57:04Z"
---

# Beyond Black-Scholes: A Computational Framework for Option Pricing Using Heston, GARCH, and Jump Diffusion Models

**Authors**: Karmanpartap Singh Sidhu, Pranshi Saxena
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.06068](https://arxiv.org/abs/2604.06068)

## Summary

This paper presents a computational framework for option pricing that moves beyond the limitations of the standard Black-Scholes model by integrating GARCH, Heston, and Merton jump-diffusion models. Using Monte Carlo simulations, the authors incorporate time-varying volatility and sudden price discontinuities to achieve more accurate pricing estimates. Empirical evaluation on live market data reveals that while the Heston model is generally more precise, the Merton model excels in scenarios involving high volatility and sudden market shocks.

## Key Contributions

- Develops a computational framework utilizing Monte Carlo simulations to integrate GARCH, Heston, and Merton Jump-Diffusion models for option pricing.
- Demonstrates that the Heston model provides superior accuracy in aligning with market prices compared to traditional Black-Scholes.
- Identifies that the Merton Jump-Diffusion model is better suited for capturing sudden price discontinuities in volatile assets.

## Open Questions & Future Work

- [[advanced-computational-paradigms-for-option-pricing]]

## Archivist Review

I reviewed the submission and found no concepts worth adding, as the paper primarily evaluates existing well-known financial models (Heston, GARCH, Merton) rather than proposing a new, reusable methodological innovation. The candidate open question was rejected because it proposed a loose collection of buzzword-driven future work (neural networks and quantum walks) rather than a specific, tractable research bottleneck. No datasets were provided for consideration.

### Approved Open Questions
- Advanced Computational Paradigms for Pricing: The paper explicitly identifies these as necessary next-generation approaches to overcome the limitations of classical stochastic pricing models like Heston and Merton.

### Rejected Candidates
- [open_question] Advanced Computational Paradigms for Pricing (`advanced-computational-paradigms-for-option-pricing`) - other: The request was too vague and speculative, listing multiple disparate technologies rather than a specific unresolved research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.06068)
- [PDF](https://arxiv.org/pdf/2604.06068)

