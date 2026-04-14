---
# CSL-compatible fields
title: "TempusBench: An Evaluation Framework for Time-Series Forecasting"
author:
  - literal: "Denizalp Goktas"
  - literal: "Gerardo Riaño-Briceño"
  - literal: "Alif Abdullah"
  - literal: "Aryan Nair"
  - literal: "Aryan Nair"
  - literal: "Chenkai Shen"
  - literal: "Beatriz de Lucio"
  - literal: "Alexandra Magnusson"
  - literal: "Farhan Mashrur"
  - literal: "Ahmed Abdulla"
  - literal: "Shawrna Sen"
  - literal: "Mahitha Thippireddy"
  - literal: "Gregory Schwartz"
  - literal: "Amy Greenwald"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11529"

# Custom fields
paper_id: "2604.11529"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "tempusbench"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:02:59Z"
created_at: "2026-04-14T05:02:59Z"
---

# TempusBench: An Evaluation Framework for Time-Series Forecasting

**Authors**: Denizalp Goktas, Gerardo Riaño-Briceño, Alif Abdullah, Aryan Nair, Aryan Nair, Chenkai Shen, Beatriz de Lucio, Alexandra Magnusson, Farhan Mashrur, Ahmed Abdulla, Shawrna Sen, Mahitha Thippireddy, Gregory Schwartz, Amy Greenwald
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11529](https://arxiv.org/abs/2604.11529)

## Summary

TempusBench is an open-source evaluation framework for time-series foundation models (TSFMs) designed to address systematic shortcomings in current benchmarking practices. The framework mitigates issues like data leakage and inconsistent model comparisons by introducing fresh, non-contaminated datasets and a standardized hyperparameter tuning protocol. Furthermore, it shifts evaluation focus from simple forecast horizons to include critical statistical properties like seasonality and non-stationarity, supplemented by a dedicated visualization interface.

## Key Contributions

- Introduces TempusBench, an evaluation framework specifically designed to mitigate data contamination by providing datasets sequestered from common pre-training corpora.
- Implements a standardized, reproducible hyperparameter tuning protocol to ensure fair performance comparisons between deep learning-based TSFMs and traditional statistical models.
- Expands evaluation beyond simple forecast horizons to include robustness testing against statistical properties such as non-stationarity and seasonality.

## Open Questions & Future Work

- [[dynamic-time-series-benchmarking]]
- [[comprehensive-benchmark-taxonomy]]

## Key Concepts

- [[tempusbench]]: An open-source evaluation framework for time-series foundation models designed to address data leakage, statistical heterogeneity, and inconsistent hyperparameter tuning protocols.

## Archivist Review

I approved the evaluation framework TempusBench as a central, reusable tool for the field, along with two high-level open questions regarding the necessity of dynamic benchmarking and improved taxonomies for evaluating time-series models. I rejected the request to add datasets because they were not explicitly named/defined in the input, and the provided list followed a generic benchmarking paradigm.

### Approved Concepts
- TempusBench: Provides a standardized evaluation framework for TSFMs to address data contamination and hyperparameter inconsistency, which are currently critical bottlenecks in the field.

### Approved Open Questions
- Dynamic Time-Series Benchmarking: As foundation models dominate the research space, the lack of robust, non-contaminated evaluation benchmarks threatens the validity of reported model advancements.
- Comprehensive Benchmark Taxonomy: Standardizing benchmark taxonomies is essential for identifying the specific strengths and weaknesses of different model architectures across varying data conditions.

## Links

- [Abstract](https://arxiv.org/abs/2604.11529)
- [PDF](https://arxiv.org/pdf/2604.11529)

