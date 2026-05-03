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
  - "quantum-machine-learning"
  - "time-series-forecasting"
  - "data-augmentation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "split-ensemble-training"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:13:55Z"
created_at: "2026-05-03T05:13:55Z"
---

# Reorganizing Quantum Measurement Records Improves Time-Series Prediction

**Authors**: Markus Baumann, Maximilian Zorn, Thomas Gabor, Claudia Linnhoff-Popien, Jonas Stein
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28160](https://arxiv.org/abs/2604.28160)

## Summary

This paper introduces split-ensemble training, a method to enhance time-series prediction in quantum reservoir computing by reorganizing quantum measurement records. Instead of averaging all shots into a single feature vector, the authors partition shots into multiple groups, providing more training examples to the classical readout while maintaining the same measurement budget. Experimental results demonstrate that this approach consistently outperforms traditional full-averaging, particularly in noisy real-world quantum hardware environments.

## Key Contributions

- Introduced split-ensemble training, an approach that increases training data volume by partitioning quantum measurement shots without additional hardware cost.
- Demonstrated that split-ensemble training significantly improves predictive performance in quantum reservoir computing compared to standard full-averaging methods.
- Validated the effectiveness of the method across both simulated forecasting benchmarks and real quantum hardware, with the largest performance gains observed on physical hardware.

## Open Questions & Future Work

- [[optimal-group-size-selection-in-split-ensemble-training]]

## Key Concepts

- [[split-ensemble-training]]: A technique that partitions quantum measurement shots into multiple groups to provide more training examples for the classical readout in quantum reservoir computing.

## Archivist Review

I approved the concept of split-ensemble training as a novel, reusable mechanism for addressing the noise-vs-data-sparsity trade-off in quantum-classical hybrid systems. The open question regarding optimal group sizing was also approved, as it addresses a key practical bottleneck for implementing this method across different hardware environments. No other concepts or datasets were submitted that met the high threshold for standalone archival.

### Approved Concepts
- Split-ensemble training: It provides a novel data-augmentation technique for quantum machine learning by increasing training sample count without additional quantum hardware cost.

### Approved Open Questions
- Optimal Group Size Selection: Developing a rigorous, analytical rule for optimal shot-record organization would eliminate the need for computationally expensive empirical search, making the method more efficient and scalable for quantum reservoir computing.

## Links

- [Abstract](https://arxiv.org/abs/2604.28160)
- [PDF](https://arxiv.org/pdf/2604.28160)

