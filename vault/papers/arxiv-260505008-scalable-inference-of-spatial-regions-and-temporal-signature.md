---
# CSL-compatible fields
title: "Scalable inference of spatial regions and temporal signatures from time series"
author:
  - literal: "Jiayu Weng"
  - literal: "Alec Kirkley"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.05008"

# Custom fields
paper_id: "2605.05008"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "spatial-temporal-analysis"
  - "clustering"
  - "nonparametric-methods"
  - "information-theory"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mdl-based-spatial-regionalization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:13:57Z"
created_at: "2026-05-07T05:13:57Z"
---

# Scalable inference of spatial regions and temporal signatures from time series

**Authors**: Jiayu Weng, Alec Kirkley
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.05008](https://arxiv.org/abs/2605.05008)

## Summary

This paper introduces a nonparametric framework for spatial regionalization that jointly infers contiguous spatial partitions and their representative temporal drivers from spatiotemporal datasets. By applying the minimum description length principle, the method eliminates the need for ad hoc regularization or pre-defined region counts, achieving log-linear computational efficiency. The approach is validated on both synthetic data and large-scale real-world applications in air quality and vegetation monitoring, where it effectively recovers interpretable structural patterns.

## Key Contributions

- Proposes a fully nonparametric and scalable framework for spatial regionalization of time series using the minimum description length principle.
- Enables the joint inference of contiguous spatial partitions and their representative temporal archetypes with a log-linear runtime complexity relative to the number of time series.
- Demonstrates the method's ability to extract meaningful structural regularities from large-scale air quality and vegetation index data while successfully recovering ground-truth regional structures in synthetic benchmarks.

## Open Questions & Future Work

- [[multivariate-spatiotemporal-regionalization-frameworks]]

## Key Concepts

- [[mdl-based-spatial-regionalization]]: A scalable, nonparametric framework for partitioning spatial domains into contiguous regions by jointly inferring partitions and representative time series archetypes using the minimum description length principle.

## Archivist Review

I approved the core MDL-based regionalization mechanism as it represents a novel and scalable nonparametric approach to a classic spatial time series problem. The open question on multivariate regionalization was selected because it addresses a fundamental structural limitation in current spatial partitioning methodologies. The second open question was rejected for being overly generic.

### Approved Concepts
- MDL-based Spatial Regionalization: It provides a principled, nonparametric alternative to ad hoc spatiotemporal clustering that handles large datasets efficiently.

### Approved Open Questions
- Multivariate Spatiotemporal Regionalization Frameworks: Holistic spatial analysis in environmental and social sciences requires integrating diverse, interacting indicators rather than relying on univariate signals.

### Rejected Candidates
- [open_question] Advanced Temporal Dependency Encoding (`advanced-temporal-dependency-encoding`) - low_impact: The proposal is too general and describes a broad class of problems rather than a specific, technical bottleneck that could be tracked.

## Links

- [Abstract](https://arxiv.org/abs/2605.05008)
- [PDF](https://arxiv.org/pdf/2605.05008)

