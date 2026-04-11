---
# CSL-compatible fields
title: "Pruning Extensions and Efficiency Trade-Offs for Sustainable Time Series Classification"
author:
  - literal: "Raphael Fischer"
  - literal: "Angus Dempster"
  - literal: "Sebastian Buschjäger"
  - literal: "Matthias Jakobs"
  - literal: "Urav Maniar"
  - literal: "Geoffrey I. Webb"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.07953"

# Custom fields
paper_id: "2604.07953"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "monster-archive"
concept_slugs:
  []
dataset_slugs:
  - "monster-archive"
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:45:03Z"
created_at: "2026-04-11T04:45:03Z"
---

# Pruning Extensions and Efficiency Trade-Offs for Sustainable Time Series Classification

**Authors**: Raphael Fischer, Angus Dempster, Sebastian Buschjäger, Matthias Jakobs, Urav Maniar, Geoffrey I. Webb
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.07953](https://arxiv.org/abs/2604.07953)

## Summary

This paper provides a systematic analysis of energy efficiency in time series classification, addressing the lack of unified performance benchmarks. The authors introduce a holistic framework to evaluate the trade-off between predictive quality and resource usage, testing 13 methods across diverse hardware setups. As a core contribution, they propose Hydrant, a novel hybrid architecture that supports theoretically bounded pruning to optimize performance, achieving significant energy savings with minimal impact on accuracy.

## Key Contributions

- Introduces a holistic evaluation framework for assessing the trade-offs between predictive accuracy and energy consumption in time series classification.
- Presents Hydrant, a novel, prunable hybrid time series classifier that integrates Hydra and Quant components.
- Demonstrates that theoretically bounded pruning can reduce energy consumption by up to 80% with less than 5% loss in predictive accuracy across 20 MONSTER datasets.

## Open Questions & Future Work

- [[hybrid-tsc-integration-refinement]]

## Archivist Review

The proposed concept 'Hydrant' was rejected as it represents a specific model architecture rather than a broadly applicable methodological advancement. The dataset 'MONSTER' was mapped to the existing 'monster-archive' entry. The open question regarding hybrid integration strategies was approved as it identifies a substantive limitation in current hybrid time series classification research.

### Approved Open Questions
- Refining Hybrid TSC Integration Strategies: The current lack of optimal integration methods for hybrid time series classifiers prevents the full realization of the performance benefits offered by merging complementary feature extraction paradigms.

### Rejected Candidates
- [concept] Hydrant (`hydrant`) - paper_local: Hydrant is a specific model implementation rather than a general, reusable methodological paradigm.

## Datasets

- [[monster-archive]]

## Links

- [Abstract](https://arxiv.org/abs/2604.07953)
- [PDF](https://arxiv.org/pdf/2604.07953)

