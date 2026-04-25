---
# CSL-compatible fields
title: "Temporal Taskification in Streaming Continual Learning: A Source of Evaluation Instability"
author:
  - literal: "Nicolae Filat"
  - literal: "Ahmed Hussain"
  - literal: "Konstantinos Kalogiannis"
  - literal: "Elena Burceanu"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21930"

# Custom fields
paper_id: "2604.21930"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "continual-learning"
  - "forecasting"
  - "evaluation-robustness"
architectures:
  []
datasets:
  - "CESNET-Timeseries24"
concept_slugs:
  - "boundary-profile-sensitivity-bps"
dataset_slugs:
  - "cesnet-timeseries24"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:53:54Z"
created_at: "2026-04-25T04:53:54Z"
---

# Temporal Taskification in Streaming Continual Learning: A Source of Evaluation Instability

**Authors**: Nicolae Filat, Ahmed Hussain, Konstantinos Kalogiannis, Elena Burceanu
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21930](https://arxiv.org/abs/2604.21930)

## Summary

This paper demonstrates that the common practice of partitioning continuous streams into discrete tasks (temporal taskification) in streaming continual learning is a critical, often ignored variable that induces evaluation instability. By analyzing network traffic forecasting benchmarks, the authors show that minor variations in temporal boundaries lead to significant discrepancies in model performance and forgetting metrics. To address this, they introduce Boundary-Profile Sensitivity (BPS), a diagnostic tool that measures how sensitive a stream's structure is to partitioning choices, suggesting that temporal taskification should be treated as a first-class evaluation parameter.

## Key Contributions

- Identified that temporal taskification—partitioning a continuous stream into discrete tasks—acts as a non-neutral structural component that biases continual learning (CL) evaluation conclusions.
- Introduced a framework to evaluate taskification quality using plasticity/stability profiles and structural distance metrics.
- Proposed Boundary-Profile Sensitivity (BPS) to quantify benchmark instability, demonstrating that varying split boundaries significantly alters metrics like forecasting error, forgetting, and backward transfer across diverse CL algorithms.

## Open Questions & Future Work

- [[adaptive-robust-taskification-streaming-cl]]

## Key Concepts

- [[boundary-profile-sensitivity-bps]]: A metric diagnosing how strongly small temporal boundary perturbations alter the induced distribution-level patterns before model training.

## Archivist Review

The paper provides a significant diagnostic framework for understanding evaluation instability in streaming continual learning. BPS is approved as a key concept because it formalizes a new way to quantify sensitivity to preprocessing, and the open question addresses the lack of adaptive methodologies for partitioning. CESNET-Timeseries24 is approved as it is the central dataset used to demonstrate these instability findings.

### Approved Concepts
- Boundary-Profile Sensitivity (BPS): It provides a novel, model-agnostic metric to quantify the impact of temporal partitioning choices on streaming continual learning regimes.

### Approved Open Questions
- Adaptive and Robust Taskification: This is critical because the current reliance on manual taskification introduces evaluation bias and instability that can undermine the validity of benchmark comparisons across different continual learning methods.

## Datasets

- [[cesnet-timeseries24]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21930)
- [PDF](https://arxiv.org/pdf/2604.21930)

