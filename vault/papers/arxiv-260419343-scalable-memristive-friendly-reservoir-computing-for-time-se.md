---
# CSL-compatible fields
title: "Scalable Memristive-Friendly Reservoir Computing for Time Series Classification"
author:
  - literal: "Coşku Can Horuz"
  - literal: "Andrea Ceni"
  - literal: "Claudio Gallicchio"
  - literal: "Sebastian Otte"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19343"

# Custom fields
paper_id: "2604.19343"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "reservoir-computing"
  - "neuromorphic-computing"
  - "time-series-classification"
  - "efficient-training"
  - "memristive-hardware"
architectures:
  []
datasets:
  []
concept_slugs:
  - "memristive-friendly-parallelized-reservoirs-mars"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:03:51Z"
created_at: "2026-04-22T05:03:51Z"
---

# Scalable Memristive-Friendly Reservoir Computing for Time Series Classification

**Authors**: Coşku Can Horuz, Andrea Ceni, Claudio Gallicchio, Sebastian Otte
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19343](https://arxiv.org/abs/2604.19343)

## Summary

This paper introduces Memristive-friendly Parallelized Reservoirs (MARS), a novel architecture designed for scalable and efficient time series classification on neuromorphic hardware. By utilizing subtractive skip connections, the framework enables deeper model composition and parallel computation, significantly accelerating training compared to conventional echo state networks. Empirical results demonstrate that MARS outperforms state-of-the-art gradient-based models like Mamba and S5 on long-sequence benchmarks, providing high predictive performance with minimal computational latency.

## Key Contributions

- Introduces MARS, a reservoir computing architecture that uses subtractive skip connections for efficient parallel computation and deeper composition.
- Achieves up to 21x training speedups compared to standard echo state networks.
- Outperforms gradient-based models like LRU, S5, and Mamba on long sequence benchmarks while reducing training times from minutes/hours to milliseconds.

## Open Questions & Future Work

- [[automated-hyperparameter-optimization-for-reservoir-networks]]

## Key Concepts

- [[memristive-friendly-parallelized-reservoirs-mars]]: A scalable reservoir computing architecture utilizing subtractive skip connections for efficient parallel sequence processing.

## Archivist Review

The review focused on the architectural innovation, MARS, which provides a novel approach to parallelizing reservoir computing, and the identified challenge of automating hyperparameter selection for these gradient-free models. Other candidates were rejected as being either subcomponents or boilerplate research directions.

### Approved Concepts
- Memristive-friendly Parallelized Reservoirs (MARS): It is the core architectural contribution of the paper, enabling efficient parallel computation in memristive systems.

### Approved Open Questions
- Automated hyperparameter optimization: The reliance on manual tuning acts as a bottleneck for scaling reservoir models to new domains, hindering their usability in broader applications.

### Rejected Candidates
- [concept] Subtractive Skip Connections (`subtractive-skip-connections`) - subcomponent_of_broader_mechanism: This is a specific subcomponent of the MARS architecture and does not warrant a separate entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.19343)
- [PDF](https://arxiv.org/pdf/2604.19343)

