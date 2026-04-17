---
# CSL-compatible fields
title: "Doubly Outlier-Robust Online Infinite Hidden Markov Model"
author:
  - literal: "Horace Yiu"
  - literal: "Leandro Sánchez-Betancourt"
  - literal: "Álvaro Cartea"
  - literal: "Gerardo Duran-Martin"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.14322"

# Custom fields
paper_id: "2604.14322"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "br-ihmm"
  - "posterior-influence-function"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:06:47Z"
created_at: "2026-04-17T05:06:47Z"
---

# Doubly Outlier-Robust Online Infinite Hidden Markov Model

**Authors**: Horace Yiu, Leandro Sánchez-Betancourt, Álvaro Cartea, Gerardo Duran-Martin
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.14322](https://arxiv.org/abs/2604.14322)

## Summary

This paper introduces the Batched Robust infinite Hidden Markov Model (BR-iHMM), designed to handle streaming data prone to outliers and model misspecification. By framing robustness through the posterior influence function (PIF), the authors derive update rules that provide theoretical guarantees for bounded influence while managing the inherent trade-off between regime-switching adaptivity and outlier rejection. Empirical evaluations on limit order book, electricity demand, and high-dimensional linear system datasets show significant forecasting improvements over conventional online Bayesian approaches.

## Key Contributions

- Derived the Batched Robust infinite Hidden Markov Model (BR-iHMM) to maintain robustness against streaming outliers and model misspecification.
- Formulated robustness using the posterior influence function (PIF) and established formal conditions for bounded PIF in online iHMMs.
- Demonstrated up to 67% reduction in one-step-ahead forecasting error compared to standard online Bayesian methods across diverse domains.

## Open Questions & Future Work

- [[extend-robustness-general-emissions]]
- [[link-pif-predictive-accuracy]]

## Key Concepts

- [[br-ihmm]]: An online infinite hidden Markov model variant that utilizes batched updates and generalized Bayesian inference to maintain robustness against streaming outliers and model misspecification.
- [[posterior-influence-function]]: A sensitivity metric used in generalized Bayesian inference to measure the impact of infinitesimal perturbations in data on the posterior distribution.

## Archivist Review

I approved the BR-iHMM mechanism and the PIF diagnostic concept as they provide a foundational, theoretical contribution to robust online Bayesian forecasting. The open questions were approved for identifying key limitations in extending these theoretical robustness guarantees to broader model classes and linking these guarantees to empirical forecasting performance. I rejected no candidates because all provided proposals were high-quality and novel within the scope of the field.

### Approved Concepts
- Batched Robust infinite Hidden Markov Model (BR-iHMM): It is a novel approach to managing the trade-off between regime adaptivity and outlier robustness in online Bayesian infinite hidden Markov models, providing explicit theoretical bounds.
- Posterior Influence Function (PIF): PIF provides a formal, quantitative framework to evaluate robustness in Bayesian models, moving beyond empirical testing to theoretical guarantees of stability.

### Approved Open Questions
- Generalizing robustness to non-LG models: Broadening the robustness guarantees to a wider class of emission models is necessary to make the doubly-robust framework applicable to non-Gaussian or non-linear time series problems.
- Connecting PIF to predictive accuracy: Establishing this relationship would provide a principled way to evaluate the effectiveness of robustness mechanisms and directly connect theoretical guarantees to practical forecasting utility.

## Links

- [Abstract](https://arxiv.org/abs/2604.14322)
- [PDF](https://arxiv.org/pdf/2604.14322)

