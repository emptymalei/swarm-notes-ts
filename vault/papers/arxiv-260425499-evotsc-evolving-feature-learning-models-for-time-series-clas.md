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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "evotsc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:15:50Z"
created_at: "2026-04-30T05:15:50Z"
---

# EvoTSC: Evolving Feature Learning Models for Time Series Classification via Genetic Programming

**Authors**: Xuanhao Yang, Bing Xue, Mengjie Zhang
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25499](https://arxiv.org/abs/2604.25499)

## Summary

EvoTSC is a genetic programming-based framework designed to automate the discovery of lightweight feature learning models for time series classification. The approach improves search efficiency and model quality by embedding domain-specific expert knowledge into the multi-layer program structure. Additionally, a Pareto tournament selection mechanism is employed to enforce model generalizability and prevent overfitting, resulting in robust performance on univariate time series benchmarks.

## Key Contributions

- Introduces EvoTSC, a genetic programming approach that evolves lightweight feature learning models for time series classification using expert-informed structural priors.
- Proposes a tailored Pareto tournament selection strategy that optimizes for model generalizability across training subsets to mitigate overfitting.
- Demonstrates that EvoTSC outperforms eleven state-of-the-art benchmark methods on univariate time series classification tasks while maintaining high resource efficiency.

## Open Questions & Future Work

- [[multivariate-tsc-extension]]
- [[cross-dataset-knowledge-transfer]]

## Key Concepts

- [[evotsc]]: A genetic programming framework that evolves lightweight, expert-guided feature learning models for time series classification.

## Archivist Review

I approved the EvoTSC framework as it introduces a distinct approach to automated feature learning by merging structural priors with genetic programming, which is highly reusable. The open questions regarding multivariate extensions and knowledge transfer were approved because they represent critical bottlenecks for scaling evolutionary feature discovery in time series domains. I applied a restrictive filter, ensuring only the core methodology and high-level architectural research directions were retained.

### Approved Concepts
- EvoTSC: It introduces a hybrid paradigm of genetic programming with expert-informed structural priors for automated feature learning in time series analysis.

### Approved Open Questions
- Multivariate Time Series Classification: Many real-world TSC problems are inherently multivariate; failure to capture inter-variable dependencies restricts the utility of evolutionary search frameworks.
- Transfer Learning in GP: Transferring structural building blocks mitigates the computational cost of re-evolving pipelines and enables the accumulation of generalized inductive biases in evolutionary systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.25499)
- [PDF](https://arxiv.org/pdf/2604.25499)

