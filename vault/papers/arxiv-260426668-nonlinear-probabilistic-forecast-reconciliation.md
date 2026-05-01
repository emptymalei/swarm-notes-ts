---
# CSL-compatible fields
title: "Nonlinear Probabilistic Forecast Reconciliation"
author:
  - literal: "Anubhab Biswas"
  - literal: "Lorenzo Zambon"
  - literal: "Lorenzo Nespoli"
  - literal: "Giorgio Corani"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26668"

# Custom fields
paper_id: "2604.26668"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "nonlinear-probabilistic-forecast-reconciliation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:24:52Z"
created_at: "2026-05-01T05:24:52Z"
---

# Nonlinear Probabilistic Forecast Reconciliation

**Authors**: Anubhab Biswas, Lorenzo Zambon, Lorenzo Nespoli, Giorgio Corani
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26668](https://arxiv.org/abs/2604.26668)

## Summary

This paper addresses the gap in probabilistic forecast reconciliation by introducing methodologies for handling nonlinear constraints. The authors extend both projection and conditioning techniques to ensure reconciled forecasts satisfy non-linear coherence requirements. Empirical evaluations demonstrate that both approaches enhance forecast accuracy, with the proposed UKF-based conditioning method offering a significant advantage in both performance and computational efficiency.

## Key Contributions

- Introduces the first comprehensive framework for probabilistic forecast reconciliation subject to nonlinear constraints.
- Extends projection-based reconciliation by mapping samples directly onto nonlinear coherent manifolds.
- Develops a conditioning-based reconciliation method utilizing an Unscented Kalman Filter (UKF) sampler, achieving superior accuracy and speed compared to projection methods.

## Open Questions & Future Work

- [[non-gaussian-nonlinear-reconciliation]]
- [[geodesic-evaluation-nonlinear-reconciliation]]

## Key Concepts

- [[nonlinear-probabilistic-forecast-reconciliation]]: A framework for adjusting independently generated probabilistic forecasts to satisfy nonlinear coherence constraints via projection or UKF-inspired conditioning.

## Archivist Review

I have approved the concept of 'Nonlinear Probabilistic Forecast Reconciliation' as it introduces a critical methodological advancement in time-series forecasting. I also approved two open questions that specifically highlight theoretical limitations in distribution assumptions (Non-Gaussianity) and evaluation geometry (Geodesic metrics), which are substantial bottlenecks in the field. No datasets were approved as none were central to the paper's primary methodological contribution.

### Approved Concepts
- Nonlinear Probabilistic Forecast Reconciliation: This provides the fundamental framework for moving beyond linear constraints in hierarchical forecasting, a common requirement in physical and industrial time-series systems.

### Approved Open Questions
- Non-Gaussian Nonlinear Reconciliation Methods: Many real-world time series, such as those representing counts or intermittent data, do not follow Gaussian distributions, limiting the applicability of the currently proposed UKF-based reconciliation methods.
- Geodesic-based Evaluation for Reconciliation: Existing metrics are scale-dependent or Euclidean-based, which may not correctly capture the performance of models constrained by nonlinear relationships, potentially leading to inaccurate model assessment.

## Links

- [Abstract](https://arxiv.org/abs/2604.26668)
- [PDF](https://arxiv.org/pdf/2604.26668)

