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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "split-ensemble-training"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:21:49Z"
created_at: "2026-05-01T05:21:49Z"
---

# Reorganizing Quantum Measurement Records Improves Time-Series Prediction

**Authors**: Markus Baumann, Maximilian Zorn, Thomas Gabor, Claudia Linnhoff-Popien, Jonas Stein
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28160](https://arxiv.org/abs/2604.28160)

## Summary

This paper addresses the limited sample efficiency of quantum reservoir computing caused by the standard practice of aggregating all quantum measurement shots into a single feature vector per time step. The authors introduce 'split-ensemble training,' which partitions these shot records into multiple partially-denoised feature vectors to provide the readout layer with more training instances. By maintaining the same measurement budget while increasing the training data diversity, the method improves prediction accuracy, particularly on noisy real-world quantum hardware. Experimental results show this simple reorganization offers a cost-effective way to boost performance in near-term quantum time-series forecasting.

## Key Contributions

- Introduces split-ensemble training, a data-reorganization technique for quantum reservoir computing that partitions measurement shot records into multiple feature vectors instead of a single average.
- Demonstrates significant improvement in time-series forecasting performance on real quantum hardware by increasing the number of effective training examples under a fixed measurement budget.
- Provides an architecture-agnostic algorithmic lever for enhancing near-term quantum machine learning models without increasing circuit execution costs or depth.

## Open Questions & Future Work

- [[generalization-of-shot-organization-effects]]

## Key Concepts

- [[split-ensemble-training]]: A data-reorganization method for quantum reservoir computing that partitions measurement shot records into multiple partially-denoised feature vectors to expand the training set.

## Archivist Review

I have approved 'split-ensemble training' as a distinct, reusable algorithmic technique for quantum-classical hybrid systems. The open question regarding the generalization of shot-organization strategies is also approved as it identifies a critical boundary for performance optimization in quantum learning. All other candidates were rejected to maintain the high-quality threshold of the vault.

### Approved Concepts
- Split-ensemble training: This is a novel algorithmic technique to improve data efficiency in quantum reservoir computing without requiring additional quantum hardware resources.

### Approved Open Questions
- Generalization of shot-organization strategies: Determining the universality of these benefits is key to scaling and optimizing near-term quantum machine learning models.

## Links

- [Abstract](https://arxiv.org/abs/2604.28160)
- [PDF](https://arxiv.org/pdf/2604.28160)

