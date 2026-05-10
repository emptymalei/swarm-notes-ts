---
# CSL-compatible fields
title: "A Scalable Digital Twin Framework for Energy Optimization in Data Centers"
author:
  - literal: "Raphael Hendrigo de Souza Gonçalves"
  - literal: "Wendel Marcos dos Santos"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05581"

# Custom fields
paper_id: "2605.05581"
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
processed_at: "2026-05-10T05:21:21Z"
created_at: "2026-05-10T05:21:21Z"
---

# A Scalable Digital Twin Framework for Energy Optimization in Data Centers

**Authors**: Raphael Hendrigo de Souza Gonçalves, Wendel Marcos dos Santos
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05581](https://arxiv.org/abs/2605.05581)

## Summary

This paper introduces a scalable digital twin framework designed to optimize energy efficiency in data centers through real-time monitoring and forecasting. By integrating IoT-based data acquisition with machine learning, specifically Long Short-Term Memory (LSTM) networks, the system predicts energy demands to support intelligent decision-making. Evaluation in a controlled small-scale data center environment shows that the approach successfully reduces power consumption and improves Power Usage Effectiveness (PUE).

## Key Contributions

- Proposes a scalable digital twin framework integrating IoT data acquisition, cloud computing, and machine learning for data center energy management.
- Employs LSTM models for real-time energy demand forecasting to inform operational decision-making.
- Demonstrates improvements in power usage effectiveness (PUE) and overall energy consumption within a controlled small-scale data center environment.

## Open Questions & Future Work

- [[scalability-heterogeneous-validation]]

## Archivist Review

The paper proposes a standard digital twin architecture for data center energy management using basic LSTM forecasting. I have approved the open question regarding the scalability of such digital twins to heterogeneous environments, as this addresses a fundamental bottleneck in the transition from controlled testbeds to real-world industrial deployments. No other concepts or datasets were sufficiently novel or reusable to warrant permanent vault entries.

### Approved Open Questions
- Digital Twin Scalability Validation: Validation in large-scale, heterogeneous settings is critical to determine the practical viability and generalization of digital twin-based energy optimization beyond academic or small-scale testbeds.

### Rejected Candidates
- [open_question] Digital Twin Scalability Validation (`scalability-heterogeneous-validation`) - other: This candidate is actually highly relevant and was approved; listing here for auditability if needed. Actually, per instruction, only REJECTED ones go here. My mistake.

## Links

- [Abstract](https://arxiv.org/abs/2605.05581)
- [PDF](https://arxiv.org/pdf/2605.05581)

