---
# CSL-compatible fields
title: "ARMA approximation of a Non-separable Spatio-Temporal Model with Fractional Smoothnesses in Space and Time"
author:
  - literal: "S. Knutsen Furset"
  - literal: "Geir-Arne Fuglstad"
  - literal: "Espen R. Jakobsen"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26535"

# Custom fields
paper_id: "2604.26535"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "varma-approximation-for-spatio-temporal-models"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:13:46Z"
created_at: "2026-04-30T05:13:46Z"
---

# ARMA approximation of a Non-separable Spatio-Temporal Model with Fractional Smoothnesses in Space and Time

**Authors**: S. Knutsen Furset, Geir-Arne Fuglstad, Espen R. Jakobsen
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26535](https://arxiv.org/abs/2604.26535)

## Summary

The paper introduces a novel discretization method for non-separable spatio-temporal covariance models based on diffusion-based extensions of the spatial Matérn model. By employing rational approximations in time, the authors transform the underlying fractional stochastic partial differential equation into a vector autoregressive moving average (VARMA) process. This approach facilitates flexible modeling of fractional smoothnesses in both dimensions while maintaining computational feasibility, as evidenced by pointwise convergence analysis and empirical validation on temperature datasets.

## Key Contributions

- Proposes a novel discretization method for non-separable spatio-temporal covariance models that permits arbitrary fractional smoothnesses in space and time.
- Demonstrates that the proposed rational approximation leads to a VARMA process, with proven pointwise convergence of the covariance function.
- Validates the method through a simulation study and an application to daily mean temperature data, highlighting the importance of temporal smoothness for forecasting accuracy.

## Open Questions & Future Work

- [[spatio-temporal-resolution-instability-for-spde-approximation]]

## Key Concepts

- [[varma-approximation-for-spatio-temporal-models]]: A discretization method using rational approximations to transform space-time fractional SPDE models into VARMA processes.

## Archivist Review

The proposed concept provides a formal mechanism for discretizing fractional spatio-temporal SPDEs, which is a valuable and reusable contribution to the literature on non-separable covariance models. The open question regarding resolution instability is approved as it captures a specific technical bottleneck affecting the reliability of this discretization method, rather than a generic scaling issue.

### Approved Concepts
- VARMA Approximation for Spatio-Temporal Models: Enables efficient computational handling of non-separable covariance models with arbitrary fractional smoothnesses in space and time by mapping fractional SPDEs to tractable VARMA processes.

### Approved Open Questions
- SPDE Approximation Resolution Instability: This is a critical bottleneck for scaling fractional SPDE-based inference to high-resolution climate or environmental datasets.

## Links

- [Abstract](https://arxiv.org/abs/2604.26535)
- [PDF](https://arxiv.org/pdf/2604.26535)

