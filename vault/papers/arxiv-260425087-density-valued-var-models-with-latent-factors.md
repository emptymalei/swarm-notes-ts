---
# CSL-compatible fields
title: "Density-valued VAR Models with Latent Factors"
author:
  - literal: "Yasumasa Matsuda"
  - literal: "Michel F. C. Haddad"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25087"

# Custom fields
paper_id: "2604.25087"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "density-estimation"
  - "latent-factor-models"
  - "causal-inference"
architectures:
  []
datasets:
  []
concept_slugs:
  - "density-valued-var-models"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:12:04Z"
created_at: "2026-04-29T05:12:04Z"
---

# Density-valued VAR Models with Latent Factors

**Authors**: Yasumasa Matsuda, Michel F. C. Haddad
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25087](https://arxiv.org/abs/2604.25087)

## Summary

This paper introduces a density-valued vector autoregressive (VAR) model with latent factors to analyze the temporal dynamics of multivariate time series of density functions. By mapping B-spline mixture weights of regional viral load distributions into a Euclidean space via a generalized logit transform, the authors enable the application of standard VAR techniques. The approach explicitly separates common regional factors from idiosyncratic dynamics, allowing for the construction of directed predictive networks through formal statistical testing. The model is validated using SARS-CoV-2 data from Brazil, demonstrating its utility in uncovering directed spatiotemporal dependencies.

## Key Contributions

- Introduces a density-valued vector autoregressive (VAR) model that decomposes density-valued time series into common factor movements and directed idiosyncratic dynamics.
- Develops a methodology to map B-spline mixture weights into Euclidean space using a generalized logit transform with an isometric inner product for tractable VAR estimation.
- Provides a statistical framework for identifying directed predictive networks from idiosyncratic VAR components using false discovery rate control, applied to SARS-CoV-2 viral load distributions in Brazil.

## Open Questions & Future Work

- [[negative-density-non-negativity-constraints]]

## Key Concepts

- [[density-valued-var-models]]: A vector autoregressive framework for modeling the temporal dynamics of multivariate density functions using latent factor decomposition.

## Archivist Review

I approved the Density-valued VAR Models concept as it provides a valuable architectural pattern for functional time series. I approved one open question concerning the non-negativity constraint of the proposed logit-based density transformation, as this represents a critical theoretical hurdle. The second open question was rejected as it describes a standard future model extension rather than a structural bottleneck.

### Approved Concepts
- Density-valued VAR Models: This introduces a novel framework for modeling the evolution of entire density functions using factor-augmented VAR models, specifically addressing the challenges of functional time series where observations are distributions.

### Approved Open Questions
- Preserving non-negativity in densities: This is a fundamental theoretical constraint on the proposed transformation-based approach that directly impacts its validity for density estimation.

### Rejected Candidates
- [open_question] Flexible density component dynamics (`component-specific-var-dynamics`) - low_impact: This is a incremental extension suggestion rather than a fundamental bottleneck or unresolved issue.

## Links

- [Abstract](https://arxiv.org/abs/2604.25087)
- [PDF](https://arxiv.org/pdf/2604.25087)

