---
# CSL-compatible fields
title: "SpatialEpiBench: Benchmarking Spatial Information and Epidemic Priors in Forecasting"
author:
  - literal: "Ruiqi Lyu"
  - literal: "Alistair Turcan"
  - literal: "Bryan Wilder"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06530"

# Custom fields
paper_id: "2605.06530"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "epidemiology"
  - "spatiotemporal-forecasting"
  - "benchmarking"
architectures:
  []
datasets:
  - "spatialepibench-suite"
concept_slugs:
  - "spatialepibench"
dataset_slugs:
  - "spatialepibench-suite"
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:10:02Z"
created_at: "2026-05-09T05:10:02Z"
---

# SpatialEpiBench: Benchmarking Spatial Information and Epidemic Priors in Forecasting

**Authors**: Ruiqi Lyu, Alistair Turcan, Bryan Wilder
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06530](https://arxiv.org/abs/2605.06530)

## Summary

SpatialEpiBench addresses the lack of standardized evaluation frameworks in spatiotemporal epidemic forecasting by providing 11 curated datasets and rigorous rolling evaluation protocols. The paper benchmarks various adjacency-informed models and identifies that most fail to outperform basic persistence models, regardless of the epidemic prior used. The findings reveal critical deficiencies in existing models regarding outbreak anticipation, noise resilience, and the representation of epidemiological spatial interactions.

## Key Contributions

- Introduces SpatialEpiBench, a standardized benchmark suite comprising 11 epidemic datasets with rolling evaluation protocols and outbreak-specific metrics.
- Demonstrates that current state-of-the-art adjacency-informed models often fail to outperform naive last-value baselines across varying forecasting horizons.
- Identifies three core systemic failure modes in modern spatiotemporal models: poor outbreak anticipation, limited robustness to data noise, and the inadequacy of standard geographic adjacency priors.

## Open Questions & Future Work

- [[geographic-adjacency-epidemic-forecasting-utility]]

## Key Concepts

- [[spatialepibench]]: A comprehensive benchmark for spatiotemporal epidemic forecasting that employs standardized rolling evaluations and outbreak-specific metrics.

## Archivist Review

I have approved the SpatialEpiBench concept and the dataset suite to provide a necessary foundation for evaluating epidemic forecasting models, as these are critical for standardizing evaluation in a field where ad-hoc practices dominate. The open question on geographic adjacency was approved because it addresses a fundamental, domain-specific challenge revealed by the benchmark's performance analysis, namely the disconnect between architectural spatial priors and actual disease transmission dynamics. I applied a strict filter to ensure only the core benchmarking suite and the central open research question were retained.

### Approved Concepts
- SpatialEpiBench: It provides a standardized benchmark suite and protocol for an area of epidemic forecasting that has historically relied on ad-hoc evaluation, revealing foundational performance gaps in existing spatiotemporal models.

### Approved Open Questions
- Utility of Geographic Adjacency: Understanding the utility of spatial priors is fundamental to the design of spatiotemporal models in public health, as the current reliance on geographic adjacency may be a limiting factor in predictive accuracy.

## Datasets

- [[spatialepibench-suite]]

## Links

- [Abstract](https://arxiv.org/abs/2605.06530)
- [PDF](https://arxiv.org/pdf/2605.06530)

