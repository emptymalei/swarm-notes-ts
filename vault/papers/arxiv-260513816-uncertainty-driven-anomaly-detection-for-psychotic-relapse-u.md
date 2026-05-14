---
# CSL-compatible fields
title: "Uncertainty-Driven Anomaly Detection for Psychotic Relapse Using Smartwatches: Forecasting and Multi-Task Learning Fusion"
author:
  - literal: "Nikolaos Tsalkitzis"
  - literal: "Panagiotis P. Filntisis"
  - literal: "Petros Maragos"
  - literal: "Niki Efthymiou"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13816"

# Custom fields
paper_id: "2605.13816"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "2nd-e-prevention-grand-challenge-dataset"
concept_slugs:
  - "uncertainty-driven-anomaly-detection"
dataset_slugs:
  - "2nd-e-prevention-grand-challenge-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:22:39Z"
created_at: "2026-05-14T05:22:39Z"
---

# Uncertainty-Driven Anomaly Detection for Psychotic Relapse Using Smartwatches: Forecasting and Multi-Task Learning Fusion

**Authors**: Nikolaos Tsalkitzis, Panagiotis P. Filntisis, Petros Maragos, Niki Efthymiou
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13816](https://arxiv.org/abs/2605.13816)

## Summary

This paper presents two smartwatch-based frameworks for detecting psychotic relapse through continuous physiological monitoring. One framework employs predictive forecasting of cardiac dynamics, while the other utilizes multi-task learning to integrate sleep, motion, and cardiac features into time-aware embeddings. The researchers demonstrate that these approaches capture complementary physiological signatures and propose a late-fusion strategy to combine their respective anomaly scores. The resulting system achieves superior performance on the 2nd e-Prevention Grand Challenge dataset, highlighting the value of uncertainty-aware multi-modal fusion for real-world digital phenotyping.

## Key Contributions

- Developed two complementary smartwatch-based frameworks: one forecasting cardiac dynamics and another multi-task learning for sleep/motion/cardiac integration.
- Proposed a late-fusion strategy that combines anomaly scores from both frameworks to improve detection fidelity.
- Achieved an 8% relative improvement over the competition-winning baseline on the 2nd e-Prevention Grand Challenge dataset.

## Open Questions & Future Work

- [[early-fusion-for-multimodal-relapse-detection]]

## Key Concepts

- [[uncertainty-driven-anomaly-detection]]: A robust anomaly detection approach for wearable data that utilizes predictive uncertainty as a primary indicator of physiological abnormality.

## Archivist Review

The review focused on identifying the core mechanism—uncertainty-driven anomaly detection in wearable contexts—and a substantial research question regarding the fusion architecture of multi-modal time-series. These represent high-level methodological contributions rather than local implementation details. The dataset, as a named competition challenge, is approved for its benchmark relevance in clinical digital phenotyping.

### Approved Concepts
- Uncertainty-Driven Anomaly Detection: Central mechanism for robustness in noisy real-world wearable data.

### Approved Open Questions
- Early Fusion for Relapse Detection: Current state-of-the-art results for this task rely on late-fusion of independent models; moving to early fusion could potentially uncover more complex, hidden correlations between physiological modalities that are critical for higher-fidelity clinical predictions.

## Datasets

- [[2nd-e-prevention-grand-challenge-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.13816)
- [PDF](https://arxiv.org/pdf/2605.13816)

