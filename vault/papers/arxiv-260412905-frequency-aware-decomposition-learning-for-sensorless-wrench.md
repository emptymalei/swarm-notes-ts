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
  - "forecasting"
  - "time-series"
  - "transfer-learning"
  - "robotics"
  - "probabilistic-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "frequency-aware-spectral-decomposition"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:02:53Z"
created_at: "2026-04-15T05:02:53Z"
---

# Frequency-aware Decomposition Learning for Sensorless Wrench Forecasting on a Vibration-rich Hydraulic Manipulator

**Authors**: Hyeonbeen Lee, Min-Jae Jung, Tae-Kyeong Yeu, Jong-Boo Han, Daegil Park, Jin-Gyun Kim
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12905](https://arxiv.org/abs/2604.12905)

## Summary

The paper presents the Frequency-aware Decomposition Network (FDN) to enable sensorless wrench forecasting for robots operating in high-vibration environments like grinding. FDN improves upon existing methods by spectrally decomposing the wrench signal, using a deterministic head for predictable components and a probabilistic head for high-frequency residuals. The model incorporates learned input filtering and frequency-band priors to refine spectral awareness. Evaluation on a 6-DoF hydraulic manipulator shows superior forecasting performance compared to standard baselines, particularly in capturing challenging high-frequency dynamics.

## Key Contributions

- Introduced the Frequency-aware Decomposition Network (FDN) which utilizes asymmetric heads to model low-frequency deterministic wrench and high-frequency probabilistic residuals.
- Demonstrated effective sensorless wrench forecasting on a 6-DoF hydraulic manipulator during high-frequency grinding tasks, outperforming baseline models in the high-frequency spectrum.
- Verified the efficacy of large-scale pretraining and transfer learning for proprioception-to-wrench mapping, facilitating improved performance in downstream robotic interaction scenarios.

## Open Questions & Future Work

- [[generalization-bounds-for-sensorless-wrench-forecasting]]

## Key Concepts

- [[frequency-aware-spectral-decomposition]]: A forecasting paradigm that partitions signal components into frequency-specific bands, using deterministic heads for trend and probabilistic heads for high-frequency residuals.

## Archivist Review

I approved the frequency-aware spectral decomposition concept as it generalizes the paper's core innovation—the dual-head modeling of deterministic and stochastic spectral components—into a reusable time-series modeling pattern. I rejected the FDN architecture itself as being too paper-specific. I approved one focused open question regarding generalization bounds for sensorless forecasting, while rejecting the other as generic boilerplate regarding scaling behavior.

### Approved Concepts
- Frequency-Aware Spectral Decomposition: The dual-head architecture separating low-frequency deterministic components from high-frequency probabilistic residuals provides a robust paradigm for modeling multi-modal, vibration-heavy time series.

### Approved Open Questions
- Generalization Bounds for Sensorless Forecasting: Determining the boundaries of generalization for proprioceptive-to-wrench mapping is necessary to move beyond isolated case studies toward universal, robust robotic interaction models.

### Rejected Candidates
- [concept] Frequency-aware Decomposition Network (FDN) (`frequency-aware-decomposition-network-fdn`) - subcomponent_of_broader_mechanism: The specific network architecture is a paper-local implementation; the underlying decomposition mechanism is more abstractly useful and has been captured as a broader concept.
- [open_question] Scaling and transfer in wrench estimation (`scaling-and-transfer-in-wrench-estimation`) - generic: This covers standard empirical desiderata (scaling and few-shot generalization) that are too broad and boilerplate for a specialized vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.12905)
- [PDF](https://arxiv.org/pdf/2604.12905)

