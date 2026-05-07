---
# CSL-compatible fields
title: "Bayesian hypergraph inference from scarce and noisy dynamical observations"
author:
  - literal: "Katerina Tang"
  - literal: "Vivek Srikrishnan"
  - literal: "Jackson Kulik"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.04218"

# Custom fields
paper_id: "2605.04218"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "bayes-this"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:16:47Z"
created_at: "2026-05-07T05:16:47Z"
---

# Bayesian hypergraph inference from scarce and noisy dynamical observations

**Authors**: Katerina Tang, Vivek Srikrishnan, Jackson Kulik
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.04218](https://arxiv.org/abs/2605.04218)

## Summary

The paper addresses the challenge of inferring higher-order interaction structures from scarce and noisy time-series data using a Bayesian extension of Taylor-based hypergraph inference. Bayes-THIS replaces fixed-threshold regression with sparse Bayesian regression to provide robust coefficient estimation and uncertainty-aware inference. While demonstrating superior performance in data-limited regimes, the authors also formally identify a structural non-identifiability issue inherent in Taylor-based approaches, where certain interaction patterns lead to spurious lower-order edge predictions.

## Key Contributions

- Introduces Bayes-THIS, a framework for robustly inferring hypergraph structure from scarce, noisy dynamical time-series data.
- Replaces deterministic sparse regression with Bayesian sparse regression to enable adaptive coefficient shrinkage and residual variance modeling.
- Identifies a fundamental structural non-identifiability in Taylor-based inference where higher-order interactions can cause spurious lower-order edge inflation.

## Open Questions & Future Work

- [[functional-reducibility-and-inferability-link]]

## Key Concepts

- [[bayes-this]]: A Bayesian framework that extends Taylor-based hypergraph inference from time-series data by employing sparse Bayesian regression with automatic relevance determination.

## Archivist Review

The submission introduces a robust Bayesian extension to existing SINDy-based structural inference. I have approved 'Bayes-THIS' as a concept due to its potential for modular reuse in network discovery and 'Functional Reducibility and Inferability' as an open question because it addresses a fundamental, well-defined theoretical limitation of the described framework. Other candidates were not proposed, and no datasets were provided.

### Approved Concepts
- Bayes-THIS: It introduces a robust Bayesian formulation for hypergraph inference in dynamical systems, providing uncertainty-aware coefficient estimation which is critical when data is scarce and noisy.

### Approved Open Questions
- Functional Reducibility and Inferability: This is a fundamental theoretical challenge for structural inference in complex systems; resolving it is necessary to establish the reliability of hypergraph reconstruction in scientific machine learning.

## Links

- [Abstract](https://arxiv.org/abs/2605.04218)
- [PDF](https://arxiv.org/pdf/2605.04218)

