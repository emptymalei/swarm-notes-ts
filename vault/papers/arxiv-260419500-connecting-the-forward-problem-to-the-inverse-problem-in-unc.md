---
# CSL-compatible fields
title: "Connecting the forward problem to the inverse problem in uncertainty quantification of Earth system models using fast emulators"
author:
  - literal: "Ethan YoungIn Shin"
  - literal: "Baris Kale"
  - literal: "Michael F. Howland"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19500"

# Custom fields
paper_id: "2604.19500"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "uncertainty-quantification"
  - "bayesian-inference"
  - "sensitivity-analysis"
  - "earth-system-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sensitivity-guided-observation-selection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:09:46Z"
created_at: "2026-04-23T05:09:46Z"
---

# Connecting the forward problem to the inverse problem in uncertainty quantification of Earth system models using fast emulators

**Authors**: Ethan YoungIn Shin, Baris Kale, Michael F. Howland
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19500](https://arxiv.org/abs/2604.19500)

## Summary

This paper addresses the computational and conceptual challenges of uncertainty quantification in Earth system models by linking forward sensitivity analysis to inverse Bayesian calibration. By using Gaussian process emulators to replace expensive physical model evaluations, the authors perform global sensitivity analysis across diverse meteorological conditions. They introduce nondimensional diagnostics to identify observation regions that effectively constrain parameter space, enabling a strategic, non-iterative reduction of parameter uncertainty. Their approach is demonstrated to improve the reliability of Bayesian inversion, significantly reducing posterior uncertainty compared to uninformed sampling.

## Key Contributions

- Introduces a non-iterative strategy using forward sensitivity analysis to identify informative observations for Bayesian calibration.
- Develops nondimensional diagnostic measures to determine parameter contributions to output variance relative to observational noise.
- Demonstrates significant reduction in posterior parameter uncertainty through emulator-aided Bayesian inversion using targeted synthetic observations.

## Open Questions & Future Work

- [[informative-observation-selection-for-esm-calibration]]

## Key Concepts

- [[sensitivity-guided-observation-selection]]: A strategy that uses sensitivity analysis to select observations that maximize information gain for Bayesian model calibration.

## Archivist Review

Approved the sensitivity-guided selection concept and the open question regarding ESM parameter calibration. Rejected the WRF model as a dataset, as it is a simulator/software environment rather than a fixed repository of experimental data. Applied the criteria of identifying high-impact, reusable research primitives and unresolved bottlenecks in uncertainty quantification.

### Approved Concepts
- Sensitivity-guided Observation Selection: It provides a systematic, non-iterative approach to selecting informative observations for Bayesian calibration, addressing the ill-posedness of inverse problems.

### Approved Open Questions
- Informative Observation Selection for ESMs: This is a fundamental bottleneck in the efficient calibration and uncertainty quantification of Earth system models, replacing expensive iterative trial-and-error observational strategies with a principled, pre-inference framework.

### Rejected Candidates
- [dataset] Weather Research and Forecasting (WRF) model (`wrf-weather-research-and-forecasting-model`) - other: This is a simulation model/software framework, not a static dataset used for benchmarking performance in the way described by the instructions.

## Links

- [Abstract](https://arxiv.org/abs/2604.19500)
- [PDF](https://arxiv.org/pdf/2604.19500)

