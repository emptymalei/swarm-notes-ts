---
# CSL-compatible fields
title: "Detection and Mode-Identification of Multiple Change Points in Tensor Factor Models"
author:
  - literal: "Yuqi Zhang"
  - literal: "Zetai Cen"
  - literal: "Haeran Cho"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11300"

# Custom fields
paper_id: "2604.11300"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "dimensionality-reduction"
  - "statistical-inference"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mode-identifiable-tensor-structural-shifts"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:03:23Z"
created_at: "2026-04-14T05:03:23Z"
---

# Detection and Mode-Identification of Multiple Change Points in Tensor Factor Models

**Authors**: Yuqi Zhang, Zetai Cen, Haeran Cho
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11300](https://arxiv.org/abs/2604.11300)

## Summary

This paper addresses structural change point detection in high-dimensional tensor-valued time series modeled via Tucker decomposition. The authors introduce a two-stage approach: first, a change point detection algorithm that utilizes low-rank structure for computational efficiency, and second, a method for identifying the specific modes associated with each structural break. They prove consistency for these methods under weak moment conditions and validate the approach through simulation studies and analyses of NYC taxi usage and Fama-French portfolio returns.

## Key Contributions

- Proposes an efficient multi-change point detection algorithm for tensor-valued time series leveraging Tucker decomposition.
- Introduces a mode-identification procedure to pinpoint which specific tensor modes contribute to a detected structural break.
- Establishes consistency for both detection and identification under weak moment conditions, demonstrating improved loading space estimation performance.

## Key Concepts

- [[mode-identifiable-tensor-structural-shifts]]: A statistical framework for localizing structural changes to specific modes in high-dimensional tensor factor models post-segmentation.

## Archivist Review

I approved the core concept of mode-identifiable structural shifts as it provides a robust, reusable statistical framework for interpreting change points in high-dimensional tensor factor models. This approach distinguishes between global and mode-specific shifts, which is essential for diagnosing non-stationarity in structured, multi-dimensional time-series data. I rejected no candidates as none were provided, and the concept itself is sufficiently distinct and important for the knowledge vault.

### Approved Concepts
- Mode-identifiable Tensor Structural Shifts: Provides a formal framework to localize structural breaks to specific dimensions in tensor-valued time series, addressing the high-dimensional challenge of partial mode shifts.

## Links

- [Abstract](https://arxiv.org/abs/2604.11300)
- [PDF](https://arxiv.org/pdf/2604.11300)

