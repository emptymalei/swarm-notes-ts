---
# CSL-compatible fields
title: "A Convolution Process for Sea Surface Temperature Hot-Spot Identification in the Mediterranean Sea"
author:
  - literal: "Leonardo Marchesin"
  - literal: "Alessandra Menafoglio"
  - literal: "Piercesare Secchi"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04921"

# Custom fields
paper_id: "2605.04921"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "spatial-temporal-modeling"
  - "uncertainty-quantification"
architectures:
  []
datasets:
  []
concept_slugs:
  - "convolution-based-covariance-framework"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-07T05:14:36Z"
created_at: "2026-05-07T05:14:36Z"
---

# A Convolution Process for Sea Surface Temperature Hot-Spot Identification in the Mediterranean Sea

**Authors**: Leonardo Marchesin, Alessandra Menafoglio, Piercesare Secchi
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04921](https://arxiv.org/abs/2605.04921)

## Summary

This paper proposes a novel convolution-based covariance framework for geostatistical modeling of sea surface temperature (SST) in complex, barrier-constrained marine domains. By representing the domain as a directed linear network, the authors encode ocean current dynamics into a moving-average stochastic process, preventing physically inconsistent correlations across land. A penalized estimator is introduced for stable parameter inference, which is then utilized within a Monte Carlo framework to improve SST projection uncertainty and identify high-risk ecological hot spots. The approach provides a rigorous, physics-aware alternative to standard spatial random field models in coastal oceanography.

## Key Contributions

- Introduced a convolution-based covariance framework that models spatial random fields on domains with physical barriers and ocean flow constraints.
- Developed a penalized estimator to stabilize covariance parameter inference while ensuring consistency with hydrodynamic properties.
- Applied the framework to refine RCP-based SST projections in the Mediterranean Sea for improved hot-spot identification and ecological risk assessment.

## Open Questions & Future Work

- [[covariance-modeling-directed-networks]]

## Key Concepts

- [[convolution-based-covariance-framework]]: A geostatistical covariance structure designed for domains with physical boundaries and flow-driven dependencies.

## Archivist Review

The proposed framework introduces a physically grounded approach to geostatistical modeling on non-Euclidean domains, which is a significant and reusable contribution. The open question regarding covariance modeling on directed networks addresses a fundamental limitation in current spatial statistics, and I have approved the overarching mechanism while rejecting the mapping sub-question, which is essentially an implementation detail for preprocessing.

### Approved Concepts
- Convolution-based Covariance Framework: It provides a geostatistical approach to modeling spatial dependence on non-Euclidean domains while explicitly incorporating physical constraints like barriers and directional flow vectors.

### Approved Open Questions
- Covariance Modeling on Directed Networks: This is a fundamental bottleneck for geostatistical modeling of flow-driven domains like marine and river environments, where Euclidean-based models produce physically invalid correlations.

## Links

- [Abstract](https://arxiv.org/abs/2605.04921)
- [PDF](https://arxiv.org/pdf/2605.04921)

