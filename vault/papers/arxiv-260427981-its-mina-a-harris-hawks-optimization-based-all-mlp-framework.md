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
  - "mlp-architecture"
  - "attention-mechanism"
  - "optimization"
  - "regularization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "iterative-refinement-mechanism"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:07:28Z"
created_at: "2026-05-02T05:07:28Z"
---

# ITS-Mina: A Harris Hawks Optimization-Based All-MLP Framework with Iterative Refinement and External Attention for Multivariate Time Series Forecasting

**Authors**: Pourya Zamanvaziri, Amirhossein Sadr, Aida Pakniyat, Dara Rahmati
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27981](https://arxiv.org/abs/2604.27981)

## Summary

ITS-Mina is an all-MLP framework designed for efficient multivariate time series forecasting. It employs an iterative refinement mechanism to deepen representation learning through parameter sharing and replaces traditional self-attention with linear-complexity external memory units. Additionally, the framework utilizes Harris Hawks Optimization to automatically tune dropout rates, demonstrating state-of-the-art results on six benchmark datasets across various forecasting horizons.

## Key Contributions

- ITS-Mina proposes a novel all-MLP framework for multivariate time series forecasting that combines iterative refinement, external attention, and automated hyperparameter optimization.
- The iterative refinement mechanism enhances model depth through shared-parameter residual mixers without increasing the parameter count.
- The external attention module leverages learnable memory units to capture global cross-sample dependencies with linear complexity.
- Harris Hawks Optimization (HHO) is introduced for adaptive dataset-specific dropout rate tuning, improving generalization across six standard benchmarks.

## Open Questions & Future Work

- [[adaptive-iterative-refinement-halting]]

## Key Concepts

- [[iterative-refinement-mechanism]]: A technique to deepen a model's representation learning via repeated applications of shared-parameter residual mixer stacks.

## Archivist Review

The concept of iterative refinement via shared-parameter stacks is a reusable architectural pattern that balances capacity with parameter efficiency, distinct enough for its own note. The open question on adaptive halting for iterative processes addresses a fundamental limitation in current static-depth forecasting architectures. Other candidates were rejected as either implementation-specific details (HHO dropout tuning) or general boilerplate suggestions for future work (auxiliary data integration).

### Approved Concepts
- Iterative Refinement Mechanism: Enables increasing the effective model depth and computational capacity without increasing the number of learnable parameters.

### Approved Open Questions
- Adaptive Iterative Refinement Halting: Developing dynamic stopping criteria for iterative models can potentially improve computational efficiency by allocating more compute to complex inputs and less to simpler ones.

## Links

- [Abstract](https://arxiv.org/abs/2604.27981)
- [PDF](https://arxiv.org/pdf/2604.27981)

