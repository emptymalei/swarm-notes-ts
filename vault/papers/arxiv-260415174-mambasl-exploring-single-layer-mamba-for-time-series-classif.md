---
# CSL-compatible fields
title: "MambaSL: Exploring Single-Layer Mamba for Time Series Classification"
author:
  - literal: "Yoo-Min Jung"
  - literal: "Leekyung Kim"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.15174"

# Custom fields
paper_id: "2604.15174"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "classification"
  - "state-space-models"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:04:55Z"
created_at: "2026-04-17T05:04:55Z"
---

# MambaSL: Exploring Single-Layer Mamba for Time Series Classification

**Authors**: Yoo-Min Jung, Leekyung Kim
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.15174](https://arxiv.org/abs/2604.15174)

## Summary

MambaSL explores the potential of state space models (SSMs) for time series classification by introducing a streamlined, single-layer Mamba architecture. The authors systematically refine projection and selection mechanisms based on TSC-specific hypotheses to optimize performance. To address evaluation inconsistencies in the field, they establish a unified benchmark protocol covering all 30 UEA datasets and provide public checkpoints for all baselines. The resulting architecture outperforms strong alternatives, establishing single-layer Mamba as a viable, high-performance backbone for time series tasks.

## Key Contributions

- Introduces MambaSL, a single-layer selective state space model framework specifically optimized for time series classification (TSC).
- Performs a comprehensive re-evaluation of 20 existing baselines across the complete 30-dataset UEA suite using a unified, reproducible experimental protocol.
- Demonstrates that MambaSL achieves state-of-the-art performance on TSC benchmarks while maintaining significantly higher efficiency through architectural minimalism.

## Open Questions & Future Work

- [[mamba-standalone-tsc-capacity]]

## Archivist Review

The paper focuses on empirical TSC benchmarking and architectural streamlining of Mamba. Most candidates provided were either roadmap-style future work or lacked generalizable conceptual depth. I approved the question regarding Mamba's standalone TSC capacity as it addresses a fundamental, field-wide challenge in evaluating the intrinsic value of new neural architectures versus hybrid engineering.

### Approved Open Questions
- Standalone Mamba TSC Capacity: It is crucial to determine if SSMs are viable backbones on their own merits rather than through hybrid feature-engineering pipelines.

### Rejected Candidates
- [open_question] Modular Time-Variance in Mamba-2 (`modularizing-time-variance-mamba2`) - low_impact: This is a technology-specific, roadmap-style question that does not identify a fundamental theoretical or methodological bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.15174)
- [PDF](https://arxiv.org/pdf/2604.15174)

