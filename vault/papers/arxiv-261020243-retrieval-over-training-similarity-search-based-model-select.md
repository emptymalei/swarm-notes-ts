---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Retrieval Over Training: Similarity search-based Model Selection for Time Series Anomaly Detection"
description: "The paper introduces RAMSAD, a retrieval-based framework for model selection in time-series anomaly detection, addressing the limitation that no single detector works across all data types. Unlike traditional meta-learning approaches that train predictors, RAMSAD queries a knowledge base of historical performance profiles to identify the top-k most similar time series and transfers their detector recommendations. This similarity-based approach outperforms existing baselines in In-Distribution settings and shows superior robustness in Out-of-Distribution scenarios. Furthermore, RAMSAD matches the performance of large detector ensembles while executing only a fraction of the models, offering a highly efficient solution for scalable anomaly detection."
resource: "https://arxiv.org/abs/2610.20243"
tags:
  - "time-series-anomaly-detection"
  - "model-selection"
  - "anomaly-detection"
  - "similarity-search"
  - "out-of-distribution"
  - "benchmarking"
  - "efficiency"
timestamp: "2026-10-18T00:34:16Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Christos Panourgias"
  - literal: "Roberto Stanzione"
  - literal: "Adrien Petralia"
  - literal: "Themis Palpanas"
  - literal: "Paul Boniol"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20243"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "ramsad"
    description: "A retrieval-augmented framework that selects time-series anomaly detectors by querying a knowledge base of performance profiles from similar historical instances rather than training a meta-regressor."
datasets:
  []
open_questions:
  - name: "retrieval-model-selection-cold-start"
    description: "How can retrieval-based model selection systems be optimized to maintain performance when the query time series has no close neighbors in the existing knowledge base (i.e., cold-start or extreme OOD scenarios)?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:34:16Z"
created_at: "2026-10-18T00:34:16Z"
---

# Retrieval Over Training: Similarity search-based Model Selection for Time Series Anomaly Detection

**Authors**: Christos Panourgias, Roberto Stanzione, Adrien Petralia, Themis Palpanas, Paul Boniol
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20243](https://arxiv.org/abs/2610.20243)

## Summary

The paper introduces RAMSAD, a retrieval-based framework for model selection in time-series anomaly detection, addressing the limitation that no single detector works across all data types. Unlike traditional meta-learning approaches that train predictors, RAMSAD queries a knowledge base of historical performance profiles to identify the top-k most similar time series and transfers their detector recommendations. This similarity-based approach outperforms existing baselines in In-Distribution settings and shows superior robustness in Out-of-Distribution scenarios. Furthermore, RAMSAD matches the performance of large detector ensembles while executing only a fraction of the models, offering a highly efficient solution for scalable anomaly detection.

## Key Contributions

- Proposed RAMSAD, a retrieval-based framework for time-series anomaly detection model selection that bypasses the need for training complex meta-regressors.
- Demonstrated that similarity-based retrieval provides significantly higher robustness in Out-of-Distribution (OOD) settings compared to state-of-the-art training-based model selectors.
- Achieved performance levels matching or exceeding full ensemble methods while using only a small subset of detectors, leading to substantial computational efficiency gains.

## Limitations

The abstract does not specify the overhead of maintaining or querying the knowledge base as it scales, nor does it address how to handle cases where no similar series exist in the database.

## Open Questions & Future Work

- [[retrieval-model-selection-cold-start]]

## Key Concepts

- [[ramsad]]: A retrieval-augmented framework that selects time-series anomaly detectors by querying a knowledge base of performance profiles from similar historical instances rather than training a meta-regressor.

## Archivist Review

Approved RAMSAD as a novel retrieval-based approach to model selection in time series, which offers a distinct alternative to traditional meta-learning. The open question on knowledge base density targets a fundamental limitation of retrieval-augmented systems in sparse or novel data regimes. No datasets were approved as none were specifically named in the abstract.

### Approved Concepts
- RAMSAD: RAMSAD introduces a retrieval-based paradigm for model selection, specifically addressing the failure of traditional meta-learning (training-based) approaches in out-of-distribution (OOD) scenarios.

### Approved Open Questions
- Knowledge Base Density in Retrieval Selection: Standard retrieval mechanisms degrade when data density is low, which is a critical failure mode for anomaly detection in evolving industrial or financial environments.

## Links

- [Abstract](https://arxiv.org/abs/2610.20243)
- [PDF](https://arxiv.org/pdf/2610.20243)

