---
# CSL-compatible fields
title: "Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping"
author:
  - literal: "Ugur Demir"
  - literal: "Philipp M. Srivastava"
  - literal: "Aggelos Katsaggelos"
  - literal: "Vicky Kalogera"
  - literal: "Santiago L. Tapia"
  - literal: "Manuel Ballester"
  - literal: "Shamal Lalvani"
  - literal: "Patrick Koller"
  - literal: "Jeff J. Andrews"
  - literal: "Seth Gossage"
  - literal: "Max M. Briel"
  - literal: "Elizabeth Teng"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13604"

# Custom fields
paper_id: "2604.13604"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "interpolation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "joint-alignment-track-averaging"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:06:38Z"
created_at: "2026-04-16T05:06:38Z"
---

# Irregularly Sampled Time Series Interpolation for Binary Evolution Simulations Using Dynamic Time Warping

**Authors**: Ugur Demir, Philipp M. Srivastava, Aggelos Katsaggelos, Vicky Kalogera, Santiago L. Tapia, Manuel Ballester, Shamal Lalvani, Patrick Koller, Jeff J. Andrews, Seth Gossage, Max M. Briel, Elizabeth Teng
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13604](https://arxiv.org/abs/2604.13604)

## Summary

This paper addresses the difficulty of interpolating binary stellar evolution tracks, which are often irregularly sampled and feature discontinuities from mutual interactions. The authors introduce a novel approach using Dynamic Time Warping (DTW) to compute a single, shared warping path across multiple physical parameters, ensuring consistent temporal alignment. This joint-alignment strategy preserves causal physical relationships, such as the Stefan-Boltzmann law, within interpolated tracks. The method provides a scalable solution for efficiently generating large binary population samples for astrophysical research.

## Key Contributions

- Proposes a novel track alignment and iterative averaging method using Dynamic Time Warping (DTW) to handle irregularly sampled binary stellar evolution tracks.
- Introduces a joint-alignment strategy that computes a shared warping path across multiple parameters, preserving critical physical relationships such as the Stefan-Boltzmann law.
- Demonstrates that the proposed method consistently outperforms existing interpolation approaches in generating accurate binary population samples for astrophysical simulations.

## Open Questions & Future Work

- [[morphologically-informed-neighbor-selection]]

## Key Concepts

- [[joint-alignment-track-averaging]]: A Dynamic Time Warping-based method that aligns multiple physical parameters of evolution tracks onto a shared, consistent temporal grid.

## Archivist Review

The paper introduces a reusable approach for multivariate time series alignment using Dynamic Time Warping to maintain physical consistency during interpolation, which is approved as a concept. The open question regarding neighbor selection in parameter spaces with high sensitivity is approved as it addresses a core limitation in interpolation-based surrogate modeling. No datasets were approved as they were not specified.

### Approved Concepts
- Joint-Alignment Track Averaging: It enables meaningful interpolation of complex, irregularly sampled physical tracks where traditional alignment fails to preserve causal relations.

### Approved Open Questions
- Morphologically Informed Neighbor Selection: This is a fundamental bottleneck for interpolation accuracy in sparse or highly non-linear regions of the parameter space, directly impacting the reliability of large-scale population synthesis studies.

## Links

- [Abstract](https://arxiv.org/abs/2604.13604)
- [PDF](https://arxiv.org/pdf/2604.13604)

