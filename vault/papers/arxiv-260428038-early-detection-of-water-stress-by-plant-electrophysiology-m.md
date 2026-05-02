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
  - "time-series"
  - "precision-agriculture"
  - "machine-learning-for-science"
architectures:
  []
datasets:
  []
concept_slugs:
  - "biofeedback-driven-precision-irrigation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:07:21Z"
created_at: "2026-05-02T05:07:21Z"
---

# Early Detection of Water Stress by Plant Electrophysiology: Machine Learning for Irrigation Management

**Authors**: Eduard Buss, Till Aust, Heiko Hamann
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28038](https://arxiv.org/abs/2604.28038)

## Summary

This study introduces a machine learning-based decision-support framework to detect early-stage water stress in plants using electrophysiological signal monitoring. By analyzing time-series data from greenhouse-grown tomato plants, the authors developed a processing pipeline involving statistical feature extraction, sequential backward feature selection, and probability calibration. The resulting model achieves 92% accuracy, outperforming deep learning baselines, and successfully generalizes to unseen recordings to enable biofeedback-driven irrigation control.

## Key Contributions

- Developed an end-to-end processing pipeline for online plant stress detection using electrophysiological signals.
- Identified a 30-minute look-back window as optimal for balancing rapid response and classification accuracy.
- Demonstrated that automated machine learning outperforms deep learning on this task, achieving 92% classification accuracy.

## Key Concepts

- [[biofeedback-driven-precision-irrigation]]: A closed-loop irrigation framework that uses real-time electrophysiological plant stress signals to dynamically optimize water application.

## Archivist Review

I focused on extracting the core paradigm shift—transitioning from static or sensor-based environment monitoring to active, biological signal-driven control—rather than the specific application to tomato plants. The rejection of the specific plant-electrophysiology concept avoids overly narrow entries that fail to capture the broader methodological contribution of the paper. I applied a strict filter to ensure that only the transferable decision-support framework was archived.

### Approved Concepts
- Biofeedback-Driven Precision Irrigation: Shifts the paradigm from reactive or schedule-based irrigation to adaptive, signal-based biofeedback, which is a significant advancement in precision agriculture.

### Rejected Candidates
- [concept] Plant Electrophysiology Water Stress Detection (`plant-electrophysiology-water-stress-detection`) - subcomponent_of_broader_mechanism: This is a specific application instance rather than a broadly reusable methodological concept, and it is better captured by the more general biofeedback irrigation framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.28038)
- [PDF](https://arxiv.org/pdf/2604.28038)

