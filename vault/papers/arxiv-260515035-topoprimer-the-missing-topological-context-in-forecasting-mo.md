---
# CSL-compatible fields
title: "TopoPrimer: The Missing Topological Context in Forecasting Models"
author:
  - literal: "Zara Zetlin"
  - literal: "Kayhan Moharreri"
  - literal: "Maria Safi"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15035"

# Custom fields
paper_id: "2605.15035"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series"
  - "topological-data-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "topoprimer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:11:07Z"
created_at: "2026-05-16T05:11:07Z"
---

# TopoPrimer: The Missing Topological Context in Forecasting Models

**Authors**: Zara Zetlin, Kayhan Moharreri, Maria Safi
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15035](https://arxiv.org/abs/2605.15035)

## Summary

TopoPrimer is a topological augmentation framework that injects global structural context into time-series forecasting models. By utilizing persistent homology and spectral sheaf coordinates, the approach provides per-token features for trained models or lightweight adapters for pre-trained backbones. Experimental results show significant improvements in forecasting accuracy across Chronos and TimesFM architectures, particularly during high-volatility seasonal spikes and cold-start scenarios.

## Key Contributions

- Introduces TopoPrimer, a framework that integrates global topological structure into time-series forecasting via persistent homology and spectral sheaf coordinates.
- Achieves significant accuracy improvements on public benchmarks, specifically yielding a 7.3% MSE reduction on the ECL dataset.
- Demonstrates strong robustness in difficult regimes, maintaining performance within 10% under peak seasonal demand and reducing cold-start MAE by 27%.

## Open Questions & Future Work

- [[learned-topological-filtration-metric]]
- [[multi-parameter-persistent-homology]]

## Key Concepts

- [[topoprimer]]: A framework that incorporates global topological structure into forecasting models as explicit inputs to improve accuracy and cold-start performance.

## Archivist Review

TopoPrimer was approved as a model-agnostic topological augmentation framework suitable for various forecasting backbones. I approved two open questions concerning the advancement of TDA metrics and persistent homology methods, as these represent substantial research bottlenecks. The ECL dataset was rejected as it is a standard, widely used benchmark in time-series forecasting.

### Approved Concepts
- TopoPrimer: Introduces a model-agnostic framework for augmenting forecasting models with global topological features via persistent homology and spectral sheaf coordinates.

### Approved Open Questions
- Learned Topological Filtration Metrics: Determining the optimal metric for TDA is a fundamental bottleneck, as the choice of metric currently bounds the quality and expressiveness of the topological representation.
- Multi-parameter Persistent Homology: Multi-parameter persistence potentially offers a more expressive characterization of population manifolds critical for forecasting performance in volatile regimes.

### Rejected Candidates
- [dataset] ECL (`ecl`) - not_novel: ECL is a widely used benchmark dataset already well-documented in time-series literature.

## Links

- [Abstract](https://arxiv.org/abs/2605.15035)
- [PDF](https://arxiv.org/pdf/2605.15035)

