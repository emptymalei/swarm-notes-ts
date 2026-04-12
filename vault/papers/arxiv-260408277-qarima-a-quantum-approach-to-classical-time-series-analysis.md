---
# CSL-compatible fields
title: "QARIMA: A Quantum Approach To Classical Time Series Analysis"
author:
  - literal: "Nishikanta Mohanty"
  - literal: "Bikash K. Behera"
  - literal: "Badshah Mukherjee"
  - literal: "Pravat Dash"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08277"

# Custom fields
paper_id: "2604.08277"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "quantum-computing"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quantum-assisted-time-series-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-12T05:03:21Z"
created_at: "2026-04-12T05:03:21Z"
---

# QARIMA: A Quantum Approach To Classical Time Series Analysis

**Authors**: Nishikanta Mohanty, Bikash K. Behera, Badshah Mukherjee, Pravat Dash
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08277](https://arxiv.org/abs/2604.08277)

## Summary

QARIMA introduces a quantum-assisted methodology for classical time series analysis by replacing traditional order discovery and parameter estimation with variational quantum circuits (VQCs). The framework employs swap-test-driven quantum autocorrelation and partial autocorrelation functions to determine model orders, followed by fixed-configuration VQCs to estimate autoregressive and moving-average coefficients. A lightweight weak-lag refinement step further prunes redundant temporal dependencies. Experimental results across environmental and industrial datasets show that this approach reduces meta-optimization overhead and offers a rigorous, explainable integration of quantum primitives into classical statistical forecasting.

## Key Contributions

- Introduces QARIMA, a hybrid framework that utilizes quantum autocorrelation (QACF) and partial autocorrelation (QPACF) via swap-tests for automated order discovery (p, d, q).
- Implements VQC-based estimation for autoregressive (VQC-AR) and moving-average (VQC-MA) components, combined with a weak-lag refinement step that prunes redundant features.
- Demonstrates that fixed-configuration VQCs reduce meta-optimization overhead while achieving competitive out-of-sample MSE and MAPE across diverse industrial and environmental benchmarks.

## Open Questions & Future Work

- [[scalability-robustness-quantum-arima-hybrids]]

## Key Concepts

- [[quantum-assisted-time-series-forecasting]]: A hybrid quantum-classical framework that utilizes VQCs for order discovery, lag refinement, and parameter estimation within the ARIMA modeling pipeline.

## Archivist Review

I approved the overarching hybrid framework concept and the open question regarding its scalability, as these reflect the core theoretical and practical contributions. I rejected individual components like 'swap-test-driven autocorrelation' as they are sub-components of the broader quantum-assisted forecasting mechanism already being vaulted. The open question was renamed to be more general and consistent with existing vault nomenclature.

### Approved Concepts
- Quantum-assisted Time Series Forecasting: This paper formalizes a hybrid quantum-classical approach to the classical ARIMA framework, providing a structured methodology for replacing key statistical components with quantum primitives.

### Approved Open Questions
- Scalability of Quantum ARIMA: This addresses the core transition from theoretical quantum-inspired methodology to practical, large-scale application, which is the primary hurdle for adopting quantum approaches in time series analysis.

## Links

- [Abstract](https://arxiv.org/abs/2604.08277)
- [PDF](https://arxiv.org/pdf/2604.08277)

