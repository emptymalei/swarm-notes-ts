---
# CSL-compatible fields
title: "A Control Framework for Induced Seismicity Mitigation in Groningen Gas Reservoir"
author:
  - literal: "Diego Gutiérrez-Oribio"
  - literal: "Ioannis Stefanou"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26802"

# Custom fields
paper_id: "2604.26802"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "control-theory"
architectures:
  []
datasets:
  []
concept_slugs:
  - "control-oriented-induced-seismicity-mitigation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:09:28Z"
created_at: "2026-05-02T05:09:28Z"
---

# A Control Framework for Induced Seismicity Mitigation in Groningen Gas Reservoir

**Authors**: Diego Gutiérrez-Oribio, Ioannis Stefanou
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26802](https://arxiv.org/abs/2604.26802)

## Summary

This paper presents a control-oriented framework for managing gas extraction in the Groningen field to minimize induced seismicity. The approach integrates pore-pressure diffusion with seismicity rate dynamics and a stochastic event-generation process to simulate earthquake catalogs. By implementing a robust feedback controller that adjusts well-rate commands under operational constraints, the framework effectively regulates seismicity while optimizing production targets. The methodology is validated against historical data and demonstrated through numerical simulations of nitrogen reinjection and various control update scenarios.

## Key Contributions

- Introduces a control-oriented framework that couples pore-pressure diffusion with seismicity rate dynamics for operational gas extraction.
- Develops a stochastic event-generation procedure to derive synthetic earthquake catalogs from continuous seismicity rate fields.
- Designs a robust feedback controller that manages well-rate commands to regulate seismicity levels while satisfying production constraints and actuator saturation.

## Open Questions & Future Work

- [[real-time-seismicity-rate-estimation]]

## Key Concepts

- [[control-oriented-induced-seismicity-mitigation]]: A feedback control methodology that regulates extraction rates to minimize induced seismicity while satisfying production and actuator constraints.

## Archivist Review

The paper provides a significant advancement by framing induced seismicity as a closed-loop control problem rather than a pure forecasting one. I approved the control-oriented methodology as it is a foundational, reusable approach for complex industrial dynamics. The open question was approved for its recognition of the fundamental observability gap that limits feedback-based mitigation. I rejected the stochastic event-generation procedure as it is a subcomponent supporting the main controller rather than a standalone framework.

### Approved Concepts
- Control-oriented induced seismicity mitigation: It shifts the focus from passive seismicity forecasting to active operational regulation, bridging control theory with geophysics.

### Approved Open Questions
- Real-time seismicity rate estimation: The performance of any seismic mitigation feedback loop is directly limited by the accuracy, robustness, and temporal lag of the estimator used to map sparse event catalogs back to the continuous state-space controller.

## Links

- [Abstract](https://arxiv.org/abs/2604.26802)
- [PDF](https://arxiv.org/pdf/2604.26802)

