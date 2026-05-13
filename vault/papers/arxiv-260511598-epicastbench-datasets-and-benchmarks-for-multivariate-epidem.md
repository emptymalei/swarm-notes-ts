---
# CSL-compatible fields
title: "EpiCastBench: Datasets and Benchmarks for Multivariate Epidemic Forecasting"
author:
  - literal: "Madhurima Panja"
  - literal: "Danny D'Agostino"
  - literal: "Huitao Li, Tanujit Chakraborty"
  - literal: "Nan Liu"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11598"

# Custom fields
paper_id: "2605.11598"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "EpiCastBench"
concept_slugs:
  - "epicastbench"
dataset_slugs:
  - "epicastbench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:25:12Z"
created_at: "2026-05-13T05:25:12Z"
---

# EpiCastBench: Datasets and Benchmarks for Multivariate Epidemic Forecasting

**Authors**: Madhurima Panja, Danny D'Agostino, Huitao Li, Tanujit Chakraborty, Nan Liu
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11598](https://arxiv.org/abs/2605.11598)

## Summary

EpiCastBench addresses the critical lack of standardized evaluation frameworks in multivariate epidemic forecasting by providing 40 curated datasets with diverse temporal and structural characteristics. The framework facilitates fair comparison through a unified benchmarking environment that includes standardized preprocessing, forecasting horizons, and statistical significance testing. By evaluating 15 state-of-the-art models, the authors establish a rigorous baseline for future research in data-driven public health decision-making.

## Key Contributions

- Introduces EpiCastBench, a large-scale benchmarking framework containing 40 correlated multivariate epidemic datasets across various infectious diseases and geographic regions.
- Provides a standardized evaluation infrastructure including consistent preprocessing, unified forecasting horizons, and rigorous statistical significance testing.
- Conducts a comprehensive benchmark analysis of 15 multivariate models, ranging from traditional statistical baselines to modern deep learning and foundation models.

## Open Questions & Future Work

- [[zero-inflation-epidemic-forecasting]]
- [[spatiotemporal-epidemic-modeling]]

## Key Concepts

- [[epicastbench]]: A large-scale benchmarking framework for multivariate epidemic forecasting comprising 40 curated datasets, standardized evaluation protocols, and performance metrics.

## Archivist Review

I approved the benchmark framework and the most critical methodological bottlenecks identified. The concept and dataset are canonical for the domain, while the open questions target the specific structural limitations of purely temporal models in epidemiology (zero-inflation and lack of spatial awareness). Other open questions were rejected as being either broader than this specific paper's focus or less critical than the ones selected.

### Approved Concepts
- EpiCastBench: It provides the first large-scale, standardized benchmarking framework specifically for multivariate epidemic forecasting across diverse diseases and regions.

### Approved Open Questions
- Addressing zero-inflation in forecasting: Addressing zero-inflation is critical for moving beyond simple univariate models to reliable multivariate forecasting in public health.
- Spatiotemporal epidemic forecasting frameworks: Spatiotemporal modeling is essential for accurately capturing the real-world propagation of epidemics between interconnected geographical units.

## Datasets

- [[epicastbench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.11598)
- [PDF](https://arxiv.org/pdf/2605.11598)

