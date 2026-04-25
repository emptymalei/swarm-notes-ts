---
# CSL-compatible fields
title: "Interpretable Analytic Formulae for GWTC-4 Binary Black Hole Population Properties via Symbolic Regression"
author:
  - literal: "Chayan Chatterjee"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20941"

# Custom fields
paper_id: "2604.20941"
paper_source: "arxiv"
domain: "physics-astronomy-ml"
tags:
  - "symbolic-regression"
  - "astrophysics"
  - "bayesian-inference"
architectures:
  []
datasets:
  - "gwtc-4"
concept_slugs:
  - "symbolic-regression-for-population-inference"
dataset_slugs:
  - "gwtc-4"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:56:11Z"
created_at: "2026-04-25T04:56:11Z"
---

# Interpretable Analytic Formulae for GWTC-4 Binary Black Hole Population Properties via Symbolic Regression

**Authors**: Chayan Chatterjee
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20941](https://arxiv.org/abs/2604.20941)

## Summary

This paper addresses the lack of transparency in current binary black hole (BBH) population models by utilizing symbolic regression to analyze GWTC-4 catalog posteriors. The author derives compact, closed-form analytic expressions for key astrophysical relationships, including merger-rate redshift evolution and spin-mass correlations. These analytic formulae provide exact gradient diagnostics and serve as efficient surrogate models for complex numerical posteriors, facilitating improved physical interpretation and faster computation for downstream astrophysical tasks.

## Key Contributions

- Introduces a symbolic regression framework to derive interpretable, closed-form analytic expressions for BBH population properties from GWTC-4 posterior data.
- Identifies that mass ratio-spin and redshift-spin correlations in BBH populations are primarily driven by posterior width broadening rather than mean shifts.
- Enables rapid downstream astrophysics applications such as rate forecasting and formation channel comparison via exact analytic derivatives and compact surrogate modeling.

## Key Concepts

- [[symbolic-regression-for-population-inference]]: The use of symbolic regression to distill complex posterior inference products into compact, closed-form analytic expressions for physical parameters.

## Archivist Review

The paper provides a strong methodological contribution by using symbolic regression to extract interpretable, closed-form models from numerical astrophysical posteriors. I approved the core concept of symbolic regression for population inference due to its potential for reuse in other scientific domains where black-box Bayesian inference currently lacks transparency. The GWTC-4 dataset is included as it is the primary empirical source for these population studies.

### Approved Concepts
- Symbolic Regression for Population Inference: It replaces opaque phenomenological models with interpretable, differentiable analytic laws for complex astrophysical populations, offering a bridge between numerical posterior estimation and physical law discovery.

## Datasets

- [[gwtc-4]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20941)
- [PDF](https://arxiv.org/pdf/2604.20941)

