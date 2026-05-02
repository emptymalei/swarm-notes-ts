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
processed_at: "2026-05-02T05:08:53Z"
created_at: "2026-05-02T05:08:53Z"
---

# VTBench: A Multimodal Framework for Time-Series Classification with Chart-Based Representations

**Authors**: Madhumitha Venkatesan, Xuyang Chen, Dongyu Liu
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27259](https://arxiv.org/abs/2604.27259)

## Summary

VTBench is a multimodal framework for time-series classification (TSC) that bridges the gap between raw numerical data and interpretable chart-based representations. By generating diverse visual encodings—including line, area, bar, and scatter plots—it enables flexible fusion strategies to capture complementary signal characteristics. The framework provides a systematic approach for evaluating these visual features across different datasets, ultimately offering practical guidelines for selecting optimal fusion configurations. Experiments on 31 UCR datasets validate that combining chart modalities with raw data can enhance performance, provided the visual features introduce non-redundant information.

## Key Contributions

- Introduces VTBench, a systematic framework for multimodal time-series classification that fuses raw numerical data with diverse chart-based visual representations.
- Demonstrates through empirical evaluation on 31 UCR datasets that chart-based modalities can provide complementary cues to improve classification accuracy, especially on smaller datasets.
- Identifies the performance trade-offs of visual-numerical fusion, noting that effectiveness depends on the non-redundancy of the visual features provided.

## Open Questions & Future Work

- [[adaptive-chart-selection-and-multimodal-fusion]]

## Key Concepts

- [[vtbench]]: A multimodal framework for time-series classification that fuses raw numerical sequences with interpretable chart-based visualizations.

## Archivist Review

VTBench provides a useful, systematic framework for the under-explored area of using standard visualization techniques as temporal representations for TSC. I approved the framework and the open question regarding adaptive multimodal fusion strategies, as these represent a reusable approach and a substantial bottleneck in the field. I rejected the UCR datasets as they are an aggregate benchmark repository rather than a novel or highly specific standalone dataset.

### Approved Concepts
- VTBench: The framework introduces a novel approach to TSC by systematically exploring chart-based visualizations as complementary input modalities to raw numerical data.

### Approved Open Questions
- Adaptive Chart Selection and Multimodal Fusion Strategies: Current multimodal fusion approaches often rely on fixed strategies that may not account for task-specific noise or redundancy, leading to inconsistent performance. Developing adaptive, data-driven frameworks for chart selection and fusion is essential to achieve robust and scalable multimodal time-series classification.

## Links

- [Abstract](https://arxiv.org/abs/2604.27259)
- [PDF](https://arxiv.org/pdf/2604.27259)

