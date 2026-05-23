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
  - "ensemble-methods"
  - "uncertainty-quantification"
  - "chaotic-systems"
architectures:
  []
datasets:
  []
concept_slugs:
  - "stochastic-parameterization-ensemble-decomposition"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-23T05:21:54Z"
created_at: "2026-05-23T05:21:54Z"
---

# Decomposing Ensemble Spread in Lorenz '96 With Learned Stochastic Parameterizations

**Authors**: Birgit Kühbacher, Daan Crommelin, Niki Kilbertus
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22242](https://arxiv.org/abs/2605.22242)

## Summary

This paper investigates the persistent issue of underdispersive ensemble forecasts in chaotic systems by decomposing the sources of forecast spread into intrinsic variability, initial conditions, and model uncertainty. Using the two-scale Lorenz '96 model, the authors evaluate various parameterization strategies and show that stochastic parameterizations with temporal persistence are superior at improving spread-error consistency. The findings offer a principled approach to designing more robust stochastic representations for weather and climate models.

## Key Contributions

- Establishes a systematic decomposition framework to disentangle intrinsic variability, initial-condition perturbations, and stochastic model uncertainty in the Lorenz '96 system.
- Demonstrates that stochastic parameterizations with temporally persistent structures significantly improve early ensemble spread growth and spread-error consistency.
- Provides critical diagnostic insights into how ensemble perturbations regulate trajectory decorrelation and the exploration of the system's invariant measure.

## Key Concepts

- [[stochastic-parameterization-ensemble-decomposition]]: A systematic methodological framework to disentangle intrinsic variability, initial-condition uncertainty, and model-error uncertainty in ensemble systems.

## Archivist Review

The paper is approved for the contribution of a systematic framework for decomposing ensemble uncertainty. I have rejected no candidates as this single concept effectively captures the paper's primary methodological contribution to uncertainty quantification in chaotic forecasting systems.

### Approved Concepts
- Stochastic Parameterization Ensemble Decomposition: Provides a rigorous framework for isolating the sources of uncertainty in ensemble weather and climate models, which is crucial for addressing underdispersive ensemble forecasts.

## Links

- [Abstract](https://arxiv.org/abs/2605.22242)
- [PDF](https://arxiv.org/pdf/2605.22242)

