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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "sensitivity-guided-observation-selection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:03:38Z"
created_at: "2026-04-22T05:03:38Z"
---

# Connecting the forward problem to the inverse problem in uncertainty quantification of Earth system models using fast emulators

**Authors**: Ethan YoungIn Shin, Baris Kale, Michael F. Howland
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19500](https://arxiv.org/abs/2604.19500)

## Summary

This paper addresses the computational and ill-posed nature of uncertainty quantification in Earth system models by linking forward sensitivity analysis to inverse Bayesian calibration. The authors employ Gaussian process emulators to surrogate expensive WRF model simulations, enabling global sensitivity analysis across varying observational conditions. They introduce nondimensional diagnostic measures that identify informative observational regions where parameter contributions to output variance are high relative to noise. These metrics serve as a proxy to anticipate the efficacy of Bayesian inversion, successfully reducing posterior parameter uncertainty in atmospheric turbulence parameterizations.

## Key Contributions

- Proposes a sensitivity-guided, non-iterative strategy to identify informative observational data for Bayesian calibration in Earth system models.
- Demonstrates that nondimensional diagnostic measures based on variance sensitivity can predict the potential for parameter uncertainty reduction before performing Bayesian inversion.
- Enables large-scale uncertainty quantification for the WRF model by utilizing Gaussian process emulators to replace $\mathcal{O}(10^5)$ expensive physics-based simulations.

## Open Questions & Future Work

- [[structural-model-discrepancy-in-bayesian-calibration]]

## Key Concepts

- [[sensitivity-guided-observation-selection]]: A non-iterative strategy that uses forward sensitivity analysis to identify informative observational regions for Bayesian calibration.

## Archivist Review

I have approved the core concept of Sensitivity-Guided Observation Selection, which formalizes the paper's primary contribution to bridging forward and inverse uncertainty quantification. The open question regarding structural model discrepancy was also approved as it captures a critical, well-known bottleneck in scientific machine learning that the paper explicitly acknowledges but does not resolve. Other candidates were rejected as subcomponents or for being too specific to the implementation details of the presented atmospheric modeling experiments.

### Approved Concepts
- Sensitivity-Guided Observation Selection: Provides a novel bridge between forward sensitivity analysis and inverse problem calibration, avoiding costly iterative cycles in uncertainty quantification for complex simulations.

### Approved Open Questions
- Structural Model Discrepancy Calibration: Ignoring structural model-form error leads to biased parameter estimates and failure to generalize when calibrated parameters are applied to real-world scenarios.

### Rejected Candidates
- [concept] Nondimensional Diagnostic Measures (`nondimensional-diagnostic-measures`) - subcomponent_of_broader_mechanism: This is a specific subcomponent/heuristic within the broader sensitivity-guided selection framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.19500)
- [PDF](https://arxiv.org/pdf/2604.19500)

