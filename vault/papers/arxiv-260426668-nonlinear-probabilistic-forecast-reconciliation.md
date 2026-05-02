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
processed_at: "2026-05-02T05:11:56Z"
created_at: "2026-05-02T05:11:56Z"
---

# Nonlinear Probabilistic Forecast Reconciliation

**Authors**: Anubhab Biswas, Lorenzo Zambon, Lorenzo Nespoli, Giorgio Corani
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26668](https://arxiv.org/abs/2604.26668)

## Summary

This paper addresses the challenge of reconciling probabilistic forecasts when variables must satisfy nonlinear constraints, a significant limitation of existing linear reconciliation methods. The authors propose two novel strategies: a projection approach that maps forecast samples to the nonlinear manifold, and a conditioning approach leveraging an Unscented Kalman Filter (UKF) algorithm. Empirical evaluations indicate that both methods effectively improve forecast accuracy, with the UKF-based conditioning approach providing a more scalable and performant solution.

## Key Contributions

- Introduces a novel framework for probabilistic forecast reconciliation subject to nonlinear constraints, covering both projection and conditioning methods.
- Adapts the Unscented Kalman Filter (UKF) as a conditioning approach for non-linear forecast reconciliation, providing a computationally efficient alternative to sample-based projection.
- Demonstrates that both proposed reconciliation approaches improve accuracy across synthetic and real-world datasets, with the UKF-based method offering superior speed and performance.

## Open Questions & Future Work

- [[geodesic-evaluation-nonlinear-reconciliation]]
- [[nonlinear-reconciliation-non-gaussian]]

## Key Concepts

- [[nonlinear-probabilistic-forecast-reconciliation]]: A framework to ensure probabilistic forecast coherence when variables are related through nonlinear constraints.

## Archivist Review

I have approved the core conceptual framework for nonlinear forecast reconciliation as it introduces a new and important domain for time series forecasting. I have also approved two open questions that specifically identify theoretical bottlenecks—the limitations of Euclidean scoring rules on manifolds and the Gaussian constraints of current UKF-based reconciliation. No datasets were approved as none provided sufficient evidence of being novel or reusable benchmarks in the context of this specific paper.

### Approved Concepts
- Nonlinear Probabilistic Forecast Reconciliation: Establishes a novel framework for handling nonlinear constraints in probabilistic forecasting, overcoming the limitations of standard linear reconciliation methods.

### Approved Open Questions
- Geodesic evaluation nonlinear reconciliation: Current metrics like CRPS or Energy Scores are rooted in Euclidean space and may not accurately reflect performance on non-linear coherent manifolds.
- Non-Gaussian nonlinear reconciliation: The reliance on Gaussianity in UKF-based reconciliation prevents the application of this efficient framework to common real-world data types like intermittent or discrete time series.

## Links

- [Abstract](https://arxiv.org/abs/2604.26668)
- [PDF](https://arxiv.org/pdf/2604.26668)

