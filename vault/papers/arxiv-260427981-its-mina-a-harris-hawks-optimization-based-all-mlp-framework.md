---
# CSL-compatible fields
title: "ITS-Mina: A Harris Hawks Optimization-Based All-MLP Framework with Iterative Refinement and External Attention for Multivariate Time Series Forecasting"
author:
  - literal: "Pourya Zamanvaziri"
  - literal: "Amirhossein Sadr"
  - literal: "Aida Pakniyat"
  - literal: "Dara Rahmati"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27981"

# Custom fields
paper_id: "2604.27981"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "multivariate-time-series"
  - "mlp"
  - "attention-mechanism"
  - "hyperparameter-optimization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "iterative-refinement-mechanism"
  - "external-attention-module"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:14:12Z"
created_at: "2026-05-03T05:14:12Z"
---

# ITS-Mina: A Harris Hawks Optimization-Based All-MLP Framework with Iterative Refinement and External Attention for Multivariate Time Series Forecasting

**Authors**: Pourya Zamanvaziri, Amirhossein Sadr, Aida Pakniyat, Dara Rahmati
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27981](https://arxiv.org/abs/2604.27981)

## Summary

ITS-Mina is an all-MLP framework for multivariate time series forecasting that addresses the limitations of standard Transformer models. It employs an iterative refinement mechanism to expand model capacity via weight sharing and an external attention module for efficient global dependency modeling with linear complexity. Additionally, the framework utilizes Harris Hawks Optimization to automatically tune dropout rates, resulting in competitive state-of-the-art performance across six benchmark datasets.

## Key Contributions

- ITS-Mina integrates iterative refinement of residual mixer stacks to deepen model representation without increasing parameter count.
- The external attention module leverages learnable memory units to achieve linear-complexity global dependency modeling.
- Harris Hawks Optimization (HHO) is introduced for adaptive dropout rate tuning, providing dataset-specific regularization.

## Open Questions & Future Work

- [[adaptive-iterative-refinement-halting]]
- [[auxiliary-information-integration-forecasting]]

## Key Concepts

- [[iterative-refinement-mechanism]]: A technique that progressively improves temporal representations through shared-parameter residual mixer stacks.
- [[external-attention-module]]: An attention mechanism utilizing learnable memory units to capture global dependencies with linear complexity.

## Archivist Review

I approved the two main architectural innovations as concepts because they provide reusable mechanisms for efficient time series modeling. I also approved two open questions that address key bottlenecks regarding adaptive inference and external context integration, which are critical for scaling MLP-based forecasting. Harris Hawks Optimization for hyperparameter tuning was rejected as it is a standard optimization algorithm rather than a specialized contribution to time series representation learning.

### Approved Concepts
- Iterative Refinement Mechanism: Increases computational capacity and model depth without increasing parameter count by reusing residual mixer layers.
- External Attention Module: Reduces attention complexity from quadratic to linear while maintaining global dependency modeling.

### Approved Open Questions
- Adaptive Iterative Refinement Halting: This is a key architectural bottleneck that, if resolved, would allow for adaptive inference, potentially saving significant computation on "easy" samples while focusing resources on complex ones, thereby balancing speed and accuracy.
- Integrating Auxiliary Information Covariates: Many real-world forecasting tasks provide access to exogenous variables and static metadata; failing to leverage these is a substantial limitation for any general-purpose time series model.

## Links

- [Abstract](https://arxiv.org/abs/2604.27981)
- [PDF](https://arxiv.org/pdf/2604.27981)

