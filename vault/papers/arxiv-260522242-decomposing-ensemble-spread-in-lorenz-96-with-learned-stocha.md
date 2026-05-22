---
# CSL-compatible fields
title: "Decomposing Ensemble Spread in Lorenz '96 With Learned Stochastic Parameterizations"
author:
  - literal: "Birgit Kühbacher"
  - literal: "Daan Crommelin"
  - literal: "Niki Kilbertus"
issued:
  date-parts:
    - [2026, 5, 21]
url: "https://arxiv.org/abs/2605.22242"

# Custom fields
paper_id: "2605.22242"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "stochastic-modeling"
  - "uncertainty-quantification"
architectures:
  []
datasets:
  []
concept_slugs:
  - "stochastic-parameterization-ensemble-decomposition"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-22T05:29:26Z"
created_at: "2026-05-22T05:29:26Z"
---

# Decomposing Ensemble Spread in Lorenz '96 With Learned Stochastic Parameterizations

**Authors**: Birgit Kühbacher, Daan Crommelin, Niki Kilbertus
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22242](https://arxiv.org/abs/2605.22242)

## Summary

This paper addresses the common issue of underdispersive ensemble forecasts in chaotic systems by investigating the two-scale Lorenz '96 model. The authors develop a framework to systematically disentangle the roles of intrinsic variability, initial-condition perturbations, and stochastic model uncertainty. Through the comparison of various deterministic, autoregressive, Bayesian, and flow-based parameterizations, the study reveals that persistent stochastic structures are key to achieving superior spread-error consistency. These findings provide actionable insights for improving stochastic parameterization design in complex weather and climate forecasting models.

## Key Contributions

- Proposes a systematic decomposition framework for disentangling intrinsic variability, initial-condition, and model uncertainty in the two-scale Lorenz '96 system.
- Demonstrates that ensemble perturbations primarily regulate trajectory decorrelation and invariant measure exploration rather than increasing long-term variance.
- Establishes that stochastic parameterizations with temporally persistent structure significantly enhance early ensemble spread growth and spread-error consistency.

## Key Concepts

- [[stochastic-parameterization-ensemble-decomposition]]: A framework for isolating and analyzing the relative contributions of intrinsic variability, initial condition uncertainty, and stochastic parameterization to ensemble spread.

## Archivist Review

The paper's proposed framework for decomposing ensemble uncertainty sources addresses a persistent challenge in weather and climate modeling. I have approved the framework concept as it provides a valuable diagnostic tool for assessing spread-error consistency. Other candidates were rejected for being routine testbeds or failing to meet the strict criteria for standalone conceptual or dataset importance.

### Approved Concepts
- Stochastic Parameterization Ensemble Decomposition: It provides a formal mechanism for diagnosing underdispersive forecast ensembles by isolating distinct uncertainty contributions in chaotic systems.

### Rejected Candidates
- [dataset] Lorenz 1996 (`lorenz-1996`) - other: This is a widely used standard mathematical model/testbed rather than a novel or domain-specific dataset.

## Links

- [Abstract](https://arxiv.org/abs/2605.22242)
- [PDF](https://arxiv.org/pdf/2605.22242)

