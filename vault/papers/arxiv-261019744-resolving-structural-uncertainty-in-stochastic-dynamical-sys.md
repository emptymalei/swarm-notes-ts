---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Resolving Structural Uncertainty in Stochastic Dynamical Systems via Ensemble-Based Bayesian Inference"
description: "This paper proposes a fully Bayesian ensemble-based framework for inferring the interaction structure of complex stochastic dynamical systems from sparse observations. By formulating an SDE likelihood as an Onsager-Machlup quasi-potential and employing a non-parametric Minimum Description Length (MDL) prior, the method effectively regularizes network complexity and prevents overfitting. Evaluation on population dynamics reveals that resolving causal information requires non-stationary transient data, and that propagating structural uncertainty via the full posterior ensemble significantly outperforms point estimates (MAP) in predicting the outcomes of system perturbations."
resource: "https://arxiv.org/abs/2610.19744"
tags:
  - "bayesian-inference"
  - "stochastic-processes"
  - "dynamical-systems"
  - "network-analysis"
  - "uncertainty-quantification"
  - "time-series-analysis"
  - "causal-inference"
  - "non-stationary"
  - "stochastic-modeling"
timestamp: "2026-10-18T00:42:42Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Francesco Zambelli"
  - literal: "Valeria D'Andrea"
  - literal: "Manlio De Domenico"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19744"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "onsager-machlup-sde-likelihood"
    description: "A likelihood formulation for stochastic differential equations based on the path-integral quasi-potential of non-equilibrium trajectories."
  - name: "mdl-structural-prior"
    description: "A regularization technique for network structure inference that uses Minimum Description Length principles to discretize continuous parameters and penalize complexity."
datasets:
  []
open_questions:
  - name: "structural-inference-model-mismatch"
    description: "How can ensemble-based Bayesian frameworks be extended to provide reliable structural uncertainty estimates when the true interaction types or functional forms are entirely absent from the model's hypothesis space (vocabulary)?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:42:42Z"
created_at: "2026-10-18T00:42:42Z"
---

# Resolving Structural Uncertainty in Stochastic Dynamical Systems via Ensemble-Based Bayesian Inference

**Authors**: Francesco Zambelli, Valeria D'Andrea, Manlio De Domenico
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19744](https://arxiv.org/abs/2610.19744)

## Summary

This paper proposes a fully Bayesian ensemble-based framework for inferring the interaction structure of complex stochastic dynamical systems from sparse observations. By formulating an SDE likelihood as an Onsager-Machlup quasi-potential and employing a non-parametric Minimum Description Length (MDL) prior, the method effectively regularizes network complexity and prevents overfitting. Evaluation on population dynamics reveals that resolving causal information requires non-stationary transient data, and that propagating structural uncertainty via the full posterior ensemble significantly outperforms point estimates (MAP) in predicting the outcomes of system perturbations.

## Key Contributions

- Developed a Bayesian ensemble-based inference framework for recovering interaction networks from sparse, stochastic time-series data.
- Integrated an Onsager-Machlup quasi-potential likelihood with a Minimum Description Length (MDL) prior to avoid kinetic overfitting in high-dimensional structure spaces.
- Demonstrated through population dynamics benchmarks that non-stationary transient data is a prerequisite for resolving causal structural information.
- Showed that propagating full structural uncertainty via ensemble posterior analysis yields more reliable predictions for downstream system perturbations than MAP estimates.

## Limitations

The framework requires non-stationary transient data to resolve causal structure and may face computational scaling challenges due to the high-dimensional MCMC topological sampling.

## Open Questions & Future Work

- [[structural-inference-model-mismatch]]

## Key Concepts

- [[onsager-machlup-sde-likelihood]]: A likelihood formulation for stochastic differential equations based on the path-integral quasi-potential of non-equilibrium trajectories.
- [[mdl-structural-prior]]: A regularization technique for network structure inference that uses Minimum Description Length principles to discretize continuous parameters and penalize complexity.

## Archivist Review

The approved concepts represent the core mathematical and regularizing contributions of the paper (Onsager-Machlup likelihood and MDL priors), which are highly relevant to the intersection of physics and ML. The open question addresses a fundamental limitation in structural discovery: the assumption of a complete model library. No datasets were approved as the paper utilizes generic population dynamics simulations rather than unique, named benchmark datasets.

### Approved Concepts
- Onsager-Machlup SDE Likelihood: It provides a formal path-integral basis for evaluating the likelihood of time-series trajectories in stochastic systems, bridging statistical mechanics and Bayesian inference.
- MDL Structural Prior: It addresses the ill-posed nature of network reconstruction by using information-theoretic principles to regularize discrete graph structures and continuous parameters simultaneously.

### Approved Open Questions
- Robustness to Structural Misspecification: Ensuring robustness to model misspecification is essential for applying automated discovery tools to biological or social systems where the fundamental 'laws' are not known a priori.

## Links

- [Abstract](https://arxiv.org/abs/2610.19744)
- [PDF](https://arxiv.org/pdf/2610.19744)

