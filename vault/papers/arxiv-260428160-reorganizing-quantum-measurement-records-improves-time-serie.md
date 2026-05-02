---
# CSL-compatible fields
title: "Reorganizing Quantum Measurement Records Improves Time-Series Prediction"
author:
  - literal: "Markus Baumann"
  - literal: "Maximilian Zorn"
  - literal: "Thomas Gabor"
  - literal: "Claudia Linnhoff-Popien"
  - literal: "Jonas Stein"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28160"

# Custom fields
paper_id: "2604.28160"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "quantum-reservoir-computing"
  - "time-series-forecasting"
  - "shot-noise-mitigation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "split-ensemble-training"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:07:11Z"
created_at: "2026-05-02T05:07:11Z"
---

# Reorganizing Quantum Measurement Records Improves Time-Series Prediction

**Authors**: Markus Baumann, Maximilian Zorn, Thomas Gabor, Claudia Linnhoff-Popien, Jonas Stein
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28160](https://arxiv.org/abs/2604.28160)

## Summary

This paper addresses the data-efficiency bottleneck in quantum reservoir computing caused by aggregating all measurement shots into a single feature vector per time step. The authors introduce split-ensemble training, a method that partitions measurement records into smaller groups to create multiple partially denoised training examples for each target. This simple reorganization of measurement records increases the effective training volume without requiring additional quantum circuit executions. Empirical results confirm that this technique significantly improves time-series forecasting accuracy, especially on noisy real-world quantum hardware.

## Key Contributions

- Introduced split-ensemble training to increase effective training data for quantum reservoir computing without increasing quantum hardware costs.
- Demonstrated consistent improvements in forecasting performance on both simulated benchmarks and real quantum hardware.
- Showed that partitioning measurement shots into multiple feature vectors mitigates limitations caused by small training datasets.

## Open Questions & Future Work

- [[split-ensemble-qrc-optimization-limits]]

## Key Concepts

- [[split-ensemble-training]]: A technique that partitions quantum measurement shots into smaller groups to generate multiple training feature vectors from a single measurement step.

## Archivist Review

The paper introduces an algorithmic lever, split-ensemble training, to effectively multiply the training data for quantum reservoir computing by reorganizing measurement shots. This concept is novel, reusable, and addresses a fundamental trade-off in current quantum machine learning between feature noise and sample size. I have approved the concept and a refined open question regarding the optimization of this technique.

### Approved Concepts
- Split-ensemble training: It provides a novel, cost-free method to increase the effective training set size for quantum reservoir computing by manipulating existing measurement data.

### Approved Open Questions
- Split-ensemble QRC optimization limits: Understanding the limits and versatility of shot-record organization is critical for optimizing near-term quantum learning without increasing the hardware execution budget.

## Links

- [Abstract](https://arxiv.org/abs/2604.28160)
- [PDF](https://arxiv.org/pdf/2604.28160)

