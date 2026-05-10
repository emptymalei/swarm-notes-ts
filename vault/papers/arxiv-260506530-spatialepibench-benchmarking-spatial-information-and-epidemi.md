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
  - "spatio-temporal"
  - "public-health"
architectures:
  []
datasets:
  - "spatialepibench"
concept_slugs:
  - "spatialepibench"
dataset_slugs:
  - "spatialepibench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:18:12Z"
created_at: "2026-05-10T05:18:12Z"
---

# SpatialEpiBench: Benchmarking Spatial Information and Epidemic Priors in Forecasting

**Authors**: Ruiqi Lyu, Alistair Turcan, Bryan Wilder
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06530](https://arxiv.org/abs/2605.06530)

## Summary

SpatialEpiBench addresses the lack of standardized, realistic evaluation frameworks in epidemic forecasting by introducing a comprehensive benchmark suite of 11 spatiotemporal datasets. By implementing rolling evaluation protocols and outbreak-specific metrics, the authors demonstrate that current models often struggle to outperform simple last-value baselines. Their analysis reveals significant limitations in existing approaches regarding outbreak anticipation, data robustness, and the efficacy of standard geographic adjacency priors. This work provides an essential resource for developing more operationally relevant and reliable public health forecasting tools.

## Key Contributions

- Introduces SpatialEpiBench, a comprehensive benchmark for spatiotemporal epidemic forecasting featuring 11 standardized datasets.
- Implements rolling evaluation protocols and outbreak-specific metrics to better mirror real-time public health forecasting requirements.
- Reveals that existing adjacency-informed models and epidemic priors consistently underperform simple last-value baselines across 1-day to 1-month horizons.
- Identifies three critical failure modes in current models: poor outbreak anticipation, limited robustness to data sparsity/noise, and weak utility of geographic adjacency for epidemiology.

## Open Questions & Future Work

- [[limitations-of-geographic-adjacency]]

## Key Concepts

- [[spatialepibench]]: A standardized benchmark for spatiotemporal epidemic forecasting designed to reflect realistic public-health evaluation practices.

## Archivist Review

SpatialEpiBench is approved as it addresses a significant gap in the standardization of epidemic forecasting evaluations. The open question regarding the utility of geographic adjacency is approved because it articulates a fundamental structural bottleneck identified by the authors that challenges the status quo in the field. Other components were kept concise in alignment with the strict archival policy.

### Approved Concepts
- SpatialEpiBench: Provides a standardized, realistic evaluation framework for epidemic forecasting, addressing the lack of real-time practice alignment in existing literature.

### Approved Open Questions
- Efficacy of geographic adjacency: Identifying the correct structural priors is a fundamental bottleneck in spatiotemporal epidemic forecasting, as current reliance on geographic adjacency fails to yield performance gains over univariate models.

## Datasets

- [[spatialepibench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.06530)
- [PDF](https://arxiv.org/pdf/2605.06530)

