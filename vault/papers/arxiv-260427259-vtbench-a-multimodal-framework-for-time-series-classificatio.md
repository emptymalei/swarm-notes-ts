---
# CSL-compatible fields
title: "VTBench: A Multimodal Framework for Time-Series Classification with Chart-Based Representations"
author:
  - literal: "Madhumitha Venkatesan"
  - literal: "Xuyang Chen"
  - literal: "Dongyu Liu"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.27259"

# Custom fields
paper_id: "2604.27259"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "vtbench"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:23:49Z"
created_at: "2026-05-01T05:23:49Z"
---

# VTBench: A Multimodal Framework for Time-Series Classification with Chart-Based Representations

**Authors**: Madhumitha Venkatesan, Xuyang Chen, Dongyu Liu
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27259](https://arxiv.org/abs/2604.27259)

## Summary

VTBench addresses the under-exploration of chart-based representations in time-series classification by creating a modular framework for fusing raw sequences with various plot types (line, area, bar, scatter). The framework supports diverse fusion strategies, ranging from single-chart to full multimodal integration, allowing for a nuanced analysis of visual feature utility. Experiments across the UCR repository reveal that chart-based visual features provide significant value in data-constrained settings and offer complementary cues that enhance classification performance.

## Key Contributions

- Introduces VTBench, a systematic framework for multimodal time-series classification using both raw numerical data and human-interpretable chart representations.
- Demonstrates that multi-chart visual fusion captures complementary temporal cues, often improving accuracy over single-modality baselines.
- Provides empirically-derived guidelines for selecting optimal chart types and fusion strategies, showing that visual representations are particularly competitive on smaller datasets.

## Open Questions & Future Work

- [[adaptive-multimodal-time-series-representation]]

## Key Concepts

- [[vtbench]]: A modular framework for multimodal time-series classification that integrates raw numerical sequences with interpretable chart-based visual representations.

## Archivist Review

I have approved VTBench as a foundational concept for multimodal time-series representation and the corresponding open question regarding adaptive multimodal selection. I rejected the UCR Archive as it is a widely-used benchmark dataset and lacks the novelty required for a standalone vault entry. The review adhered to the policy of focusing on reusable mechanisms and substantial unresolved research bottlenecks.

### Approved Concepts
- VTBench: It provides a systematic framework for multimodal time-series classification using both raw numerical data and human-interpretable chart representations, establishing a benchmark for visual encoding utility.

### Approved Open Questions
- Adaptive Multimodal Time-Series Representation: Enabling models to automatically optimize for the most discriminative representations is crucial for efficiency and robustness in multimodal TSC applications.

### Rejected Candidates
- [dataset] UCR Archive (`ucr-archive`) - not_novel: The UCR Archive is a routine, well-established benchmark suite and does not require a standalone note in the knowledge vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.27259)
- [PDF](https://arxiv.org/pdf/2604.27259)

