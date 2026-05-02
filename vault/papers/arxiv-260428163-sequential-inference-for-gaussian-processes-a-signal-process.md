---
# CSL-compatible fields
title: "Sequential Inference for Gaussian Processes: A Signal Processing Perspective"
author:
  - literal: "Daniel Waxman"
  - literal: "Fernando Llorente"
  - literal: "Petar M. Djurić"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28163"

# Custom fields
paper_id: "2604.28163"
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
processed_at: "2026-05-02T05:06:59Z"
created_at: "2026-05-02T05:06:59Z"
---

# Sequential Inference for Gaussian Processes: A Signal Processing Perspective

**Authors**: Daniel Waxman, Fernando Llorente, Petar M. Djurić
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28163](https://arxiv.org/abs/2604.28163)

## Summary

This paper provides a unified, tutorial-style overview of Gaussian processes (GPs) with a specific emphasis on sequential and streaming inference techniques. By bridging recent machine learning advancements with classical signal processing perspectives, the authors categorize methods for modeling nonlinear relationships in non-i.i.d. data streams. The work serves as a practical guide for researchers and engineers tasked with deploying GP-based systems for time-series forecasting, anomaly detection, and decision-making.

## Key Contributions

- Provides a comprehensive tutorial-style survey of Gaussian process (GP) methodology tailored for signal processing (SP) practitioners.
- Organizes and bridges recent machine learning advancements in sequential and streaming GP inference with traditional signal processing frameworks.
- Establishes a structured roadmap for deploying sequential GP models across diverse applications including state-space modeling, sequential forecasting, and adaptive sensing.

## Open Questions & Future Work

- [[nonstationary-kernel-expressiveness]]
- [[distributed-gp-scalability]]

## Archivist Review

This paper is a survey and does not propose new specific methods or novel concepts that meet the vault's high bar for standalone notes, although it does clearly identify key research bottlenecks. The two open questions were approved because they represent central, long-standing research challenges in the GP and signal processing literature that require persistent tracking. No datasets were proposed by the authors, and no concepts were identified that qualify as unique, reusable architectural or methodological contributions beyond the existing knowledge base.

### Approved Open Questions
- Flexible kernels for nonstationarity: Developing nonstationary kernels that maintain computational efficiency is critical for applying Gaussian processes to complex, real-world signal processing problems where signal properties evolve significantly over time.
- Scalable distributed GP inference: As signal processing systems become increasingly decentralized, developing scalable, fault-tolerant inference mechanisms for distributed Gaussian processes is essential for practical deployment.

## Links

- [Abstract](https://arxiv.org/abs/2604.28163)
- [PDF](https://arxiv.org/pdf/2604.28163)

