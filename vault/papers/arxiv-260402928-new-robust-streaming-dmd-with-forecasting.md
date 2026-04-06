---
# CSL-compatible fields
title: "New Robust Streaming DMD with Forecasting"
author:
  - literal: "Zlatko Drmač"
  - literal: "Ela Đimoti"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.02928"

# Custom fields
paper_id: "2604.02928"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "streaming-dynamic-mode-decomposition"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-06T05:02:24Z"
created_at: "2026-04-06T05:02:24Z"
---

# New Robust Streaming DMD with Forecasting

**Authors**: Zlatko Drmač, Ela Đimoti
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.02928](https://arxiv.org/abs/2604.02928)

## Summary

This paper presents a refined approach to streaming Dynamic Mode Decomposition (DMD), targeting high-dimensional dynamical systems. By revisiting and optimizing existing streaming DMD frameworks, the authors improve the numerical stability, computational efficiency, and memory requirements of the decomposition process. The proposed method utilizes residual bounds and exact DMD vectors to enhance spectral extraction and forecasting accuracy in online, data-driven settings.

## Key Contributions

- Introduces an improved streaming Dynamic Mode Decomposition (DMD) algorithm with enhanced computational efficiency and a reduced memory footprint.
- Improves numerical robustness of the DMD matrix updates by optimizing condition numbers, facilitating more reliable spectral analysis of Koopman operators.
- Enhances forecasting skill in online applications through the integration of residual bounds and exact DMD vectors within the streaming update process.

## Open Questions & Future Work

- [[streaming-dmd-data-forgetting]]

## Key Concepts

- [[streaming-dynamic-mode-decomposition]]: An adaptive numerical method for extracting spectral information and forecasting from high-dimensional dynamical systems by processing data snapshots in a streaming, memory-efficient manner.

## Archivist Review

I approved the core concept of streaming DMD as it is a well-established foundational technique for data-driven dynamical systems analysis that is highly relevant to time-series forecasting. The open question regarding data forgetting addresses a critical limitation in current low-memory, streaming compression techniques, representing a substantial research bottleneck. No other candidates were provided, and I refrained from inventing new ones.

### Approved Concepts
- Streaming Dynamic Mode Decomposition: DMD is a fundamental tool for data-driven spectral analysis of dynamical systems, and the ability to perform it in a streaming, low-rank fashion is central to scalability in high-dimensional forecasting applications.

### Approved Open Questions
- Data Forgetting in Streaming DMD: Effective forgetting is essential for maintaining model performance in non-stationary environments where system dynamics drift over time.

## Links

- [Abstract](https://arxiv.org/abs/2604.02928)
- [PDF](https://arxiv.org/pdf/2604.02928)

