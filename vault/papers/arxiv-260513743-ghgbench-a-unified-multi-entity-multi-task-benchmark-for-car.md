---
# CSL-compatible fields
title: "GHGbench: A Unified Multi-Entity, Multi-Task Benchmark for Carbon Emission Prediction"
author:
  - literal: "Yifan Duan"
  - literal: "Siyuan Zheng"
  - literal: "Lihuan Li"
  - literal: "Chao Xue"
  - literal: "Flora Salim"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13743"

# Custom fields
paper_id: "2605.13743"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "ghgbench"
concept_slugs:
  - "ghgbench"
dataset_slugs:
  - "ghgbench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:22:55Z"
created_at: "2026-05-14T05:22:55Z"
---

# GHGbench: A Unified Multi-Entity, Multi-Task Benchmark for Carbon Emission Prediction

**Authors**: Yifan Duan, Siyuan Zheng, Lihuan Li, Chao Xue, Flora Salim
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13743](https://arxiv.org/abs/2605.13743)

## Summary

GHGbench is a comprehensive benchmark designed to standardize carbon emission prediction across entity levels, covering 12,000+ firms and nearly 500,000 building records. The benchmark evaluates models on both in-distribution and cross-region transfer tasks using a diverse set of baseline architectures, ranging from traditional gradient-boosted trees to tabular foundation models and multimodal fusion networks. Findings reveal significant performance gaps in cross-city transfer and highlight the utility of remote-sensing data in enhancing building-level emission forecasting.

## Key Contributions

- Introduces GHGbench, a large-scale, unified benchmark with 32,000+ company-year and 491,591 building-year records across diverse metropolitan areas.
- Identifies structural difficulty differences between building and company emissions and quantifies the performance gap between in-distribution and out-of-distribution transfer tasks.
- Demonstrates that multimodal remote-sensing embeddings improve generalization for building emissions when tabular models reach their performance limits.

## Open Questions & Future Work

- [[emissions-prediction-generalization-failure-modes]]

## Key Concepts

- [[ghgbench]]: A unified, large-scale benchmark for company- and building-level greenhouse-gas emission prediction.

## Archivist Review

I approved GHGbench as it introduces a critical standardized evaluation framework for the underserved domain of carbon emission forecasting. The open question on generalization failure modes was approved because it addresses the identified 'catastrophic' performance bottlenecks which are central to the future development of robust emission models. I was highly selective, rejecting any minor findings or specific technical implementation details.

### Approved Concepts
- GHGbench: It establishes a unified, large-scale, multi-entity benchmark for carbon emission prediction, standardizing evaluation across company and building scales.

### Approved Open Questions
- Emissions Forecasting Generalization Failure: These failure modes represent the most significant bottlenecks to deploying predictive emission models across diverse geographic and structural contexts.

## Datasets

- [[ghgbench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.13743)
- [PDF](https://arxiv.org/pdf/2605.13743)

