---
# CSL-compatible fields
title: "Conformal Prediction with Time-Series Data via Sequential Conformalized Density Regions"
author:
  - literal: "M. Sampson"
  - literal: "K. S. Chan"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07325"

# Custom fields
paper_id: "2604.07325"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "conformal-prediction"
  - "uncertainty-quantification"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sequential-conformalized-density-regions-scdr"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:30:55Z"
created_at: "2026-04-10T15:30:55Z"
---

# Conformal Prediction with Time-Series Data via Sequential Conformalized Density Regions

**Authors**: M. Sampson, K. S. Chan
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07325](https://arxiv.org/abs/2604.07325)

## Summary

The authors introduce Sequential Conformalized Density Regions (SCDR), a novel conformal prediction framework designed to provide guaranteed asymptotic conditional coverage for non-exchangeable time-series data. Unlike standard approaches that produce single intervals, SCDR can generate disconnected prediction regions, allowing it to capture complex predictive structures like bifurcations. The method exhibits double robustness, maintaining coverage guarantees under misspecification of either the density model or the autoregressive score dynamics, and outperforms existing methods in empirical coverage and set informativeness.

## Key Contributions

- Introduced Sequential Conformalized Density Regions (SCDR), a conformal prediction method that guarantees asymptotic conditional coverage for non-exchangeable time-series data.
- Demonstrated the flexibility of SCDR to generate disconnected prediction intervals, effectively capturing bifurcations in predictive distributions.
- Proved double robustness of SCDR, ensuring validity if either the predictive density model is correct or the score follows a correctly specified nonlinear autoregressive model.

## Open Questions & Future Work

- [[joint-multi-step-conformal-prediction-coverage]]

## Key Concepts

- [[sequential-conformalized-density-regions-scdr]]: A time-series conformal prediction method that generates disconnected prediction sets for multimodal uncertainty quantification.

## Archivist Review

I approved SCDR as it introduces a distinct mechanism for conformal inference in time-series that explicitly handles non-exchangeability and multimodality. I also approved the open question regarding joint multi-step coverage as it represents a significant, non-trivial extension to the standard conformal prediction framework that future research will need to address. Other candidates were rejected as they concerned implementation-level choices or broad extensions better addressed by future development cycles.

### Approved Concepts
- Sequential Conformalized Density Regions (SCDR): Provides a framework for handling non-exchangeable time-series data and generating disconnected (multimodal) prediction sets.

### Approved Open Questions
- Joint Multi-Step Prediction Coverage: Joint coverage is essential for many practical applications where the entire trajectory or sequence of future states is of interest, rather than only individual time points.

### Rejected Candidates
- [open_question] Multivariate Time-Series Conformal Prediction (`multivariate-time-series-conformal-prediction`) - low_impact: The core challenge of multivariate forecasting is largely covered by existing research in density estimation and uncertainty; this is a broad implementation goal rather than a fundamental bottleneck.
- [open_question] Alternative Conditional Density Estimators (`alternative-conditional-density-estimators`) - subcomponent_of_broader_mechanism: Selecting specific density estimators (like normalizing flows vs. GMMs) is an architectural choice rather than a foundational open research question for conformal inference.

## Links

- [Abstract](https://arxiv.org/abs/2604.07325)
- [PDF](https://arxiv.org/pdf/2604.07325)

