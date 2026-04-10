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
  - "time-series-forecasting"
  - "quantum-machine-learning"
  - "arima-variants"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quantum-autocorrelation-function-qacf"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:27:38Z"
created_at: "2026-04-10T15:27:38Z"
---

# QARIMA: A Quantum Approach To Classical Time Series Analysis

**Authors**: Nishikanta Mohanty, Bikash K. Behera, Badshah Mukherjee, Pravat Dash
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08277](https://arxiv.org/abs/2604.08277)

## Summary

This paper introduces QARIMA, a quantum-inspired framework for time series analysis that replaces traditional autocorrelation methods with swap-test-driven quantum primitives (QACF/QPACF) for order identification. The method utilizes fixed-configuration variational quantum circuits (VQCs) for both parameter estimation and a specialized weak-lag refinement stage. By maintaining a fixed circuit ansatz and training budget, the approach mitigates hyperparameter leakage and achieves competitive performance against automated classical ARIMA baselines across environmental and industrial datasets.

## Key Contributions

- Introduces QARIMA, a quantum-inspired ARIMA methodology using swap-test-driven quantum autocorrelation (QACF) and partial autocorrelation (QPACF) for lag identification.
- Implements a fixed-configuration VQC framework for AR/MA coefficient estimation to prevent hyperparameter leakage while reducing meta-optimization overhead.
- Provides a weak-lag refinement mechanism that re-weights or prunes lags without modifying the ARIMA(p,d,q) structure, improving forecast accuracy on environmental and industrial datasets.

## Open Questions & Future Work

- [[vqc-estimation-stability-in-tsf]]

## Key Concepts

- [[quantum-autocorrelation-function-qacf]]: A swap-test-driven method for identifying time-series lags and differencing orders in a quantum-inspired feature selection framework.

## Archivist Review

I approved the Quantum Autocorrelation Function (QACF) as a novel primitive for feature selection in hybrid quantum forecasting and an open question regarding the stability of VQC-based estimation in time series. I rejected the framework name QARIMA itself and its weak-lag refinement subcomponent to adhere to the policy of focusing on reusable mechanisms rather than specific implementations.

### Approved Concepts
- Quantum Autocorrelation Function (QACF): Provides a novel, quantum-inspired primitive for time-series feature engineering that replaces classical counterparts, offering a reusable mechanism for feature selection in hybrid quantum-classical pipelines.

### Approved Open Questions
- VQC Estimation Stability in TSF: Determining the robustness of VQC-based estimation is critical for transitioning quantum-enhanced forecasting tools from controlled simulations to high-dimensional, real-world temporal modeling.

### Rejected Candidates
- [open_question] VQC Estimation Sensitivity Analysis (`vqc-parameter-estimation-stability`) - other: Renamed for better alignment with vault naming conventions (adding -in-tsf suffix and tightening the title).
- [concept] QARIMA (`qarima`) - paper_local: QARIMA is a specific methodology name rather than a reusable mechanism.
- [concept] VQC weak-lag refinement (`weak-lag-refinement`) - subcomponent_of_broader_mechanism: This is a subcomponent of the overarching QARIMA framework and does not have enough standalone utility or conceptual depth yet to warrant a permanent vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.08277)
- [PDF](https://arxiv.org/pdf/2604.08277)

