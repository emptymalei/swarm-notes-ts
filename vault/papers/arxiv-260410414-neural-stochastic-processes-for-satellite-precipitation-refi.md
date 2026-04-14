---
# CSL-compatible fields
title: "Neural Stochastic Processes for Satellite Precipitation Refinement"
author:
  - literal: "Shunya Nagashima"
  - literal: "Takumi Bannai"
  - literal: "Shuitsu Koyama"
  - literal: "Tomoya Mitsui"
  - literal: "Shuntaro Suzuki"
issued:
  date-parts:
    - [2026, 4, 12]
url: "https://arxiv.org/abs/2604.10414"

# Custom fields
paper_id: "2604.10414"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "spatiotemporal-modeling"
  - "precipitation-forecasting"
  - "stochastic-processes"
architectures:
  - "neural-process"
  - "neural-sde"
datasets:
  - "qpebench"
concept_slugs:
  - "neural-stochastic-process-nsp"
dataset_slugs:
  - "qpebench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:05:56Z"
created_at: "2026-04-14T05:05:56Z"
---

# Neural Stochastic Processes for Satellite Precipitation Refinement

**Authors**: Shunya Nagashima, Takumi Bannai, Shuitsu Koyama, Tomoya Mitsui, Shuntaro Suzuki
**Date**: 2026-04-12
**Paper ID**: [arxiv:2604.10414](https://arxiv.org/abs/2604.10414)

## Summary

This paper introduces the Neural Stochastic Process (NSP) framework for refining satellite-based precipitation estimates using sparse ground-based gauge data. By integrating a Neural Process encoder with a latent Neural SDE, the model effectively captures the spatiotemporal dependencies that traditional independent-time-step methods overlook. The authors also present QPEBench, a high-resolution benchmark dataset covering the Contiguous United States, where NSP consistently outperforms existing operational and machine learning baselines. Experimental results confirm the model's ability to maintain accuracy and generalize across distinct geographical regions.

## Key Contributions

- Introduced Neural Stochastic Process (NSP), which leverages latent Neural SDEs over 2D spatial representations to capture temporal dynamics in precipitation refinement.
- Developed QPEBench, a large-scale spatiotemporal precipitation dataset containing 43,756 hourly samples from the Contiguous United States.
- Achieved superior performance against 13 baselines and operational products on QPEBench, demonstrating robustness in regional generalization to Kyushu, Japan.

## Open Questions & Future Work

- [[residual-correction-spatial-reconstruction-limits]]

## Key Concepts

- [[neural-stochastic-process-nsp]]: A spatiotemporal fusion model that combines a Neural Process encoder with a latent Neural SDE to refine sparse observational data on spatial grids.

## Archivist Review

The paper introduces a compelling synthesis of Neural Processes and SDEs for spatial field refinement. I approved the NSP concept and the QPEBench dataset as they represent a robust, reusable framework and a significant benchmark for spatiotemporal forecasting. I approved the question regarding residual correction limitations because it probes a specific architectural bottleneck inherent to the satellite-gauge fusion paradigm, while rejecting the extreme precipitation question as too generic to the field of ML.

### Approved Concepts
- Neural Stochastic Process (NSP): It provides a novel framework for merging continuous-time latent dynamics with spatial process modeling for sparse observation fusion.

### Approved Open Questions
- Residual Correction Spatial Limits: This addresses a fundamental limitation in current sensor-fusion paradigms for spatial field reconstruction.

### Rejected Candidates
- [open_question] Extreme Precipitation Reconstruction Bottlenecks (`extreme-precipitation-reconstruction-bottleneck`) - generic: The problem of training on extreme events is a generic challenge for most climate and forecasting models and does not represent a specific, unique unresolved architectural bottleneck as defined by the provided prompt.

## Datasets

- [[qpebench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.10414)
- [PDF](https://arxiv.org/pdf/2604.10414)

