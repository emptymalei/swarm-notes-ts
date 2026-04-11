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
  - "time-series"
  - "conformal-prediction"
  - "uncertainty-quantification"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sequential-conformalized-density-regions-scdr"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:47:50Z"
created_at: "2026-04-11T04:47:50Z"
---

# Conformal Prediction with Time-Series Data via Sequential Conformalized Density Regions

**Authors**: M. Sampson, K. S. Chan
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07325](https://arxiv.org/abs/2604.07325)

## Summary

This paper introduces Sequential Conformalized Density Regions (SCDR), a novel conformal prediction method for time-series forecasting that guarantees asymptotic conditional coverage. By leveraging quantile random forest conformal adjustment, SCDR adapts to the non-exchangeable nature of sequential data and provides the flexibility to generate disjoint prediction sets, effectively capturing potential bifurcations. The method demonstrates double robustness and superior performance in terms of empirical coverage and set size compared to existing conformal techniques on standard benchmarks.

## Key Contributions

- Introduced SCDR, which enables the generation of disjoint prediction sets to capture bifurcations in time-series data.
- Demonstrated that SCDR achieves guaranteed asymptotic conditional coverage for non-exchangeable data through quantile random forest adjustment.
- Proved that the method is doubly robust under specified conditions regarding the predictive density model or nonlinear autoregressive score models.

## Open Questions & Future Work

- [[multivariate-multistep-scdr-extension]]

## Key Concepts

- [[sequential-conformalized-density-regions-scdr]]: A conformal prediction framework for time-series that generates both prediction intervals and disjoint prediction sets to account for bifurcations in non-exchangeable data.

## Archivist Review

I approved the SCDR methodology as a novel contribution to time-series uncertainty quantification. I also approved the open question regarding its extension to multivariate and multi-step scenarios, as this is a fundamental scaling bottleneck for conformal prediction in time series. I rejected the open question about density estimators, as it is a routine research direction common to almost all predictive models.

### Approved Concepts
- Sequential Conformalized Density Regions (SCDR): This is the core methodology of the paper, providing a flexible framework for generating disjoint prediction sets in time-series to capture bifurcations.

### Approved Open Questions
- Multivariate and Multi-step SCDR Extension: Reliable multi-step and multivariate uncertainty quantification is critical for complex decision-making and control tasks in time-series analysis where cross-variable dependencies must be modeled.

### Rejected Candidates
- [open_question] Alternative Density Estimators SCDR (`alternative-density-models-scdr`) - weak_evidence: This is a routine request for testing more model architectures (like normalizing flows) rather than a fundamental scientific bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.07325)
- [PDF](https://arxiv.org/pdf/2604.07325)

