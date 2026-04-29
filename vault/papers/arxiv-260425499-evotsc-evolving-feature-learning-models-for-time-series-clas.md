---
# CSL-compatible fields
title: "EvoTSC: Evolving Feature Learning Models for Time Series Classification via Genetic Programming"
author:
  - literal: "Xuanhao Yang"
  - literal: "Bing Xue"
  - literal: "Mengjie Zhang"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25499"

# Custom fields
paper_id: "2604.25499"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-classification"
  - "genetic-programming"
  - "automated-machine-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "evotsc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:11:16Z"
created_at: "2026-04-29T05:11:16Z"
---

# EvoTSC: Evolving Feature Learning Models for Time Series Classification via Genetic Programming

**Authors**: Xuanhao Yang, Bing Xue, Mengjie Zhang
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25499](https://arxiv.org/abs/2604.25499)

## Summary

EvoTSC addresses the challenges of computational cost and data scarcity in time series classification (TSC) by utilizing genetic programming to evolve efficient feature learning models. The framework embeds expert knowledge directly into the multi-layer program structure to guide the search space toward high-performing temporal operations. Additionally, a Pareto tournament selection mechanism is employed to ensure model robustness and generalizability across different training subsets. Empirical results on univariate benchmarks confirm that EvoTSC outperforms multiple standard classification baselines while achieving significant model compression.

## Key Contributions

- Introduces EvoTSC, a genetic programming framework that automatically evolves lightweight, interpretable feature learning models for time series classification.
- Integrates domain-specific expert knowledge into the evolutionary search process to prioritize effective temporal operations.
- Implements a Pareto tournament selection strategy to enhance model generalizability and mitigate overfitting on small-labeled datasets.
- Demonstrates superior performance against eleven benchmark methods across standard univariate time series classification datasets while maintaining resource efficiency.

## Open Questions & Future Work

- [[multivariate-time-series-gp-search]]
- [[cross-dataset-gp-knowledge-transfer]]

## Key Concepts

- [[evotsc]]: A genetic programming framework that evolves lightweight, generalizable feature learning models for time series classification by incorporating expert knowledge.

## Archivist Review

The paper introduces a specific genetic programming framework for TSC. I approved the framework itself as it embodies a reusable methodology for evolutionary AutoML in time series. I also approved two research directions that specifically address the limitations of GP methods in scaling to multivariate data and the redundant nature of learning from scratch for every new task. Generic benchmarks were excluded.

### Approved Concepts
- EvoTSC: Represents a structured approach to evolutionary AutoML for time series, specifically targeting the constraint of low data/resource availability.

### Approved Open Questions
- Multivariate time series GP extension: Multivariate data is ubiquitous, and existing evolutionary search techniques often struggle to scale to cross-variable dependencies effectively.
- Cross-dataset GP knowledge transfer: Crucial for scaling evolutionary learning methods and reducing redundant computation in resource-constrained environments.

## Links

- [Abstract](https://arxiv.org/abs/2604.25499)
- [PDF](https://arxiv.org/pdf/2604.25499)

