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
processed_at: "2026-05-03T05:13:44Z"
created_at: "2026-05-03T05:13:44Z"
---

# Sequential Inference for Gaussian Processes: A Signal Processing Perspective

**Authors**: Daniel Waxman, Fernando Llorente, Petar M. Djurić
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28163](https://arxiv.org/abs/2604.28163)

## Summary

This paper presents a comprehensive tutorial on Gaussian Processes (GPs) tailored for sequential inference, a critical requirement in real-time signal processing systems where data arrive incrementally. It synthesizes theoretical foundations with recent methodological advancements, bridging the gap between traditional signal processing paradigms and contemporary machine learning techniques. The authors organize these developments into a coherent roadmap designed to assist practitioners in deploying scalable, adaptive GP models for complex time-series and decision-making tasks.

## Key Contributions

- Provides a self-contained, tutorial-style overview of Gaussian Processes (GPs) focused on sequential, incremental, and streaming inference.
- Establishes a bridge between traditional signal processing perspectives and modern machine learning approaches for GP modeling.
- Systematizes applications of sequential GP models across state-space modeling, forecasting, anomaly detection, Bayesian optimization, and active sensing.

## Open Questions & Future Work

- [[flexible-nonstationary-kernels-for-sgps]]
- [[scalable-distributed-gps-in-networks]]

## Archivist Review

The paper is a high-quality tutorial synthesis rather than a source of novel methodology. I have therefore approved the two open questions, which concisely capture the critical limitations of GP-based sequential inference in complex environments, but I have rejected the concept category as no novel, standalone mechanism was identified.

### Approved Open Questions
- Flexible kernels for sequential GPs: Improving the expressiveness of sequential GP models is critical for deploying probabilistic models in complex, nonstationary signal processing environments where standard stationary kernels fail.
- Scalable distributed GP inference: This is essential for enabling scalable, fault-tolerant, and autonomous sensor networks where decentralized signal estimation is required.

### Rejected Candidates
- [concept] No concepts were proposed. (`none-proposed`) - not_novel: The paper is a tutorial overview and did not propose a new, standalone ML methodology worthy of a permanent vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.28163)
- [PDF](https://arxiv.org/pdf/2604.28163)

