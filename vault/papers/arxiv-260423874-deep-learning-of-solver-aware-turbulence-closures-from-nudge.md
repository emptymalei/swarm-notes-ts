---
# CSL-compatible fields
title: "Deep Learning of Solver-Aware Turbulence Closures from Nudged LES Dynamics"
author:
  - literal: "Ashwin Suriyanarayanan"
  - literal: "Melissa Adrian"
  - literal: "Dibyajyoti Chakraborty"
  - literal: "Romit Maulik"
issued:
  date-parts:
    - [2026, 4, 26]
url: "https://arxiv.org/abs/2604.23874"

# Custom fields
paper_id: "2604.23874"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "physics-informed-machine-learning"
  - "computational-fluid-dynamics"
  - "forecasting"
  - "model-generalization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "cda-turbulence-closure-training"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:16:31Z"
created_at: "2026-04-28T05:16:31Z"
---

# Deep Learning of Solver-Aware Turbulence Closures from Nudged LES Dynamics

**Authors**: Ashwin Suriyanarayanan, Melissa Adrian, Dibyajyoti Chakraborty, Romit Maulik
**Date**: 2026-04-26
**Paper ID**: [arxiv:2604.23874](https://arxiv.org/abs/2604.23874)

## Summary

This paper introduces a novel approach for learning turbulence closures in large eddy simulations (LES) by leveraging continuous data assimilation (nudging). Unlike traditional a-posteriori methods that require expensive backpropagation through solvers, this framework enables stable training by treating high-fidelity DNS data as sparse observations. The proposed method successfully captures ground-truth statistics and generalizes across varied numerical and temporal discretizations while maintaining long-term stability. Evaluations confirm that the learned closures effectively account for numerical discretization errors, surpassing traditional closure models in robustness.

## Key Contributions

- Introduces a nudging-based (CDA) approach for a-priori training of turbulence closures that incorporates solver effects without backpropagation.
- Demonstrates improved long-term stability and generalization across different numerical and temporal discretization schemes compared to traditional closure models.
- Achieves DNS-consistent statistical accuracy in coarse-grid LES using sparse observations, effectively mitigating the filter-discretization mismatch inherent in standard a-priori learning.

## Open Questions & Future Work

- [[generalizing-closures-across-numerical-schemes]]

## Key Concepts

- [[cda-turbulence-closure-training]]: A training framework for turbulence closures that uses continuous data assimilation (nudging) to account for solver discretizations and ensure stability during a-priori learning.

## Archivist Review

The approved concept introduces a significant shift in how turbulence closures are trained by utilizing CDA (nudging) as a bridge between efficient a-priori learning and stable a-posteriori performance. This provides a robust alternative to expensive backpropagation methods. The approved open question addresses the critical bottleneck of scheme-dependence in physics-informed forecasting, which remains a primary hurdle for practical scientific machine learning deployment. Other candidates were rejected for being local performance considerations or incremental extensions rather than fundamental research problems.

### Approved Concepts
- Continuous Data Assimilation (CDA) Turbulence Closure Training: It provides a computationally efficient alternative to a-posteriori training by leveraging nudging to incorporate solver-specific numerical dynamics without requiring expensive adjoints or full backpropagation.

### Approved Open Questions
- Generalizing closures across schemes: Practical deployment of learned closure models in industry depends on the ability to generalize across solvers without the prohibitive cost of retraining for every specific scheme.

### Rejected Candidates
- [open_question] Nudging with sparse observations (`nudging-with-sparse-noisy-data`) - low_impact: The question is framed as a performance optimization/robustness check for an existing methodology rather than a fundamental open research problem in the field.

## Links

- [Abstract](https://arxiv.org/abs/2604.23874)
- [PDF](https://arxiv.org/pdf/2604.23874)

