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
  - "learning-debt"
architectures:
  []
datasets:
  - "CESNET-Timeseries24"
concept_slugs:
  - "boundary-profile-sensitivity-bps"
dataset_slugs:
  - "cesnet-timeseries24"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:07:04Z"
created_at: "2026-04-24T05:07:04Z"
---

# Temporal Taskification in Streaming Continual Learning: A Source of Evaluation Instability

**Authors**: Nicolae Filat, Ahmed Hussain, Konstantinos Kalogiannis, Elena Burceanu
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21930](https://arxiv.org/abs/2604.21930)

## Summary

This paper investigates the often-overlooked influence of temporal taskification in streaming continual learning, showing that arbitrary partitioning of data streams creates significant variance in evaluation metrics. By introducing a framework based on plasticity and stability profiles along with the Boundary-Profile Sensitivity (BPS) diagnostic, the authors demonstrate that different valid task splits can lead to contradictory benchmark conclusions for identical models. Evaluations using network traffic forecasting reveal that shorter task segments exacerbate distribution-level noise and sensitivity to boundary choices, highlighting the need to treat temporal taskification as a critical variable in continual learning research.

## Key Contributions

- Introduces a framework for analyzing the impact of temporal taskification on streaming continual learning, demonstrating that partition choices fundamentally alter benchmark outcomes.
- Defines Boundary-Profile Sensitivity (BPS) as a model-agnostic diagnostic for evaluating the stability of continual learning benchmarks against temporal partitioning.
- Empirical analysis on CESNET-Timeseries24 shows that shorter task durations significantly increase BPS, leading to higher variability in error, forgetting, and transfer metrics.

## Open Questions & Future Work

- [[adaptive-robust-streaming-taskification]]

## Key Concepts

- [[boundary-profile-sensitivity-bps]]: A diagnostic metric that quantifies how small perturbations in temporal task boundaries alter the distribution-level regimes in streaming continual learning.

## Archivist Review

I approved Boundary-Profile Sensitivity (BPS) as a novel, model-agnostic diagnostic for measuring evaluation stability in streaming continual learning. I also approved the open question regarding robust taskification to address the identified 'benchmark lottery' risk. CESNET-Timeseries24 was approved as the central evaluation dataset for this study. All other concepts and questions were rejected as either sub-components or generic future work.

### Approved Concepts
- Boundary-Profile Sensitivity (BPS): Provides a principled way to quantify the sensitivity of continual learning benchmarks to arbitrary temporal partitioning of data streams.

### Approved Open Questions
- Robust streaming taskification methods: If temporal taskification is a first-class evaluation variable, the current lack of objective, automated selection criteria contributes to 'benchmark lottery' effects in continual learning research.

## Datasets

- [[cesnet-timeseries24]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21930)
- [PDF](https://arxiv.org/pdf/2604.21930)

