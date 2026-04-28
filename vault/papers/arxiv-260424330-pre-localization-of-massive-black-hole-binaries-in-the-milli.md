---
# CSL-compatible fields
title: "Pre-localization of Massive Black Hole Binaries in the Millihertz Band"
author:
  - literal: "Xue-Ting Zhang"
  - literal: "Jonathan Gair"
  - literal: "Chris Messenger"
  - literal: "Natalia Korsakova"
  - literal: "Yi-Ming Hu"
  - literal: "Hong-Yu Chen"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24330"

# Custom fields
paper_id: "2604.24330"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "bayesian-inference"
  - "gravitational-waves"
  - "real-time-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:14:33Z"
created_at: "2026-04-28T05:14:33Z"
---

# Pre-localization of Massive Black Hole Binaries in the Millihertz Band

**Authors**: Xue-Ting Zhang, Jonathan Gair, Chris Messenger, Natalia Korsakova, Yi-Ming Hu, Hong-Yu Chen
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24330](https://arxiv.org/abs/2604.24330)

## Summary

This paper introduces a fast, normalizing flow-based Bayesian inference pipeline for the real-time detection and localization of massive black hole binaries (MBHBs) in space-borne gravitational-wave detectors like TianQin. By leveraging a learned embedding of detector time series combined with a neural spline flow, the pipeline achieves efficient pre-merger parameter estimation and sky localization. The model provides results comparable to classical PTMCMC methods within a one-minute processing window, enabling rapid electromagnetic follow-up for pre-merger events.

## Key Contributions

- Proposes a Normalizing Flow-based inference pipeline using Neural Spline Flows (NSF) for real-time MBHB early-warning parameter estimation.
- Demonstrates that the proposed pipeline achieves ~20 deg^2 sky localization for events 15 minutes before merger in a TianQin-like configuration.
- Matches the accuracy and recovery capability of standard Parallel-Tempered Markov Chain Monte Carlo (PTMCMC) methods while reducing inference time to approximately one minute.

## Open Questions & Future Work

- [[handling-overlapping-gravitational-wave-signals]]

## Archivist Review

The paper presents a domain-specific application of normalizing flows for real-time parameter estimation in gravitational-wave astronomy. While the pipeline is effective for its specific use case, it does not introduce a sufficiently novel or generalizable forecasting concept to warrant a permanent vault entry. The open question regarding overlapping signal handling is approved as it addresses a critical scalability bottleneck for high-density time-series monitoring environments.

### Approved Open Questions
- Handling overlapping GW signals: As space-based detectors will observe signals from numerous overlapping sources, developing techniques to perform robust parameter estimation and deblending in high-density data is a fundamental requirement for operational pipeline scalability.

### Rejected Candidates
- [concept] Normalizing Flow-based inference pipeline (`normalizing-flow-based-inference-pipeline`) - not_novel: Normalizing flows are a well-established generative modeling technique; applying them to gravitational wave inference is a domain-specific application rather than a novel, reusable forecasting concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.24330)
- [PDF](https://arxiv.org/pdf/2604.24330)

