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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "quantum-assisted-time-series-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:44:36Z"
created_at: "2026-04-11T04:44:36Z"
---

# QARIMA: A Quantum Approach To Classical Time Series Analysis

**Authors**: Nishikanta Mohanty, Bikash K. Behera, Badshah Mukherjee, Pravat Dash
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08277](https://arxiv.org/abs/2604.08277)

## Summary

QARIMA is a quantum-inspired framework that hybridizes classical ARIMA with variational quantum circuits (VQCs) for robust time-series forecasting. It utilizes swap-test-based quantum autocorrelation (QACF) and partial autocorrelation (QPACF) to identify differencing and lag orders, followed by VQC-based estimation for AR and MA coefficients. By maintaining a fixed-configuration VQC ansatz, the model avoids hyperparameter leakage and achieves superior predictive performance and reduced computational overhead compared to classical ARIMA baselines.

## Key Contributions

- Proposes QARIMA, a quantum-inspired ARIMA framework that replaces classical lag selection and parameter estimation with quantum-assisted counterparts.
- Introduces swap-test-driven QACF and QPACF to derive differencing and AR/MA lag orders through quantum projections.
- Demonstrates significant reduction in meta-optimization overhead while achieving improved out-of-sample MSE and MAPE across industrial datasets compared to classical automated ARIMA.

## Open Questions & Future Work

- [[scalability-robustness-quantum-arima-hybrids]]

## Key Concepts

- [[quantum-assisted-time-series-forecasting]]: A hybrid framework that replaces classical autocorrelation-based lag selection and parameter estimation with swap-test-driven quantum primitives and variational quantum circuits.

## Archivist Review

The paper presents a comprehensive hybrid approach. I approved the overarching concept of quantum-assisted time series forecasting as a reusable methodology, while rejecting the specific submodules (QACF, VQC-AR, etc.) as they are implementations of the primary framework. The open question was renamed slightly to maintain clarity and avoid duplication with existing vault items while retaining the core inquiry into hybrid model scalability.

### Approved Concepts
- Quantum-Assisted Time Series Forecasting: Integrates quantum primitives (QACF, QPACF, VQC) into a classical statistical forecasting workflow, providing a blueprint for future hybrid model development.

### Approved Open Questions
- Scalability and Robustness of Quantum-ARIMA Hybrids: As ARIMA remains a core statistical benchmark, understanding the limits and stability of its quantum-classical hybridizations is crucial for assessing their practical utility in econometrics and real-world forecasting.

### Rejected Candidates
- [concept] differencing selection (`1`) - subcomponent_of_broader_mechanism: Subcomponent of the broader QARIMA framework.
- [concept] QACF (`2`) - subcomponent_of_broader_mechanism: Subcomponent of the broader QARIMA framework.
- [concept] QPACF (`3`) - subcomponent_of_broader_mechanism: Subcomponent of the broader QARIMA framework.
- [concept] swap-test primitives with delayed-matrix construction (`4`) - paper_local: Implementation-specific detail of the framework.
- [concept] VQC-AR (`5`) - subcomponent_of_broader_mechanism: Subcomponent of the broader QARIMA framework.
- [concept] VQC weak-lag refinement (`6`) - subcomponent_of_broader_mechanism: Subcomponent of the broader QARIMA framework.
- [concept] VQC-MA (`7`) - subcomponent_of_broader_mechanism: Subcomponent of the broader QARIMA framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.08277)
- [PDF](https://arxiv.org/pdf/2604.08277)

