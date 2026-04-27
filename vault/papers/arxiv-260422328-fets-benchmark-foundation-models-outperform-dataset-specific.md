---
# CSL-compatible fields
title: "FETS Benchmark: Foundation Models Outperform Dataset-specific Machine Learning in Energy Time Series Forecasting"
author:
  - literal: "Marco Obermeier"
  - literal: "Marco Pruckner"
  - literal: "Florian Haselbeck"
  - literal: "Andreas Zeiselmair"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2604.22328"

# Custom fields
paper_id: "2604.22328"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "foundation-models"
  - "energy-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "fets-benchmark"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T05:11:32Z"
created_at: "2026-04-27T05:11:32Z"
---

# FETS Benchmark: Foundation Models Outperform Dataset-specific Machine Learning in Energy Time Series Forecasting

**Authors**: Marco Obermeier, Marco Pruckner, Florian Haselbeck, Andreas Zeiselmair
**Date**: 2026-04-24
**Paper ID**: [arxiv:2604.22328](https://arxiv.org/abs/2604.22328)

## Summary

The FETS benchmark provides a structured evaluation of foundation models in the energy forecasting domain, addressing the limitations of traditional dataset-specific models. By analyzing 54 distinct datasets across 9 categories, the researchers demonstrate that pretrained foundation models achieve superior forecasting accuracy compared to specialized ML models. The results highlight the efficacy of covariate-informed foundation models and provide insights into the scaling behaviors of performance relative to data aggregation and spectral characteristics.

## Key Contributions

- Developed the FETS benchmark, evaluating foundation models across 54 datasets spanning 9 energy categories.
- Demonstrated that foundation models consistently outperform dataset-specific ML baselines, even when the latter are trained on the full historic target data.
- Identified performance drivers such as covariate utilization, spectral entropy correlation, and aggregation levels, while documenting saturation effects of context length.

## Key Concepts

- [[fets-benchmark]]: A large-scale benchmark for evaluating and comparing foundation models across 54 energy time series forecasting datasets.

## Archivist Review

I have approved the FETS Benchmark as a concept because it introduces a crucial taxonomic framework for categorizing energy forecasting tasks across stakeholders, attributes, and data, which is more reusable than just the dataset collection itself. I have rejected all other candidates to maintain a high threshold for inclusion, focusing on architectural or theoretical contributions rather than empirical benchmark reports.

### Approved Concepts
- FETS Benchmark: It provides the first comprehensive, large-scale evaluation of foundation models across 54 diverse energy datasets, moving the field toward cross-dataset generalizable forecasting.

### Rejected Candidates
- [concept] FETS Benchmark (`fets-benchmark`) - not_reusable: The benchmark is the primary contribution, but I have opted to keep it as a concept for its taxonomy of energy forecasting use cases; however, it is borderline as a benchmark suite.

## Links

- [Abstract](https://arxiv.org/abs/2604.22328)
- [PDF](https://arxiv.org/pdf/2604.22328)

