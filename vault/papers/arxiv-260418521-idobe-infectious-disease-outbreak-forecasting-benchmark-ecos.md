---
# CSL-compatible fields
title: "IDOBE: Infectious Disease Outbreak forecasting Benchmark Ecosystem"
author:
  - literal: "Aniruddha Adiga"
  - literal: "Jingyuan Chou"
  - literal: "Anshul Chiranth"
  - literal: "Bryan Lewis"
  - literal: "Ana I. Bento"
  - literal: "Shaun Truelove"
  - literal: "Geoffrey Fox"
  - literal: "Madhav Marathe"
  - literal: "Harry Hochheiser"
  - literal: "Srini Venkatramanan"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18521"

# Custom fields
paper_id: "2604.18521"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "benchmarking"
  - "epidemiology"
architectures:
  []
datasets:
  - "idobe"
concept_slugs:
  []
dataset_slugs:
  - "idobe"
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:05:54Z"
created_at: "2026-04-22T05:05:54Z"
---

# IDOBE: Infectious Disease Outbreak forecasting Benchmark Ecosystem

**Authors**: Aniruddha Adiga, Jingyuan Chou, Anshul Chiranth, Bryan Lewis, Ana I. Bento, Shaun Truelove, Geoffrey Fox, Madhav Marathe, Harry Hochheiser, Srini Venkatramanan
**Date**: 2026-04-20
**Paper ID**: [arxiv:2604.18521](https://arxiv.org/abs/2604.18521)

## Summary

The paper introduces IDOBE, a novel, curated benchmark ecosystem designed to standardize the evaluation of infectious disease outbreak forecasting models. It compiles over 10,000 historical outbreak segments across 13 diseases, providing a diverse set of epidemiological time series for multi-horizon forecasting. By assessing 11 baseline models using both standard point metrics and probabilistic scoring rules, the authors offer critical insights into the performance of machine learning versus statistical approaches during different outbreak phases. The ecosystem is released publicly to facilitate reproducible research and advancement in real-time epidemic response.

## Key Contributions

- Introduces IDOBE, a comprehensive benchmark ecosystem for infectious disease outbreak forecasting containing over 10,000 segmented outbreaks.
- Standardizes evaluation protocols for epidemic forecasting across 13 diseases using a mix of point and probabilistic metrics including NWIS.
- Provides a comparative analysis of 11 baseline models, revealing superior performance of MLP-based methods over statistical baselines for general outbreak modeling.

## Open Questions & Future Work

- [[multi-wave-epidemic-forecasting-benchmarks]]

## Archivist Review

I approved the IDOBE dataset as a significant, curated resource for epidemiological time-series benchmarking and the multi-wave epidemic forecasting question as a substantial research gap. I rejected the ecosystem itself as a concept because it represents a collection of tasks and data rather than an abstract forecasting mechanism or methodology that would naturally recur in future non-epidemiological literature.

### Approved Open Questions
- Multi-wave Epidemic Forecasting Benchmarks: Moving beyond isolated outbreaks is essential for developing predictive tools capable of handling the non-stationary, multi-wave nature of long-term epidemiological crises.

### Rejected Candidates
- [concept] IDOBE: Infectious Disease Outbreak forecasting Benchmark Ecosystem (`idobe-ecosystem`) - not_reusable: The core contribution is a dataset/benchmark package, not a distinct algorithmic mechanism or conceptual methodology reusable outside of epidemic forecasting.

## Datasets

- [[idobe]]

## Links

- [Abstract](https://arxiv.org/abs/2604.18521)
- [PDF](https://arxiv.org/pdf/2604.18521)

