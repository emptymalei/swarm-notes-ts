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
  - "time-series-forecasting"
  - "multivariate-forecasting"
  - "attention-mechanisms"
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
processed_at: "2026-05-01T05:22:06Z"
created_at: "2026-05-01T05:22:06Z"
---

# ITS-Mina: A Harris Hawks Optimization-Based All-MLP Framework with Iterative Refinement and External Attention for Multivariate Time Series Forecasting

**Authors**: Pourya Zamanvaziri, Amirhossein Sadr, Aida Pakniyat, Dara Rahmati
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27981](https://arxiv.org/abs/2604.27981)

## Summary

ITS-Mina is a novel all-MLP architecture designed for multivariate time series forecasting that avoids the high computational overhead of Transformer-based models. The framework features an iterative refinement module for deep representation learning with shared parameters and an external attention mechanism for linear-time global dependency modeling. Additionally, it incorporates Harris Hawks Optimization (HHO) for adaptive dropout regularization, yielding superior predictive performance across multiple benchmark datasets.

## Key Contributions

- Introduces ITS-Mina, an all-MLP framework for multivariate time series forecasting leveraging parameter-efficient iterative refinement.
- Implements an external attention module with linear computational complexity to model cross-sample dependencies.
- Utilizes Harris Hawks Optimization (HHO) for dataset-specific adaptive dropout tuning to improve generalization.
- Achieves state-of-the-art performance on six common multivariate time series benchmarks across varying forecasting horizons.

## Open Questions & Future Work

- [[adaptive-iterative-refinement-halting]]
- [[auxiliary-information-integration-forecasting]]

## Key Concepts

- [[iterative-refinement-mechanism]]: A shared-parameter residual mixer stack that iteratively refines temporal representations to improve model depth efficiently.
- [[external-attention-module]]: A linear-complexity attention mechanism using learnable memory units to capture cross-sample global dependencies.

## Archivist Review

Approved the core architectural innovations of the framework (iterative refinement and external attention) and two substantial research questions regarding adaptive computation and auxiliary feature integration. Rejected the Harris Hawks Optimization proposal as it is a specific hyperparameter optimization technique rather than a foundational forecasting mechanism.

### Approved Concepts
- Iterative Refinement Mechanism: Central mechanism for enhancing temporal representation depth without increasing parameter count.
- External Attention Module: Addresses the O(n^2) complexity of standard self-attention in multivariate forecasting.

### Approved Open Questions
- Adaptive Iterative Refinement Halting: Implementing adaptive computation is technically significant as it enables models to scale their computational effort based on input complexity, potentially leading to faster inference for "easy" samples while maintaining accuracy for "hard" samples.
- Auxiliary Information Integration Forecasting: Integrating external information is critical for real-world deployment, where forecasting accuracy is often capped by the absence of domain-specific context.

### Rejected Candidates
- [concept] Harris Hawks Optimization for Dropout Tuning (`hho-dropout-tuning`) - subcomponent_of_broader_mechanism: Using a global optimization heuristic for a sub-task like hyperparameter tuning is a common implementation detail that does not warrant a core architectural concept note.

## Links

- [Abstract](https://arxiv.org/abs/2604.27981)
- [PDF](https://arxiv.org/pdf/2604.27981)

