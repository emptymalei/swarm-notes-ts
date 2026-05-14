---
# CSL-compatible fields
title: "Measures of predictive accuracy, miscalibration and discrimination"
author:
  - literal: "Łukasz Delong"
  - literal: "Mario Wüthrich"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12679"

# Custom fields
paper_id: "2605.12679"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "probabilistic-forecasting"
  - "model-evaluation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mean-squared-concentration-area-abc2"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-14T05:26:04Z"
created_at: "2026-05-14T05:26:04Z"
---

# Measures of predictive accuracy, miscalibration and discrimination

**Authors**: Łukasz Delong, Mario Wüthrich
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12679](https://arxiv.org/abs/2605.12679)

## Summary

This paper evaluates point predictors through the lens of mean-consistent loss functions and Bregman divergences. The authors introduce a modified Murphy's decomposition and demonstrate that popular metrics—such as the ABC, ABC², and Gini scores—may lead to dishonest model selection due to their reliance on predictor-dependent weights. To address these inconsistencies, they propose prioritizing mean-consistent loss functions and provide rigorous conditions for forecast dominance under Lorenz curve intersections.

## Key Contributions

- Derived a modified Murphy’s decomposition for expected loss functions based on Bregman divergences that relies exclusively on predictor values.
- Identified that common accuracy measures like ABC, ABC², and the Gini score use predictor-dependent weights, leading to inconsistent model evaluation compared to mean-consistent scoring functions.
- Established theoretical dominance criteria using third-degree stochastic dominance for cases where Lorenz and Murphy curves exhibit single-crossing intersections.

## Open Questions & Future Work

- [[finite-sample-bregman-evaluation]]

## Key Concepts

- [[mean-squared-concentration-area-abc2]]: A mean-squared variation of the area between concentration and Lorenz curves designed to improve mean-calibration assessment in point forecasting.

## Archivist Review

The approved items represent significant methodological refinements in point forecast evaluation. The ABC² concept addresses identified weaknesses in common evaluation metrics, and the open question targets the essential bottleneck of reconciling theoretically grounded decomposition frameworks with practical finite-sample model selection.

### Approved Concepts
- Mean-Squared Concentration Area (ABC²): Provides a mathematically refined metric for evaluating mean-calibration that addresses limitations in standard Lorenz-curve-based accuracy measures by correcting for predictor-dependent weighting biases.

### Approved Open Questions
- Finite-sample Bregman evaluation: Addresses the critical gap between theoretically sound scoring rules and commonly used, yet potentially dishonest, empirical accuracy metrics.

## Links

- [Abstract](https://arxiv.org/abs/2605.12679)
- [PDF](https://arxiv.org/pdf/2605.12679)

