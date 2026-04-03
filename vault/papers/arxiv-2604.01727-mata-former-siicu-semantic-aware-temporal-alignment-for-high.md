---
# CSL-compatible fields
title: "MATA-Former & SIICU: Semantic Aware Temporal Alignment for High-Fidelity ICU Risk Prediction"
author:
  - literal: "Zhichong Zheng"
  - literal: "Xiaohang Nie"
  - literal: "Xueqi Wang"
  - literal: "Yuanjin Zhao"
  - literal: "Haitao Zhang"
  - literal: "Yichao Tang"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.01727"

# Custom fields
paper_id: "2604.01727"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "siicu"
concept_slugs:
  - "semantic-aware-temporal-alignment"
  - "plateau-gaussian-soft-labeling"
dataset_slugs:
  - "siicu"
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:20:10Z"
created_at: "2026-04-03T05:20:10Z"
---

# MATA-Former & SIICU: Semantic Aware Temporal Alignment for High-Fidelity ICU Risk Prediction

**Authors**: Zhichong Zheng, Xiaohang Nie, Xueqi Wang, Yuanjin Zhao, Haitao Zhang, Yichao Tang
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.01727](https://arxiv.org/abs/2604.01727)

## Summary

MATA-Former addresses the limitations of standard transformer architectures in clinical settings by using event-driven semantic alignment to prioritize causal dependencies over raw chronological time. To improve risk prediction fidelity, the authors introduce Plateau-Gaussian Soft Labeling (PSL), which enables multi-horizon trajectory regression instead of conventional binary classification. The framework's efficacy is demonstrated through extensive evaluations on both the novel SIICU dataset and the established MIMIC-IV benchmark.

## Key Contributions

- Introduces MATA-Former, which uses event semantics to dynamically adjust attention weights for improved clinical causal alignment in time-series forecasting.
- Proposes Plateau-Gaussian Soft Labeling (PSL) to transform binary clinical risk classification into a continuous multi-horizon regression task for more granular trajectory modeling.
- Achieves superior performance on the newly constructed SIICU dataset and the benchmark MIMIC-IV dataset, demonstrating robustness in irregular, text-heavy clinical data.

## Open Questions & Future Work

- [[cross-center-generalization-clinical-models]]

## Key Concepts

- [[semantic-aware-temporal-alignment]]: A mechanism that dynamically adjusts attention weights using event-level semantic information to prioritize causal clinical relationships over raw chronological proximity.
- [[plateau-gaussian-soft-labeling]]: A label transformation technique that reformulates binary event classification into continuous regression targets to better capture risk trajectories.

## Archivist Review

Approved the core transformer-based mechanism (Semantic-Aware Temporal Alignment) and the soft labeling technique, as both provide reusable methodological contributions for clinical time-series forecasting. SIICU was approved as a high-fidelity benchmark, while one open question on cross-center generalization was selected for its critical impact on clinical translation. The second open question was rejected as too generic.

### Approved Concepts
- Semantic-Aware Temporal Alignment: Represents a shift from standard chronological attention to domain-specific causal alignment in irregular time series.
- Plateau-Gaussian Soft Labeling: Provides a continuous, gradient-friendly target for binary classification problems, facilitating multi-horizon forecasting.

### Approved Open Questions
- Cross-Center Generalization Challenges: Essential for clinical safety and broad adoption of any predictive model in real-world healthcare settings.

### Rejected Candidates
- [open_question] Multimodal Clinical Data Integration (`multimodal-clinical-data-integration`) - generic: This is a broad, generic limitation regarding multi-modal integration rather than a specific, technical open problem in time-series modeling.

## Datasets

- [[siicu]]

## Links

- [Abstract](https://arxiv.org/abs/2604.01727)
- [PDF](https://arxiv.org/pdf/2604.01727)

