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
  - "time-series-forecasting"
  - "spatio-temporal-forecasting"
  - "benchmark-dataset"
architectures:
  []
datasets:
  - "airqualitybench"
concept_slugs:
  - "airqualitybench"
dataset_slugs:
  - "airqualitybench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:12:08Z"
created_at: "2026-05-09T05:12:08Z"
---

# AirQualityBench: A Realistic Evaluation Benchmark for Global Air Quality Forecasting

**Authors**: Xing Xu, Xu Wang, Yudong Zhang, Huilin Zhao, Zhengyang Zhou, Yang Wang
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05854](https://arxiv.org/abs/2605.05854)

## Summary

AirQualityBench is a comprehensive, real-world benchmark for air quality forecasting that addresses the limitations of current research practices relying on sanitized, cleaned data. By preserving heterogeneous observation masks and requiring forecasts to be evaluated on unnormalized physical scales, the benchmark exposes the challenges of structured missingness and non-uniform global coverage. The authors show that standard spatiotemporal models often fail when applied to these more realistic, fragmented environmental data streams.

## Key Contributions

- Introduces AirQualityBench, a new benchmark containing 5 years of hourly data from 3,720 global stations, specifically designed to address limitations of traditional sanitized air quality datasets.
- Shifts the forecasting evaluation paradigm by maintaining provider-native observation masks and requiring error assessment on physical concentration scales rather than normalized, imputed tensors.
- Demonstrates that performance on idealized, preprocessed datasets does not correlate with success in realistic, fragmented monitoring scenarios, highlighting the need for robust mask-aware modeling.

## Open Questions & Future Work

- [[harmonized-pollutant-unit-conversion]]

## Key Concepts

- [[airqualitybench]]: A global multi-pollutant benchmark for air-quality forecasting that treats structured missingness and realistic observation masks as core components of the problem.

## Archivist Review

The paper provides a significant methodological shift for evaluating spatio-temporal forecasting by emphasizing the importance of native observation masks and physical scale evaluation over traditional, sanitized benchmarks. I have approved the benchmark as both a concept and a dataset, as it serves as a new foundation for testing model robustness. The open question regarding unit harmonization is approved as it addresses a core limitation to generalizability in real-world environmental monitoring.

### Approved Concepts
- AirQualityBench: It addresses a significant gap in time-series forecasting by shifting from sanitized, pre-imputed data to a paradigm that includes structured missingness and physical scale evaluation, which are critical for real-world environmental monitoring.

### Approved Open Questions
- Harmonization of Pollutant Units: This issue is a fundamental bottleneck to achieving physically valid evaluation and cross-region model generalization in global environmental monitoring.

## Datasets

- [[airqualitybench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.05854)
- [PDF](https://arxiv.org/pdf/2605.05854)

