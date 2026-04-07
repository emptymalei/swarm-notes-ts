---
# CSL-compatible fields
title: "Spherically Embedded Time Series with Unknown Trend and Periodic Components"
author:
  - literal: "Jiazhen Xu"
  - literal: "Han Lin Shang"
issued:
  date-parts:
    - [2026, 4, 4]
url: "https://arxiv.org/abs/2604.03574"

# Custom fields
paper_id: "2604.03574"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "trend-periodic-spherical-autoregressive-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:55:38Z"
created_at: "2026-04-07T04:55:38Z"
---

# Spherically Embedded Time Series with Unknown Trend and Periodic Components

**Authors**: Jiazhen Xu, Han Lin Shang
**Date**: 2026-04-04
**Paper ID**: [arxiv:2604.03574](https://arxiv.org/abs/2604.03574)

## Summary

This paper introduces a geometric framework to model nonstationary time series constrained to spherical manifolds, where traditional Euclidean methods fail. The authors propose a novel decomposition approach using optimal transport to isolate smooth trends and periodic components while preserving spherical structure, followed by a spherical autoregressive model for residuals. Theoretical consistency and superior empirical forecasting performance are demonstrated, providing a robust tool for analyzing complex directional time series data.

## Key Contributions

- Introduces a unified geometric framework for nonstationary spherically embedded time series analysis.
- Proposes a nonparametric trend-periodicity decomposition model utilizing an optimal-transport-based removal operation to maintain spherical topology.
- Establishes a trend-periodic spherical autoregressive (TPSAR) model with theoretical consistency proofs under temporal dependence.
- Demonstrates improved forecasting performance and interpretability on electricity generation and bike trip volume data compared to traditional Euclidean methods.

## Open Questions & Future Work

- [[long-memory-residual-stationary-assumption]]
- [[general-random-object-decomposition]]

## Key Concepts

- [[trend-periodic-spherical-autoregressive-model]]: A geometric time series model that uses optimal-transport-based decomposition to extract trend and seasonality from spherically constrained data before applying autoregressive modeling.

## Archivist Review

I have approved the core Trend-Periodic Spherical Autoregressive Model as a novel geometric approach to non-Euclidean time series, along with two open questions regarding the generalization of this decomposition to more complex residual structures and non-Euclidean objects. The selection focuses on reusable methodologies rather than the specific applications provided in the paper.

### Approved Concepts
- Trend-Periodic Spherical Autoregressive Model: Provides a unified framework for decomposing and forecasting nonstationary spherical time series by handling latent trends and periodic components while respecting spherical geometry.

### Approved Open Questions
- Long-memory residual time series: Addressing non-stationarity beyond simple trend and periodicity is necessary for broader applicability to real-world time series.
- Decomposition of general random objects: This would broaden the scope of structural decomposition techniques to a wider variety of non-Euclidean data types prevalent in modern data analysis.

## Links

- [Abstract](https://arxiv.org/abs/2604.03574)
- [PDF](https://arxiv.org/pdf/2604.03574)

