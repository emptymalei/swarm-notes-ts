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
domain: "astrophysics"
tags:
  []
architectures:
  []
datasets:
  - "gwtc-4"
concept_slugs:
  - "posterior-symbolic-compression"
dataset_slugs:
  - "gwtc-4"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:09:54Z"
created_at: "2026-04-24T05:09:54Z"
---

# Interpretable Analytic Formulae for GWTC-4 Binary Black Hole Population Properties via Symbolic Regression

**Authors**: Chayan Chatterjee
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20941](https://arxiv.org/abs/2604.20941)

## Summary

This paper introduces an approach to characterize binary black hole population properties by applying symbolic regression to the GWTC-4 posterior inference data. By compressing complex phenomenological models into compact, closed-form analytic expressions, the framework provides transparent insights into merger-rate evolution and spin-mass correlations. These analytic formulae enable exact gradient diagnostics and serve as efficient surrogate models for downstream astrophysical applications, overcoming the limitations of black-box numerical posteriors.

## Key Contributions

- Discovers four closed-form analytic expressions for key binary black hole population relationships using symbolic regression on GWTC-4 posterior data.
- Demonstrates that observed mass-ratio--effective-spin and redshift--effective-spin correlations are driven by posterior broadening rather than shifts in the mean.
- Provides analytic derivative diagnostics for population models, enabling more efficient downstream tasks like rate forecasting and stochastic background estimation.

## Key Concepts

- [[posterior-symbolic-compression]]: The use of symbolic regression to distill complex numerical posterior distributions into compact, differentiable, and interpretable closed-form analytic expressions.

## Archivist Review

I have approved 'Posterior Symbolic Compression' as a generalized, reusable method for distilling complex posterior models into interpretable analytic forms. This replaces the paper-specific 'Symbolic Regression for GWTC-4 Population Analysis'. I also approved 'GWTC-4' as a key dataset. All other candidates were rejected as they were either too specific or covered by the generalized concept.

### Approved Concepts
- Posterior Symbolic Compression: Enables distillation of high-dimensional, complex numerical posterior models into interpretable, differentiable, and closed-form analytic laws, which are crucial for diagnostics and surrogate modeling.

### Rejected Candidates
- [concept] Symbolic Regression for GWTC-4 Population Analysis (`symbolic-regression-for-gwtc-4-population-analysis`) - duplicate_existing: Replaced by a more generalized and reusable concept 'Posterior Symbolic Compression'.

## Datasets

- [[gwtc-4]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20941)
- [PDF](https://arxiv.org/pdf/2604.20941)

