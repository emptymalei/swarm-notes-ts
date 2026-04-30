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
processed_at: "2026-04-30T05:13:05Z"
created_at: "2026-04-30T05:13:05Z"
---

# Nonlinear Probabilistic Forecast Reconciliation

**Authors**: Anubhab Biswas, Lorenzo Zambon, Lorenzo Nespoli, Giorgio Corani
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26668](https://arxiv.org/abs/2604.26668)

## Summary

This paper introduces the first framework for probabilistic forecast reconciliation in the presence of nonlinear constraints, addressing a critical limitation in hierarchical and grouped time-series forecasting. The authors propose two main methods: a projection-based approach that maps samples onto a nonlinear manifold, and a sampling-based approach utilizing an Unscented Kalman Filter (UKF) for efficient conditioning. Empirical results demonstrate that these techniques effectively improve forecast accuracy, with the UKF-based method offering a favorable balance between performance and computational speed.

## Key Contributions

- Formulates and addresses the problem of probabilistic forecast reconciliation under nonlinear constraints for the first time.
- Extends the projection-based reconciliation approach to map forecast samples onto nonlinear coherent manifolds.
- Introduces a conditioning-based reconciliation method inspired by the Unscented Kalman Filter (UKF) that demonstrates superior speed and accuracy over projection-based alternatives.

## Open Questions & Future Work

- [[geodesic-scoring-rules-nonlinear-manifold]]
- [[nonlinear-reconciliation-nongaussian-distributions]]

## Key Concepts

- [[nonlinear-probabilistic-forecast-reconciliation]]: A framework for adjusting independently generated probabilistic forecasts so that they satisfy nonlinear constraints among variables.

## Archivist Review

I approved the primary concept of nonlinear forecast reconciliation as it provides a novel, widely applicable approach to constrained time-series forecasting. I also approved two research questions that identify critical theoretical and practical bottlenecks: the geometric limitation of standard scoring rules on manifolds and the Gaussian constraint of the proposed UKF-based method. No datasets were approved as none were highlighted as unique or central, and all candidates were evaluated against the standard of long-term utility to the forecasting field.

### Approved Concepts
- Nonlinear Probabilistic Forecast Reconciliation: This is the core contribution of the paper, representing a fundamental extension of classical linear forecast reconciliation methods to nonlinear manifold constraints.

### Approved Open Questions
- Geodesic-based probabilistic scoring rules: Evaluating the quality of probabilistic forecasts on nonlinear manifolds requires geometry-aware metrics rather than standard Euclidean metrics to ensure validity and interpretability.
- Non-Gaussian nonlinear probabilistic reconciliation: Many real-world forecasting tasks involve non-Gaussian variables (e.g., counts, intermittency), making this a critical limitation for the adoption of the proposed reconciliation framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.26668)
- [PDF](https://arxiv.org/pdf/2604.26668)

