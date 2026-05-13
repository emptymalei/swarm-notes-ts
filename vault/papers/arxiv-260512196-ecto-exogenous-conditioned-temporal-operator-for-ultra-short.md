---
# CSL-compatible fields
title: "ECTO: Exogenous-Conditioned Temporal Operator for Ultra-Short-Term Wind Power Forecasting"
author:
  - literal: "Cao Yuan"
  - literal: "Junjun Wang"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12196"

# Custom fields
paper_id: "2605.12196"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "physically-grounded-variable-selection-pgvs"
  - "exogenous-conditioned-regime-refinement-ecrr"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:23:38Z"
created_at: "2026-05-13T05:23:38Z"
---

# ECTO: Exogenous-Conditioned Temporal Operator for Ultra-Short-Term Wind Power Forecasting

**Authors**: Cao Yuan, Junjun Wang
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12196](https://arxiv.org/abs/2605.12196)

## Summary

ECTO is a unified forecasting framework designed for ultra-short-term wind power prediction that improves handling of non-stationary meteorological exogenous variables. The architecture decomposes exogenous modeling into a Physically-Grounded Variable Selection (PGVS) module for hierarchical feature selection and an Exogenous-Conditioned Regime Refinement (ECRR) module for dynamic gain-bias calibration. Experimental results on real-world wind farm data demonstrate consistent MSE improvements over state-of-the-art baselines, particularly as prediction horizons increase.

## Key Contributions

- Proposes ECTO, a novel forecasting framework that decomposes meteorological exogenous variable processing into two specialized modules: PGVS and ECRR.
- PGVS achieves condition-adaptive feature selection through group-aware sparse modeling, improving prediction stability across heterogeneous sites.
- ECRR employs a mixture-of-experts paradigm to perform horizon-specific gain-bias corrections, outperforming standard forecasting baselines with gains up to 8.6% at long horizons.

## Open Questions & Future Work

- [[automated-physical-group-discovery]]
- [[adaptive-regime-expert-scaling]]

## Key Concepts

- [[physically-grounded-variable-selection-pgvs]]: A hierarchical, group-aware selection mechanism that uses physical priors and sparsemax activations to isolate informative exogenous variables in forecasting.
- [[exogenous-conditioned-regime-refinement-ecrr]]: A mixture-of-experts module that applies gain-bias calibration and horizon-specific corrections based on exogenous context.

## Archivist Review

The paper presents two well-defined modules, PGVS and ECRR, that represent significant, reusable architectural contributions to exogenous-conditioned forecasting. The open questions regarding automation of variable grouping and adaptive expert scaling represent substantial, common bottlenecks in the current landscape of mixture-of-experts time-series architectures. No datasets were approved as none were presented as novel, unique, or non-routine.

### Approved Concepts
- Physically-Grounded Variable Selection (PGVS): PGVS provides a structured, domain-informed approach to exogenous variable selection, moving beyond standard black-box feature mixing.
- Exogenous-Conditioned Regime Refinement (ECRR): ECRR introduces a modular approach to dynamic calibration within a mixture-of-experts framework, addressing non-stationarity by refining forecasts based on external conditions.

### Approved Open Questions
- Automated physical group discovery: Developing data-driven group discovery would reduce the reliance on expert domain knowledge and improve the portability of forecasting frameworks to new sites where physical relationships are not well-characterized.
- Adaptive regime expert scaling: Adaptive expert counts would allow models to automatically match the complexity of the underlying data distribution, preventing both underfitting and overfitting/instability.

## Links

- [Abstract](https://arxiv.org/abs/2605.12196)
- [PDF](https://arxiv.org/pdf/2605.12196)

