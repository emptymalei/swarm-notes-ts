---
# CSL-compatible fields
title: "Revealing the influence of participant failures on model quality in cross-silo Federated Learning"
author:
  - literal: "Fabian Stricker"
  - literal: "David Bermbach"
  - literal: "Christian Zirpins"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25289"

# Custom fields
paper_id: "2603.25289"
paper_source: "openalex"
domain: "machine-learning"
tags:
  - "federated learning"
  - "reliability"
  - "fault tolerance"
  - "data skew"
architectures:
  []
datasets:
  []
concept_slugs:
  - "participant-failure-impact-analysis-fl"
  - "model-utility-for-missing-participants"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:18:23Z"
created_at: "2026-03-29T20:18:23Z"
---

# Revealing the influence of participant failures on model quality in cross-silo Federated Learning

**Authors**: Fabian Stricker, David Bermbach, Christian Zirpins
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25289](https://arxiv.org/abs/2603.25289)

## Summary

This paper addresses the gap in systematically studying the impact of participant failures, specifically client dropouts, on the reliability of Federated Learning (FL) outcomes. The authors conduct extensive experiments across image, tabular, and time-series data to analyze how model performance is affected by missing participants, considering factors like data skewness and varying availability patterns. A key finding is the strong influence of data skewness, which can lead to overly optimistic model evaluations and modify the impact of other failure variables. Additionally, the study examines the post-training utility of the global model for the participants who were absent during training.

## Key Contributions

- Systematically investigated the impact of missing participants (client dropouts) on model performance across image, tabular, and time-series data in Federated Learning (FL).
- Quantified how factors like data skewness and participant availability patterns modulate the performance degradation caused by failures.
- Demonstrated that data skewness significantly influences model evaluation, potentially leading to overoptimistic results and altering the effects of other failure factors.
- Examined the resulting utility of the final global model specifically for the participants who were missing during the training process.

## Limitations

The study focuses on crash failures/missing participants but may not cover all fault scenarios like Byzantine failures or network partitioning in detail.

## Open Questions & Future Work

- [[contribution-metrics-without-server-data]]
- [[combinatorial-fim-analysis]]
- [[multi-participant-crash-impact]]
- [[generalizability-of-fim-results]]
- [[designing-adaptive-fault-tolerance]]

## Key Concepts

- [[participant-failure-impact-analysis-fl]]: A systematic analysis of how the absence of participants (client dropouts) affects model performance and utility in Federated Learning systems.
- [[model-utility-for-missing-participants]]: Evaluating the final aggregated Federated Learning model's performance specifically on the data of participants who experienced failures or dropouts.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 2 concept(s), 5 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Concepts
- Participant Failure Impact Analysis in FL: This is the central analytical contribution, systematically studying the effects of client dropouts on FL reliability.
- Model Utility for Missing Participants: Examining the utility of the final model specifically for the clients that failed to contribute is a novel and important perspective on fairness and utility.

### Approved Open Questions
- Client-side contribution measurement: The reliance on server-side data for accurate contribution metrics like SVs is a major impediment to deploying FL systems in settings where data sharing is prohibited, making a client-side or shared-data-free alternative essential for wider adoption.
- Analysis of interacting failure modifiers: Understanding the combinatorial effects of FIMs is critical because real-world FL failures rarely occur in isolation; systems must be designed to handle concurrent changes in data distribution, model complexity, and timing.
- Impact of concurrent participant failures: Real-world system failures, particularly network outages, often lead to correlated dropouts across multiple participants, making the simulation of multi-participant failure essential for building resilient FL systems.
- Validate results across architectures: Validating results across diverse data types, structures, and model complexities is necessary to ensure that derived guidance for fault-tolerance methods applies broadly to the heterogeneous environments where cross-silo FL is deployed.
- Design fault-tolerance methods: The ultimate goal of failure analysis is to translate observations into actionable, robust system designs, which requires developing concrete, adaptive fault-tolerance mechanisms based on the derived modifier knowledge.

### Rejected Candidates
- [dataset] time-series data (`time-series-data`) - generic: The dataset is mentioned generally as a data modality tested, not a specific named benchmark dataset central to the evaluation, thus it is too generic to warrant a note.

## Links

- [Abstract](https://arxiv.org/abs/2603.25289)
- [PDF](https://arxiv.org/pdf/2603.25289)

