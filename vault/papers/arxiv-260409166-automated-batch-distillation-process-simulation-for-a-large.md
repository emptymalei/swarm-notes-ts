---
# CSL-compatible fields
title: "Automated Batch Distillation Process Simulation for a Large Hybrid Dataset for Deep Anomaly Detection"
author:
  - literal: "Jennifer Werner"
  - literal: "Justus Arweiler"
  - literal: "Indra Jungjohann"
  - literal: "Jochen Schmid"
  - literal: "Fabian Jirasek"
  - literal: "Hans Hasse"
  - literal: "Michael Bortz"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.09166"

# Custom fields
paper_id: "2604.09166"
paper_source: "arxiv"
domain: "nlp"
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
processed_at: "2026-04-13T05:09:27Z"
created_at: "2026-04-13T05:09:27Z"
---

# Automated Batch Distillation Process Simulation for a Large Hybrid Dataset for Deep Anomaly Detection

**Authors**: Jennifer Werner, Justus Arweiler, Indra Jungjohann, Jochen Schmid, Fabian Jirasek, Hans Hasse, Michael Bortz
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.09166](https://arxiv.org/abs/2604.09166)

## Summary

This paper addresses the scarcity of labeled training data for deep anomaly detection in industrial chemical processes by creating a hybrid dataset of experimental and simulated batch distillation data. The authors propose an automated simulation workflow that translates experimental metadata into consistent simulation scenarios using a tailored differential-algebraic equation solver. By calibrating the simulator to a single reference run, they successfully generate large-scale time-series data covering various operating conditions and anomalies, facilitating future research into simulation-to-experiment style transfer and robust anomaly detection models.

## Key Contributions

- Introduces an automated workflow that translates experimental batch distillation records into high-fidelity simulation scenarios for hybrid dataset creation.
- Develops a novel Python-based process simulator using index-reduction for differential-algebraic equations to predict diverse industrial process dynamics.
- Demonstrates that calibrating simulations to a single reference experiment allows for consistent, large-scale generation of normal and anomalous time-series data.

## Open Questions & Future Work

- [[modeling-non-actuator-process-anomalies]]
- [[simulation-to-experiment-style-transfer]]

## Archivist Review

The paper presents a specific simulation-based pipeline for chemical process data. While valuable, the methodology is domain-specific to batch distillation and the index-reduction strategy is a standard engineering technique rather than a reusable ML concept. I approved two open questions that capture the fundamental bottlenecks in chemical process anomaly detection: the limitations of current simulation physics and the simulation-to-reality domain shift.

### Approved Open Questions
- Modeling Non-Actuator Process Anomalies: Bridging this modeling gap is critical for creating high-fidelity, comprehensive datasets that enable the training of robust machine learning models capable of detecting diverse, non-linear, and non-actuator-related fault scenarios.
- Simulation-to-Experiment Style Transfer: This is essential for the practical deployment of simulation-trained anomaly detection systems in real-world industrial environments where perfectly labeled, noise-free data is often unavailable.

## Links

- [Abstract](https://arxiv.org/abs/2604.09166)
- [PDF](https://arxiv.org/pdf/2604.09166)

