---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Improved Forecasting for Multivariate Time Series using GNAR models with General Inverse Distance Weights"
description: "This paper introduces GNARID, an extension of the Generalised Network Autoregressive (GNAR) model that incorporates tunable inverse distance weights for multivariate time series forecasting. Unlike traditional models that use fixed uniform or reciprocal weights, GNARID introduces an exponent parameter that allows the model to learn the optimal strength of distance-based penalization between nodes. The authors provide rigorous proofs for the consistency and asymptotic normality of the estimators and demonstrate through simulations and real-world ground displacement data that flexible weight tuning significantly reduces forecasting error."
resource: "https://arxiv.org/abs/2610.19921"
tags:
  - "time-series"
  - "multivariate-time-series"
  - "time-series-forecasting"
  - "graph-signals"
  - "statistical-modeling"
  - "statistical-inference"
  - "physics"
timestamp: "2026-10-18T00:38:08Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Hengxu Liu"
  - literal: "Guy P. Nason"
  - literal: "Sourav Das"
  - literal: "Stephen Grebby"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19921"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "gnarid"
    description: "An extension of Generalized Network Autoregressive (GNAR) models that incorporates a tunable exponent parameter to optimize distance-based weighting between network nodes."
datasets:
  []
open_questions:
  - name: "spatially-varying-network-weights"
    description: "Can network autoregressive models like GNARID be extended to support locally adaptive or spatially varying distance-weight exponents to better represent heterogeneous systems where connectivity influences differ by region?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:38:08Z"
created_at: "2026-10-18T00:38:08Z"
---

# Improved Forecasting for Multivariate Time Series using GNAR models with General Inverse Distance Weights

**Authors**: Hengxu Liu, Guy P. Nason, Sourav Das, Stephen Grebby
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19921](https://arxiv.org/abs/2610.19921)

## Summary

This paper introduces GNARID, an extension of the Generalised Network Autoregressive (GNAR) model that incorporates tunable inverse distance weights for multivariate time series forecasting. Unlike traditional models that use fixed uniform or reciprocal weights, GNARID introduces an exponent parameter that allows the model to learn the optimal strength of distance-based penalization between nodes. The authors provide rigorous proofs for the consistency and asymptotic normality of the estimators and demonstrate through simulations and real-world ground displacement data that flexible weight tuning significantly reduces forecasting error.

## Key Contributions

- Proposed the GNARID model which introduces a tunable exponent parameter for inverse distance weights in network autoregressive frameworks.
- Established the theoretical consistency and asymptotic normality of GNARID estimators, extending the analysis to scenarios where the number of network nodes increases.
- Derived analytical results on the forecasting error induced by misspecifying the weight exponent, providing a justification for the parameter's tunability.
- Achieved superior forecasting accuracy on the Brumadinho ground displacement dataset compared to standard GNAR models with fixed weight schemes.

## Limitations

The model assumes a global exponent for the entire network, which might not hold in heterogeneous systems where different sub-networks exhibit different distance-decay behaviors.

## Open Questions & Future Work

- [[spatially-varying-network-weights]]

## Key Concepts

- [[gnarid]]: An extension of Generalized Network Autoregressive (GNAR) models that incorporates a tunable exponent parameter to optimize distance-based weighting between network nodes.

## Archivist Review

The review approved GNARID as a significant methodological refinement of the network autoregressive framework. The open question regarding spatially varying weights was approved because it identifies a fundamental limitation of global spatial models in heterogeneous environments, providing a clear path for future research. Niche datasets and generic scalability concerns were rejected to maintain the vault's focus on broadly reusable ML concepts and non-trivial research bottlenecks.

### Approved Concepts
- GNARID: It moves network autoregressive models beyond fixed-weight assumptions, allowing the decay of influence over spatial or network distances to be learned directly from data.

### Approved Open Questions
- Spatially Varying Network Weights: Real-world networks (e.g., transport, sensor grids) often exhibit non-stationary spatial dependencies that a single global parameter cannot capture accurately.

### Rejected Candidates
- [dataset] Brumadinho ground displacement dataset (`brumadinho-ground-displacement-dataset`) - paper_local: The dataset is highly specific to a single geographical event and monitoring task; it lacks the broad community adoption required for a standalone vault entry.
- [open_question] Large-Scale GNARID Optimization (`large-scale-gnarid-optimization`) - generic: Scalability to large networks is a generic challenge for all multivariate and network-based models and does not identify a unique research bottleneck specific to this architecture.

## Links

- [Abstract](https://arxiv.org/abs/2610.19921)
- [PDF](https://arxiv.org/pdf/2610.19921)

