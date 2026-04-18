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
  - "time-series-forecasting"
  - "bayesian-inference"
  - "robust-learning"
  - "hidden-markov-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "br-ihmm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:53:26Z"
created_at: "2026-04-18T04:53:26Z"
---

# Doubly Outlier-Robust Online Infinite Hidden Markov Model

**Authors**: Horace Yiu, Leandro Sánchez-Betancourt, Álvaro Cartea, Gerardo Duran-Martin
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.14322](https://arxiv.org/abs/2604.14322)

## Summary

This paper introduces the Batched Robust iHMM (BR-iHMM), a robustified approach to online infinite Hidden Markov Models designed for streaming data contaminated with outliers. By leveraging the posterior influence function (PIF) from generalized Bayesian inference, the authors provide theoretical guarantees that the model maintains bounded sensitivity to anomalous observations. The approach effectively balances the trade-off between robustness and the adaptation lag typically associated with regime switching, showing significant forecasting gains on complex real-world datasets.

## Key Contributions

- Derives a robust online infinite HMM update rule by bounding the posterior influence function (PIF) to mitigate the impact of outliers and model misspecification.
- Introduces the Batched Robust iHMM (BR-iHMM) which manages the inherent trade-off between robustness to outliers and responsiveness to regime switches.
- Demonstrates a performance improvement of up to 67% in one-step-ahead forecasting error compared to standard online Bayesian methods across diverse domains including financial limit order books and electricity demand.

## Open Questions & Future Work

- [[link-pif-predictive-accuracy]]
- [[ihmm-robustness-non-lg]]

## Key Concepts

- [[br-ihmm]]: A robustified online infinite hidden Markov model that balances adaptivity and forecasting performance via bounded posterior influence functions.

## Archivist Review

I approved the core architectural contribution (BR-iHMM) as it provides a concrete, reusable mechanism for balancing robustness and adaptivity in online state-space models. I rejected the Posterior Influence Function as it is a standard statistical concept, and I rejected the datasets as they were generic labels (limit order books, electricity demand) rather than specific benchmarks. The open questions regarding predictive stability and non-Gaussian generalization were approved as they identify significant theoretical barriers to the practical adoption of robust Bayesian methods.

### Approved Concepts
- Batched Robust iHMM (BR-iHMM): Provides a novel, reusable framework for robustifying online Bayesian infinite HMMs using batched processing to handle outliers.

### Approved Open Questions
- PIF and Predictive Accuracy Link: Essential for justifying robust Bayesian methods as optimal for predictive tasks under misspecification, moving beyond heuristic justifications.
- Robustness for Non-LG Emissions: Crucial for the practical utility of robust Bayesian modeling in non-linear or non-Gaussian systems like GARCH or chaotic dynamics.

### Rejected Candidates
- [concept] Posterior Influence Function (PIF) (`posterior-influence-function`) - not_novel: The Posterior Influence Function is a well-established concept in statistics and generalized Bayesian inference, not a novel contribution of this paper.

## Links

- [Abstract](https://arxiv.org/abs/2604.14322)
- [PDF](https://arxiv.org/pdf/2604.14322)

