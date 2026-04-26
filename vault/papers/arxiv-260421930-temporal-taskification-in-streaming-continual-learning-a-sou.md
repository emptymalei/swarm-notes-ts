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
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "cesnet-timeseries24"
concept_slugs:
  - "boundary-profile-sensitivity-bps"
dataset_slugs:
  - "cesnet-timeseries24"
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:07:39Z"
created_at: "2026-04-26T05:07:39Z"
---

# Temporal Taskification in Streaming Continual Learning: A Source of Evaluation Instability

**Authors**: Nicolae Filat, Ahmed Hussain, Konstantinos Kalogiannis, Elena Burceanu
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21930](https://arxiv.org/abs/2604.21930)

## Summary

This paper investigates the often-overlooked impact of temporal taskification—the process of splitting continuous data streams into discrete tasks—on streaming continual learning (CL) evaluation. By keeping the model and stream fixed while varying temporal split boundaries, the authors demonstrate that different valid taskifications lead to drastically different benchmarking conclusions. The study introduces Boundary-Profile Sensitivity (BPS) as a novel framework to diagnose the structural instability inherent in task partitioning and advocates for treating taskification as a primary variable in future CL research.

## Key Contributions

- Demonstrates that temporal taskification is a first-class evaluation variable that significantly impacts CL metrics such as forecasting error, forgetting, and backward transfer.
- Introduces Boundary-Profile Sensitivity (BPS) as a diagnostic tool to assess the stability of temporal partitioning schemes prior to model training.
- Shows that shorter temporal task windows consistently result in higher instability, increased structural distances, and greater susceptibility to perturbation-induced benchmark variation.

## Open Questions & Future Work

- [[robust-temporal-taskification-selection]]

## Key Concepts

- [[boundary-profile-sensitivity-bps]]: A metric that measures how significantly small temporal boundary shifts impact the statistical regime of a continual learning data stream prior to model training.

## Archivist Review

The paper successfully identifies a critical, overlooked vulnerability in streaming continual learning benchmarks: the sensitivity of performance conclusions to the choice of temporal task partitioning. I have approved the BPS diagnostic concept as a reusable evaluation metric, the CESNET-Timeseries24 dataset as a specific, non-generic benchmark, and an open question focused on the development of robust taskification strategies. Other candidates were not proposed, and no other concepts or datasets warranted standalone status under the strict scarcity policy.

### Approved Concepts
- Boundary-Profile Sensitivity (BPS): BPS provides a model-agnostic metric for evaluating the structural stability of temporal taskification in continual learning, which is a major, previously unquantified, source of benchmarking noise.

### Approved Open Questions
- Optimal and Robust Taskification: Establishing a methodology for selecting robust taskifications is critical to ensuring that benchmarking conclusions in streaming continual learning are intrinsic to the models being evaluated rather than artifacts of the chosen segmentation.

## Datasets

- [[cesnet-timeseries24]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21930)
- [PDF](https://arxiv.org/pdf/2604.21930)

