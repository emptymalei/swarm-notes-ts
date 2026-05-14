---
# CSL-compatible fields
title: "Stochastic modeling of Fourier modes in two-dimensional turbulence via filtered white noise"
author:
  - literal: "Paolo Cifani"
  - literal: "Franco Flandoli"
  - literal: "Andrea Zanoni"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13671"

# Custom fields
paper_id: "2605.13671"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-gaussian-chain-graph-models"
  - "data-driven-oscillator-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:23:19Z"
created_at: "2026-05-14T05:23:19Z"
---

# Stochastic modeling of Fourier modes in two-dimensional turbulence via filtered white noise

**Authors**: Paolo Cifani, Franco Flandoli, Andrea Zanoni
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13671](https://arxiv.org/abs/2605.13671)

## Summary

This paper addresses the stochastic modeling of Fourier modes in 2D turbulence, a common practice for simplifying turbulent flow analysis. The authors characterize the temporal correlation structure of these Fourier components under intermediate-scale forcing and formulate a stochastic model using filtered white noise to replicate these dynamics. Finally, they validate the model's performance by comparing its predicted effective diffusion for passive tracer transport against benchmark results from direct numerical simulations.

## Key Contributions

- Identified statistical structures and characteristic time correlation lengths in the Fourier time series of 2D turbulent flows forced at intermediate scales.
- Proposed a stochastic model for Fourier components based on filtered white noise, capturing the observed temporal correlation properties.
- Demonstrated the model's validity by comparing passive tracer transport dynamics against direct numerical simulation (DNS) results.

## Open Questions & Future Work

- [[long-memory-effects-in-2d-turbulence]]

## Archivist Review

The paper provides a localized application of stochastic modeling for Fourier modes in turbulence. While the physical findings are valuable, the proposed modeling approach is a specific application of existing filtered white noise techniques and does not constitute a sufficiently general or novel conceptual framework to warrant a standalone vault entry. The open question regarding long-memory effects in turbulence is, however, technically substantial and distinct from existing entries.

### Approved Open Questions
- Long-memory effects in 2D turbulence: Understanding long-memory effects is crucial for developing accurate stochastic models of turbulence, as current models based on short-memory processes (like filtered white noise) may fail if long-range correlations are present.

### Rejected Candidates
- [concept] Stochastic modeling of Fourier modes (`stochastic-modeling-of-fourier-modes`) - not_novel: This is a descriptive application rather than a distinct, reusable methodology distinct from existing time-series modeling approaches.

## Links

- [Abstract](https://arxiv.org/abs/2605.13671)
- [PDF](https://arxiv.org/pdf/2605.13671)

