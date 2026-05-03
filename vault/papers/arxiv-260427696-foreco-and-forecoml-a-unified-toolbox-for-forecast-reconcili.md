---
# CSL-compatible fields
title: "FoReco and FoRecoML: A Unified Toolbox for Forecast Reconciliation in R"
author:
  - literal: "Daniele Girolimetto"
  - literal: "Jeroen Rombouts"
  - literal: "Ines Wilms"
  - literal: "Yangzhuoran Fin Yang"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27696"

# Custom fields
paper_id: "2604.27696"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "forecast-reconciliation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:14:56Z"
created_at: "2026-05-03T05:14:56Z"
---

# FoReco and FoRecoML: A Unified Toolbox for Forecast Reconciliation in R

**Authors**: Daniele Girolimetto, Jeroen Rombouts, Ines Wilms, Yangzhuoran Fin Yang
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27696](https://arxiv.org/abs/2604.27696)

## Summary

This paper introduces FoReco and FoRecoML, two R packages designed to unify the implementation of forecast reconciliation for linearly constrained time series. While FoReco focuses on classical statistical and regression-based linear methods, FoRecoML extends these capabilities to non-linear reconciliation using machine learning. The framework covers cross-sectional, temporal, and cross-temporal reconciliation tasks, providing both ease-of-use for practitioners and high-level customization for researchers.

## Key Contributions

- Introduces FoReco and FoRecoML, R packages providing a unified framework for cross-sectional, temporal, and cross-temporal forecast reconciliation.
- FoReco implements classical statistical and regression-based linear reconciliation techniques for constrained time series.
- FoRecoML integrates non-linear, machine-learning-based reconciliation methods for hierarchical and grouped forecasting structures.

## Key Concepts

- [[forecast-reconciliation]]: The process of adjusting base forecasts for linearly constrained time series to ensure they satisfy hierarchical or grouping consistency.

## Archivist Review

I have approved 'Forecast Reconciliation' as it is the central concept of the paper and a fundamental problem in multivariate time series forecasting. I rejected the R packages as candidates because software toolboxes are not reusable conceptual primitives for the knowledge vault. No other candidates were provided, so the vault remains stable.

### Approved Concepts
- Forecast Reconciliation: Central to the paper's focus on unifying software for coherent hierarchical and grouped time series forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2604.27696)
- [PDF](https://arxiv.org/pdf/2604.27696)

