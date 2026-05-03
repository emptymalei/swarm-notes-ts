---
# CSL-compatible fields
title: "Early Detection of Water Stress by Plant Electrophysiology: Machine Learning for Irrigation Management"
author:
  - literal: "Eduard Buss"
  - literal: "Till Aust"
  - literal: "Heiko Hamann"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28038"

# Custom fields
paper_id: "2604.28038"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "biofeedback-driven-precision-irrigation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:14:05Z"
created_at: "2026-05-03T05:14:05Z"
---

# Early Detection of Water Stress by Plant Electrophysiology: Machine Learning for Irrigation Management

**Authors**: Eduard Buss, Till Aust, Heiko Hamann
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28038](https://arxiv.org/abs/2604.28038)

## Summary

This study introduces a machine learning-based framework for the early detection of water stress in greenhouse-grown tomato plants using electrophysiological signal analysis. By processing time-series data through a pipeline of statistical feature extraction, feature selection, and probability calibration, the authors achieve high classification accuracy in identifying plant stress before visible symptoms manifest. Their findings indicate that a 30-minute historical window is optimal for effective decision-making in precision irrigation, providing a robust foundation for automated biofeedback-driven crop management.

## Key Contributions

- Demonstrated that a 30-minute look-back window on plant electrophysiological signals optimizes the trade-off between rapid detection and accuracy for water stress identification.
- Achieved 92% classification accuracy for water stress detection using automated machine learning, outperforming deep learning baselines.
- Proposed a decision-support framework that successfully generalizes to unseen plant recordings, facilitating autonomous irrigation management.

## Key Concepts

- [[biofeedback-driven-precision-irrigation]]: An irrigation control paradigm that uses real-time plant physiological signals as feedback for automated water management.

## Archivist Review

I approved the 'biofeedback-driven-precision-irrigation' concept as it defines a novel control loop paradigm that generalizes across various physiological sensing applications in agriculture. I rejected the '30-minute look-back window' as it is a specific hyperparameter tuning result unique to this experimental setup and does not constitute a reusable methodological contribution.

### Approved Concepts
- biofeedback-driven-precision-irrigation: This framework shifts irrigation from time-based or soil-moisture-based scheduling to direct physiological response, which is a major shift in precision agriculture.

### Rejected Candidates
- [concept] 30-minute-look-back-window (`30-minute-look-back-window`) - paper_local: This is a specific hyperparameter optimization result rather than a reusable architectural principle.

## Links

- [Abstract](https://arxiv.org/abs/2604.28038)
- [PDF](https://arxiv.org/pdf/2604.28038)

