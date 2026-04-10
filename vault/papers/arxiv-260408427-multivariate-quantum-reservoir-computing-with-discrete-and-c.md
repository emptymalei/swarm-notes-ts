---
# CSL-compatible fields
title: "Multivariate quantum reservoir computing with discrete and continuous variable systems"
author:
  - literal: "Tobias Fellner"
  - literal: "Jonas Merklinger"
  - literal: "Christian Holm"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08427"

# Custom fields
paper_id: "2604.08427"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "quantum-reservoir-computing"
  - "multivariate-forecasting"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mixing-capacity"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:26:41Z"
created_at: "2026-04-10T15:26:41Z"
---

# Multivariate quantum reservoir computing with discrete and continuous variable systems

**Authors**: Tobias Fellner, Jonas Merklinger, Christian Holm
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08427](https://arxiv.org/abs/2604.08427)

## Summary

This paper advances quantum reservoir computing by establishing a systematic framework for processing multivariate temporal data. The authors propose three distinct encoding schemes for multidimensional inputs and introduce 'mixing capacity' as a novel metric to evaluate inter-stream data integration within the reservoir. Through experiments on the chaotic Lorenz-63 system, they demonstrate that performance is sensitive to the alignment between encoding methods and the physical nature of the reservoir (discrete vs. continuous-variable), with peak performance correlating with non-classical quantum effects.

## Key Contributions

- Establishes a generalized framework for extending quantum reservoir computing to multivariate time series processing.
- Introduces 'mixing capacity' as a new metric to quantify how effectively reservoirs fuse multi-dimensional data inputs.
- Demonstrates that optimal encoding strategies for multivariate data depend on whether the reservoir is discrete-variable or continuous-variable based.

## Open Questions & Future Work

- [[theoretical-link-quantum-resources-computational-capacity]]

## Key Concepts

- [[mixing-capacity]]: A metric for evaluating the effectiveness of a reservoir in combining independent temporal data streams.

## Archivist Review

The paper introduces a domain-specific metric for multivariate reservoir integration and identifies a core theoretical gap regarding the role of quantum resources in reservoir computing. I have approved the 'Mixing Capacity' metric and the question regarding the link between quantum resources and capacity, as both are central to the field's advancement. A broader candidate on multivariate quantum data processing was rejected for being too expansive and generic.

### Approved Concepts
- Mixing Capacity: It provides a quantitative way to measure how well a reservoir integrates multidimensional input features, which is critical for assessing multivariate architectures.

### Approved Open Questions
- Linking quantum resources to capacity: Establishing this theoretical foundation is critical to moving beyond empirical correlations and enabling the systematic design of quantum reservoirs that can provably leverage quantum advantage for machine learning tasks.

### Rejected Candidates
- [open_question] Multivariate quantum data processing (`multivariate-quantum-data-processing`) - generic: This is too broad and describes a general research field rather than a specific, trackable, and bounded open research question.

## Links

- [Abstract](https://arxiv.org/abs/2604.08427)
- [PDF](https://arxiv.org/pdf/2604.08427)

