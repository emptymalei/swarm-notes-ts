---
# CSL-compatible fields
title: "Nonlinear Methods for Analyzing Pose in Behavioral Research"
author:
  - literal: "Carter Sale"
  - literal: "Margaret C. Macpherson"
  - literal: "Gaurav Patil"
  - literal: "Kelly Miles"
  - literal: "Rachel W. Kallen"
  - literal: "Sebastian Wallot"
  - literal: "Michael J. Richardson"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01453"

# Custom fields
paper_id: "2604.01453"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:20:50Z"
created_at: "2026-04-03T05:20:50Z"
---

# Nonlinear Methods for Analyzing Pose in Behavioral Research

**Authors**: Carter Sale, Margaret C. Macpherson, Gaurav Patil, Kelly Miles, Rachel W. Kallen, Sebastian Wallot, Michael J. Richardson
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01453](https://arxiv.org/abs/2604.01453)

## Summary

This paper introduces a systematic analysis pipeline designed to address the challenges of high-dimensional and noisy data produced by modern markerless pose estimation systems. By combining dimensionality reduction with recurrence-based time series analysis, the framework provides a robust method for quantifying temporal structure and coordination in human behavior. The authors demonstrate the versatility of this approach through three distinct case studies involving facial and full-body movement across various social configurations. This work bridges the gap between raw video-based pose extraction and the high-level behavioral dynamics required for meaningful cognitive and behavioral research.

## Key Contributions

- Introduces a comprehensive analysis pipeline for human pose data that integrates principled preprocessing, dimensionality reduction, and recurrence-based analysis.
- Demonstrates the pipeline's utility in quantifying temporal coordination and movement dynamics across diverse experimental settings, including facial/full-body movement and individual/multi-agent behaviors.
- Provides a unified workflow for transitioning from noisy, high-dimensional markerless pose estimations to theoretically grounded behavioral metrics.

## Open Questions & Future Work

- [[pose-estimation-architecture-noise-profiles]]
- [[mdrqa-scalability-limits]]

## Archivist Review

The paper describes an applied workflow rather than introducing a novel foundational concept in time series analysis; thus, no new concepts were approved. However, the identified open questions address significant, generalizable bottlenecks regarding the noise characteristics of upstream pose models and the computational scalability of Recurrence Quantification Analysis, which are highly relevant for the behavioral time series research community.

### Approved Open Questions
- Model-specific noise profiling: Different error profiles across algorithms pose a major bottleneck for the generalizability of preprocessing pipelines, as optimal cleaning and interpolation methods likely depend on the specific structural nature of the upstream tracking artifacts.
- Scaling MdRQA for complexity: The current lack of principled, automated feature-selection methods for high-dimensional MdRQA creates a barrier for analyzing complex multi-agent or whole-body interactions where collective patterns are non-reducible to pairwise couplings.

## Links

- [Abstract](https://arxiv.org/abs/2604.01453)
- [PDF](https://arxiv.org/pdf/2604.01453)

