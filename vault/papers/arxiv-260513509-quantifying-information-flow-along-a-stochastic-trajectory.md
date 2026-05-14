---
# CSL-compatible fields
title: "Quantifying information flow along a stochastic trajectory"
author:
  - literal: "Yongjae Oh"
  - literal: "Euijoon Kwon"
  - literal: "Yongjoo Baek"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13509"

# Custom fields
paper_id: "2605.13509"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "stochastic-information-flow-sif-estimation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:23:41Z"
created_at: "2026-05-14T05:23:41Z"
---

# Quantifying information flow along a stochastic trajectory

**Authors**: Yongjae Oh, Euijoon Kwon, Yongjoo Baek
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13509](https://arxiv.org/abs/2605.13509)

## Summary

Stochastic Information Flow (SIF) provides a trajectory-level perspective on information transfer, but its adoption has been hampered by significant computational hurdles. This paper addresses these issues by developing a scalable deep-learning method to estimate SIF from general time-series data. The authors validate their approach using both analytical models and experimental data, demonstrating that SIF acts as a robust indicator for detecting cooperative behavior in complex systems.

## Key Contributions

- Introduces a scalable deep-learning methodology for estimating trajectory-level stochastic information flow from time-series data.
- Demonstrates the model's efficacy on both theoretical benchmarks (two-particle model, Kuramoto oscillators) and biological empirical trajectories (motile cells).
- Enables the use of SIF as a practical, data-driven indicator for identifying cooperative structures in complex dynamical systems.

## Open Questions & Future Work

- [[nesif-transient-state-extension]]

## Key Concepts

- [[stochastic-information-flow-sif-estimation]]: A deep-learning-based framework for estimating trajectory-level information flow from stochastic time-series data.

## Archivist Review

I approved the Stochastic Information Flow (SIF) estimation concept as it introduces a novel, scalable methodology for a classic problem in dynamical systems. I also approved the open question regarding the extension of this framework to transient states, as this is a specific, well-defined limitation that currently restricts the practical application of SIF to non-equilibrium systems. Other candidates were not submitted.

### Approved Concepts
- Stochastic Information Flow (SIF) Estimation: Provides a scalable, data-driven approach to estimate information flow at the individual trajectory level rather than ensemble averages, which is essential for analyzing non-equilibrium dynamical systems.

### Approved Open Questions
- NESIF Transient State Extension: Many real-world dynamical systems operate away from equilibrium; overcoming the steady-state assumption is essential for analyzing transient phenomena in complex biological, climate, and social systems.

## Links

- [Abstract](https://arxiv.org/abs/2605.13509)
- [PDF](https://arxiv.org/pdf/2605.13509)

