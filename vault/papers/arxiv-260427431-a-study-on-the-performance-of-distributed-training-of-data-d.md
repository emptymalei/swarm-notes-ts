---
# CSL-compatible fields
title: "A Study on the Performance of Distributed Training of Data-driven CFD Simulations"
author:
  - literal: "Sergio Iserte"
  - literal: "Alejandro González-Barberá"
  - literal: "Paloma Barreda"
  - literal: "Krzysztof Rojek"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27431"

# Custom fields
paper_id: "2604.27431"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:23:35Z"
created_at: "2026-05-01T05:23:35Z"
---

# A Study on the Performance of Distributed Training of Data-driven CFD Simulations

**Authors**: Sergio Iserte, Alejandro González-Barberá, Paloma Barreda, Krzysztof Rojek
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27431](https://arxiv.org/abs/2604.27431)

## Summary

This paper evaluates the performance of distributed training strategies for data-driven fluid simulations, which replace traditional computationally intensive PDE solvers with deep learning models. By comparing CPU-only, multi-GPU, and distributed training implementations, the study quantifies the efficiency gains in the training stage of these predictive models. The results indicate that distributed GPU training significantly reduces the time required to achieve high-accuracy fluid state predictions, making it a viable alternative to traditional CFD approaches.

## Key Contributions

- Analyzes the performance trade-offs of CPU, multi-GPU, and distributed training strategies for data-driven fluid simulation models.
- Demonstrates that distributed GPU-enabled training achieves high-accuracy fluid state predictions significantly faster than traditional PDE-based CFD solvers.
- Provides a comprehensive evaluation of computational overhead and training acceleration for time series forecasting models in scientific computing.

## Open Questions & Future Work

- [[distributed-training-scalability-cfd-surrogates]]

## Archivist Review

The paper provides an empirical study of distributed training strategies for scientific surrogates, but does not introduce new architectural concepts or novel learning mechanisms. I approved the open question regarding the scalability of such training, as it identifies a critical, unresolved infrastructure bottleneck in the adoption of AI-driven PDE emulators, and renamed it for better clarity.

### Approved Open Questions
- Scalability of Distributed CFD Training: Efficient training is a primary barrier to replacing computationally expensive numerical solvers with AI-driven surrogates in physical sciences.

### Rejected Candidates
- [open_question] Scalability of Distributed CFD Training (`distributed-training-bottlenecks-cfd`) - duplicate_existing: The slug was renamed to better reflect the scope of 'cfd-surrogates'.

## Links

- [Abstract](https://arxiv.org/abs/2604.27431)
- [PDF](https://arxiv.org/pdf/2604.27431)

