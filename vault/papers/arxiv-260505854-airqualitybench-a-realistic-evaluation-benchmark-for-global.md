---
# CSL-compatible fields
title: "AirQualityBench: A Realistic Evaluation Benchmark for Global Air Quality Forecasting"
author:
  - literal: "Xing Xu"
  - literal: "Xu Wang"
  - literal: "Yudong Zhang"
  - literal: "Huilin Zhao"
  - literal: "Zhengyang Zhou"
  - literal: "Yang Wang"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05854"

# Custom fields
paper_id: "2605.05854"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "AirQualityBench"
concept_slugs:
  - "airqualitybench"
dataset_slugs:
  - "airqualitybench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:20:15Z"
created_at: "2026-05-10T05:20:15Z"
---

# AirQualityBench: A Realistic Evaluation Benchmark for Global Air Quality Forecasting

**Authors**: Xing Xu, Xu Wang, Yudong Zhang, Huilin Zhao, Zhengyang Zhou, Yang Wang
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05854](https://arxiv.org/abs/2605.05854)

## Summary

AirQualityBench is a new, realistic benchmark for global air-quality forecasting that addresses the limitations of existing datasets by preserving structured missingness and heterogeneous pollutant scales. Unlike conventional benchmarks that use imputed, sanitized data, this testbed requires models to operate on native observation masks and report results in physical concentration units. The study demonstrates that high performance on cleaned datasets often fails to generalize to the fragmented and uneven monitoring networks encountered in real-world deployment. This work provides a critical resource for developing scalable and mask-aware forecasting models.

## Key Contributions

- Introduces AirQualityBench, a global multi-pollutant benchmark with 3,720 stations over 2021-2025, to address gaps in evaluating air-quality forecasting models.
- Enforces a unified evaluation protocol that mandates the handling of provider-native observation masks and avoids dense tensor imputation.
- Demonstrates through empirical evaluation that existing spatio-temporal models often struggle to maintain performance when transitioning from sanitized to fragmented, real-world monitoring streams.

## Open Questions & Future Work

- [[region-stratified-evaluation]]

## Key Concepts

- [[airqualitybench]]: A global multi-pollutant benchmark for air quality forecasting that emphasizes realistic evaluation protocols including structured missingness and native observation masks.

## Archivist Review

I approved AirQualityBench as a concept and dataset because it formalizes a standard for realistic evaluation in time-series forecasting, specifically moving beyond sanitized imputation. I also approved the region-stratified evaluation question, as it targets a significant gap in spatio-temporal modeling where data scarcity biases research toward affluent, high-sensor regions. I rejected the physical-scale unit harmonization question as it is a specific data-engineering requirement rather than a broad, reusable research problem.

### Approved Concepts
- AirQualityBench: Establishes a new standard for evaluating air quality forecasting models by emphasizing realistic data characteristics such as structured missingness and heterogeneous scales.

### Approved Open Questions
- Region-Stratified Evaluation Tracks: Addressing spatial bias is critical for ensuring that air-quality forecasting models perform reliably across the globe rather than only in data-rich urban centers.

### Rejected Candidates
- [open_question] Physical-Scale Unit Harmonization (`physical-unit-harmonization`) - low_impact: This describes a data-cleaning task rather than a foundational research bottleneck.

## Datasets

- [[airqualitybench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.05854)
- [PDF](https://arxiv.org/pdf/2605.05854)

