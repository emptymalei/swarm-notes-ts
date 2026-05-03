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
processed_at: "2026-05-03T05:15:27Z"
created_at: "2026-05-03T05:15:27Z"
---

# A Study on the Performance of Distributed Training of Data-driven CFD Simulations

**Authors**: Sergio Iserte, Alejandro González-Barberá, Paloma Barreda, Krzysztof Rojek
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27431](https://arxiv.org/abs/2604.27431)

## Summary

This paper investigates the performance scaling of training data-driven models for computational fluid dynamics (CFD) simulations. It evaluates various infrastructure implementations, including CPU-only, multi-GPU, and distributed setups, to accelerate the traditionally time-consuming training phase for PDE-based simulation surrogates. The results demonstrate the efficiency gains of distributed GPU-enabled training in achieving high-accuracy fluid state predictions compared to conventional solvers.

## Key Contributions

- Analyzes performance of CPU-only, multi-GPU, and distributed training configurations for data-driven CFD simulation forecasting.
- Demonstrates that distributed GPU-enabled training significantly reduces training time compared to traditional iterative PDE-based solvers.
- Provides a comparative implementation study for time-series forecasting models applied to fluid simulation physical behavior.

## Open Questions & Future Work

- [[distributed-training-scalability-bottlenecks]]

## Archivist Review

The paper provides a comparative study of infrastructure for training CFD surrogates, which is an applied systems engineering result rather than a methodological contribution to the field of time-series forecasting or scientific ML. The proposed open question is rejected because it describes general distributed computing overheads common to many domains rather than a specific research gap in the context of PDE-based surrogate modeling.

### Approved Open Questions
- Distributed training scalability bottlenecks: Communication overhead relative to compute intensity remains a fundamental scaling limitation for scientific machine learning surrogate modeling.

### Rejected Candidates
- [open_question] Distributed training scalability bottlenecks (`distributed-training-scalability-bottlenecks`) - generic: The candidate is generic to distributed machine learning rather than specific to a unique methodological hurdle in scientific forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2604.27431)
- [PDF](https://arxiv.org/pdf/2604.27431)

