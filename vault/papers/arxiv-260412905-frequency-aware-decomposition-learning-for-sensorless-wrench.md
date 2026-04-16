---
# CSL-compatible fields
title: "Frequency-aware Decomposition Learning for Sensorless Wrench Forecasting on a Vibration-rich Hydraulic Manipulator"
author:
  - literal: "Hyeonbeen Lee"
  - literal: "Min-Jae Jung"
  - literal: "Tae-Kyeong Yeu"
  - literal: "Jong-Boo Han"
  - literal: "Daegil Park"
  - literal: "Jin-Gyun Kim"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12905"

# Custom fields
paper_id: "2604.12905"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "robotics"
  - "transfer-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "frequency-aware-decomposition-network-fdn"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:07:44Z"
created_at: "2026-04-16T05:07:44Z"
---

# Frequency-aware Decomposition Learning for Sensorless Wrench Forecasting on a Vibration-rich Hydraulic Manipulator

**Authors**: Hyeonbeen Lee, Min-Jae Jung, Tae-Kyeong Yeu, Jong-Boo Han, Daegil Park, Jin-Gyun Kim
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12905](https://arxiv.org/abs/2604.12905)

## Summary

The Frequency-aware Decomposition Network (FDN) is introduced to address sensorless wrench forecasting in high-vibration robotic applications like grinding, where traditional methods struggle. By leveraging spectral decomposition and asymmetric prediction heads, the model treats the low-frequency signal deterministically and the high-frequency residual as a conditional distribution. FDN further integrates learned frequency filtering to adaptively improve input spectral representation. Empirical results on a 6-DoF hydraulic manipulator confirm that FDN significantly outperforms baseline models in high-frequency regimes and benefits from large-scale pretraining.

## Key Contributions

- Proposes the Frequency-aware Decomposition Network (FDN) for sensorless wrench forecasting in vibration-rich robotic environments.
- FDN utilizes an asymmetric architecture with deterministic heads for low-frequency signals and probabilistic heads for high-frequency residuals.
- Demonstrates superior forecasting performance on real-world grinding excavation data compared to existing baseline estimators and forecasters.
- Validates the effectiveness of cross-domain transfer learning from large-scale pretrained proprioceptive representations to downstream hydraulic manipulation tasks.

## Open Questions & Future Work

- [[generalization-scaling-wrench-estimation]]
- [[real-world-forecasting-deployment]]

## Key Concepts

- [[frequency-aware-decomposition-network-fdn]]: A forecasting architecture that spectrally decomposes signals to model low-frequency components deterministically and high-frequency residuals as conditional distributions.

## Archivist Review

I approved the FDN architecture because its hybrid decomposition (deterministic low-frequency + probabilistic high-frequency) is a powerful, reusable forecasting inductive bias. I also approved two open questions that delineate the path from offline research toward scalable foundation models and real-time deployment, respectively. Datasets were rejected as the paper did not propose a canonical named benchmark but rather evaluated on internal industrial data.

### Approved Concepts
- Frequency-aware Decomposition Network (FDN): The architecture introduces a distinct hybrid approach to forecasting by separating signals into deterministic and probabilistic components based on frequency.

### Approved Open Questions
- Scaling Sensorless Wrench Estimation: This addresses the core question of whether foundation model paradigms can effectively transfer to specialized robotic sensing and interaction tasks.
- Real-time Wrench Forecasting Deployment: Establishing the gap between offline accuracy and real-time control utility is essential for the industrial adoption of predictive sensing.

### Rejected Candidates
- [open_question] Generalization in Sensorless Wrench Estimation (`generalization-scaling-wrench-estimation`) - other: Renamed to 'Scaling Sensorless Wrench Estimation' for better conciseness and alignment with vault style.

## Links

- [Abstract](https://arxiv.org/abs/2604.12905)
- [PDF](https://arxiv.org/pdf/2604.12905)

