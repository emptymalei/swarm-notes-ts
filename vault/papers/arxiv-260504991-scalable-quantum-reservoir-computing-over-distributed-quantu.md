---
# CSL-compatible fields
title: "Scalable Quantum Reservoir Computing over Distributed Quantum Architectures"
author:
  - literal: "Ioannis Liliopoulos"
  - literal: "Georgios D. Varsamis"
  - literal: "Konstantinos Rallis"
  - literal: "Evangelos Tsipas"
  - literal: "Ioannis G. Karafyllidis"
  - literal: "Georgios Ch. Sirakoulis"
  - literal: "Panagiotis Dimitrakis"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04991"

# Custom fields
paper_id: "2605.04991"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "quantum-computing"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quantum-reservoir-computing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:14:11Z"
created_at: "2026-05-07T05:14:11Z"
---

# Scalable Quantum Reservoir Computing over Distributed Quantum Architectures

**Authors**: Ioannis Liliopoulos, Georgios D. Varsamis, Konstantinos Rallis, Evangelos Tsipas, Ioannis G. Karafyllidis, Georgios Ch. Sirakoulis, Panagiotis Dimitrakis
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04991](https://arxiv.org/abs/2605.04991)

## Summary

This paper investigates the application of quantum reservoir computing to time-series forecasting, benchmarking four architectures that utilize single or distributed quantum reservoirs with ridge-regression readouts. By simulating both ideal and noisy hardware environments, the authors demonstrate that quantum-enhanced configurations significantly outperform classical baselines in prediction accuracy. Furthermore, they establish that distributed quantum architectures enable scalable and modular model deployment suitable for existing NISQ-era hardware platforms.

## Key Contributions

- Proposed four distinct distributed quantum reservoir computing architectures leveraging single/multiple reservoirs and readout layers.
- Demonstrated significant forecasting performance improvements over classical counterparts, achieving up to 78.8% MAE and 72.3% RMSE reduction.
- Validated the scalability and hardware-agnostic nature of distributed quantum reservoirs in noisy, NISQ-era simulation environments.

## Open Questions & Future Work

- [[optimal-quantum-circuit-design-distributed-rc]]

## Key Concepts

- [[quantum-reservoir-computing]]: A machine learning paradigm utilizing quantum hardware as a high-dimensional nonlinear dynamical reservoir for time-series processing.

## Archivist Review

The paper is approved for its methodological contribution to quantum reservoir computing. I have accepted the core concept of 'Quantum Reservoir Computing' and the specific open question regarding optimal quantum circuit design for distributed configurations. 'Distributed Quantum Architectures' was rejected as it is a high-level design pattern rather than a distinct, granular algorithmic mechanism.

### Approved Concepts
- Quantum Reservoir Computing: Provides the core methodological framework for integrating quantum hardware reservoirs into time-series forecasting tasks.

### Approved Open Questions
- Optimal Quantum Circuit Design: Identifying optimal quantum circuit configurations is essential for maximizing the forecasting accuracy and efficiency of distributed quantum reservoir architectures, as current choices are largely exploratory.

### Rejected Candidates
- [concept] Distributed Quantum Architectures (`distributed-quantum-architectures`) - subcomponent_of_broader_mechanism: This is a descriptive organizational property of the implementation rather than a standalone algorithmic method.

## Links

- [Abstract](https://arxiv.org/abs/2605.04991)
- [PDF](https://arxiv.org/pdf/2605.04991)

