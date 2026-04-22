---
# CSL-compatible fields
title: "Skillful Global Ocean Emulation and the Role of Correlation-Aware Loss"
author:
  - literal: "Niraj Agarwal"
  - literal: "Timothy A. Smith"
  - literal: "Sergey Frolov"
  - literal: "Laura C. Slivinski"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18727"

# Custom fields
paper_id: "2604.18727"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "graph-neural-networks"
  - "ocean-dynamics"
  - "data-assimilation"
architectures:
  []
datasets:
  - "ufs-replay-dataset"
concept_slugs:
  - "correlation-aware-loss"
dataset_slugs:
  - "ufs-replay-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:05:15Z"
created_at: "2026-04-22T05:05:15Z"
---

# Skillful Global Ocean Emulation and the Role of Correlation-Aware Loss

**Authors**: Niraj Agarwal, Timothy A. Smith, Sergey Frolov, Laura C. Slivinski
**Date**: 2026-04-20
**Paper ID**: [arxiv:2604.18727](https://arxiv.org/abs/2604.18727)

## Summary

This paper introduces an ocean-specific emulator based on the GraphCast architecture, trained on the UFS-Replay dataset to provide skillful 10-15 day forecasts. By replacing Mean Squared Error with a Mahalanobis distance-based correlation-aware loss, the authors explicitly account for multivariate correlations in ocean dynamics. Experimental results demonstrate that this loss function acts as a statistical-dynamical regularizer, yielding improved forecast skill and providing higher-quality background states for data assimilation.

## Key Contributions

- Adapts the GraphCast architecture for dedicated ocean-only medium-range emulation under prescribed atmospheric conditions.
- Introduces a Mahalanobis distance-based loss function that outperforms standard MSE by capturing variable correlations.
- Demonstrates that correlation-aware loss acts as a statistical-dynamical regularizer, enhancing background forecast quality for data assimilation tasks.

## Open Questions & Future Work

- [[spatially-varying-correlation-loss-ocean-emulation]]
- [[architectural-causes-grid-imprinting-emulators]]

## Key Concepts

- [[correlation-aware-loss]]: A loss function based on the Mahalanobis distance that improves multivariate forecast skill by accounting for correlations between target variable tendencies.

## Archivist Review

I have approved the correlation-aware loss mechanism for its generalizability in multivariate forecasting and two open questions regarding regional physical realism and architectural stability (grid-locking). The UFS-Replay dataset is approved as a specific, named source crucial to the paper's claims. Other candidates were rejected to maintain the vault's high bar for novelty and impact.

### Approved Concepts
- Correlation-Aware Loss: This technique replaces standard MSE by explicitly modeling the covariance structure of target variables, which the paper proves is critical for stable ocean emulation.

### Approved Open Questions
- Spatially Varying Correlation Loss: The current use of a globally averaged correlation matrix limits the model's ability to accurately represent regional oceanic phenomena, which is critical for physical realism in data assimilation.
- Architectural Causes of Grid Imprinting: Understanding the root cause of grid-locking is essential for building stable, long-term predictive models and avoiding the need for arbitrary constraints on model inputs that may discard valuable historical information.

## Datasets

- [[ufs-replay-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.18727)
- [PDF](https://arxiv.org/pdf/2604.18727)

