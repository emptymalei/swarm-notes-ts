---
# CSL-compatible fields
title: "Bayesian Modelling of Nonstationary Extreme Values Using a Nonparametric Hawkes Process"
author:
  - literal: "Gordon J. Ross"
  - literal: "Dean Markwick"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03331"

# Custom fields
paper_id: "2605.03331"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "nonparametric-hawkes-process-extreme-values"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:12:42Z"
created_at: "2026-05-06T05:12:42Z"
---

# Bayesian Modelling of Nonstationary Extreme Values Using a Nonparametric Hawkes Process

**Authors**: Gordon J. Ross, Dean Markwick
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03331](https://arxiv.org/abs/2605.03331)

## Summary

This paper introduces a Bayesian nonparametric point process for modelling nonstationary extreme events characterized by varying occurrence rates and magnitudes. By combining a self-exciting Hawkes process—learned via a Dirichlet process—with a hierarchical mark model utilizing a Generalised Pareto Distribution, the authors effectively capture event clustering and magnitude variability. The approach employs partial pooling to stabilize GPD parameter estimation, particularly in regimes with sparse observations, and is validated through both simulation and superior performance on empirical datasets.

## Key Contributions

- Proposes a Bayesian point process model that integrates a self-exciting Hawkes process with a hierarchical Generalised Pareto Distribution (GPD) for nonstationary extreme events.
- Uses a Dirichlet process for learning the temporal excitation structure, facilitating flexible modelling of clustered event rates.
- Demonstrates superior held-out predictive performance across four empirical datasets compared to standard extreme value model variants.

## Open Questions & Future Work

- [[covariate-dependent-background-intensity]]
- [[multivariate-extreme-value-modeling]]

## Key Concepts

- [[nonparametric-hawkes-process-extreme-values]]: A Bayesian nonparametric approach using a Dirichlet process to learn temporal excitation patterns within a Hawkes point process for extreme events.

## Archivist Review

The paper presents a sophisticated Bayesian nonparametric approach to extreme value modeling, successfully combining Hawkes processes with GPD hierarchies. The approved concept captures a reusable methodological advance in point process modeling for nonstationary extremes. The approved open questions address core limitations—exogenous conditioning and multivariate scalability—which are substantial, recurring challenges in extreme value forecasting.

### Approved Concepts
- Nonparametric Hawkes Process for Extreme Values: This integration enables flexible learning of clustering dynamics in nonstationary extreme event processes without assuming rigid parametric forms, which is a major hurdle in extreme value theory.

### Approved Open Questions
- Covariate-dependent Background Intensity: Distinguishing between long-term drivers and short-term cascades is vital for robust risk assessment in both natural and financial contexts.
- Multivariate Extreme Value Modeling: Multivariate modeling is essential for realistic risk assessment in complex interconnected systems like global financial markets or disaster networks.

## Links

- [Abstract](https://arxiv.org/abs/2605.03331)
- [PDF](https://arxiv.org/pdf/2605.03331)

