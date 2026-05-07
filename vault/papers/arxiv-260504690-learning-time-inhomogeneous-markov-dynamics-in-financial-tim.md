---
# CSL-compatible fields
title: "Learning Time-Inhomogeneous Markov Dynamics in Financial Time Series via Neural Parameterization"
author:
  - literal: "Jan Rovirosa"
  - literal: "Jesse Schmolze"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04690"

# Custom fields
paper_id: "2605.04690"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "probabilistic-forecasting"
  - "interpretability"
architectures:
  []
datasets:
  []
concept_slugs:
  - "neural-parameterized-markov-transition-operators"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:15:22Z"
created_at: "2026-05-07T05:15:22Z"
---

# Learning Time-Inhomogeneous Markov Dynamics in Financial Time Series via Neural Parameterization

**Authors**: Jan Rovirosa, Jesse Schmolze
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04690](https://arxiv.org/abs/2605.04690)

## Summary

This paper proposes a framework for modeling non-stationary stochastic systems by using neural networks to parameterize time-varying Markov transition matrices. By enforcing stochastic constraints on the network output, the approach preserves the mathematical transparency of classical transition operators while leveraging deep learning for empirical estimation in high-noise environments. Evaluations on financial time series demonstrate that the learned operators effectively track regime shifts and provide diagnostic insights into the limitations of first-order Markov memory.

## Key Contributions

- Introduces a framework that parameterizes time-varying Markov transition operators using neural networks, ensuring structural interpretability.
- Demonstrates that neural-generated transition operators successfully capture financial regime shifts, showing a strong correlation (r=-0.62) between operator row entropy and realized variance.
- Utilizes the Chapman-Kolmogorov equations as a diagnostic tool for detecting violations of first-order Markov memory assumptions in temporal data.

## Open Questions & Future Work

- [[scaling-neural-markov-multi-asset]]
- [[continuous-time-operator-modeling]]

## Key Concepts

- [[neural-parameterized-markov-transition-operators]]: A framework that uses neural networks to generate time-varying Markov transition matrices that maintain formal stochastic properties.

## Archivist Review

I approved the neural-parameterized Markov transition operator concept as it provides a reusable mechanism for integrating deep learning with classical stochastic operator analysis. I also approved two open questions that specifically address the limitations of scaling such operators to multi-asset settings and transitioning them to continuous-time models, which are substantial bottlenecks in the field. No datasets were approved as they were not identified as central or reusable within the provided text.

### Approved Concepts
- Neural Parameterized Markov Transition Operators: Combines the flexibility of deep learning with the structural interpretability of Markov operators by enforcing formal stochastic constraints on network outputs.

### Approved Open Questions
- Scaling Neural Markov Models: Moving beyond single-asset analysis is crucial for validating the scalability of this approach and its practical utility in real-world systematic financial management.
- Continuous-Time Operator Frameworks: Continuous-time formulations offer a more mathematically rigorous way to handle high-frequency, asynchronous financial data compared to arbitrary time-grid discretization.

## Links

- [Abstract](https://arxiv.org/abs/2605.04690)
- [PDF](https://arxiv.org/pdf/2605.04690)

