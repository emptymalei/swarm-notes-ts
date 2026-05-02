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
domain: "time-series"
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
processed_at: "2026-05-02T05:08:41Z"
created_at: "2026-05-02T05:08:41Z"
---

# A Study on the Performance of Distributed Training of Data-driven CFD Simulations

**Authors**: Sergio Iserte, Alejandro González-Barberá, Paloma Barreda, Krzysztof Rojek
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27431](https://arxiv.org/abs/2604.27431)

## Summary

This paper examines the computational trade-offs in training data-driven models for fluid dynamics simulations, which aim to replace computationally expensive PDE-based CFD solvers. The authors compare the efficiency of CPU-only, multi-GPU, and distributed training paradigms for a time-series forecasting deep learning model. The study highlights that distributed GPU training significantly accelerates the training stage while maintaining high-fidelity physical predictions compared to classical iterative methods.

## Key Contributions

- Evaluates training performance of deep learning models for time-series CFD simulation across CPU, multi-GPU, and distributed architectures.
- Demonstrates that distributed GPU-enabled training significantly reduces training time compared to traditional CFD PDE-based solvers without compromising predictive accuracy.
- Provides a comparative analysis of implementation strategies for scaling AI-driven physical simulation training workloads.

## Open Questions & Future Work

- [[distributed-training-scalability-cfd-surrogates]]

## Archivist Review

The paper provides a comparative study of hardware scaling for neural PDE surrogates. I approved the open question regarding the scalability of small-model/large-data paradigms in distributed scientific computing, as it represents a persistent challenge for transitioning CFD to AI-based inference. No new concepts were approved as the study primarily applies existing distributed training paradigms to a specific domain use case.

### Approved Open Questions
- Distributed training scalability bottlenecks: This addresses a fundamental limitation in applying standard data-parallel distributed training to scientific computing, where the model-to-data size ratio often leads to communication-bound performance bottlenecks.

### Rejected Candidates
- [open_question] Distributed Training Scalability Bottlenecks (`ai-cfd-training-scalability-bottleneck`) - other: Renamed to a more descriptive slug for consistency with existing vault naming patterns.

## Links

- [Abstract](https://arxiv.org/abs/2604.27431)
- [PDF](https://arxiv.org/pdf/2604.27431)

