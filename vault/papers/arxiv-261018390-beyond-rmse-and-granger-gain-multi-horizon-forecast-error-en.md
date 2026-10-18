---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Beyond RMSE and Granger Gain: Multi-Horizon Forecast-Error Entropy for Nonlinear Predictive Coupling"
description: "This paper introduces Forecast-Error Distribution Entropy (FEDE), a novel framework for detecting nonlinear predictive causality in time series. By comparing the entropy of error distributions between target-only and target-plus-source forecasts, FEDE captures information gain that traditional RMSE-based metrics often miss, particularly when interactions are hidden by nonlinear transformations. The author demonstrates that nonlinear models like LightGBM, when integrated with FEDE, significantly outperform linear baselines and Convergent Cross Mapping (CCM) in identifying directional coupling across various noise levels and stochastic conditions."
resource: "https://arxiv.org/abs/2610.18390"
tags:
  - "causality"
  - "time-series-analysis"
  - "nonlinear-dynamics"
  - "entropy-measures"
  - "information-theory"
  - "forecasting-horizon"
  - "robustness"
  - "predictive-modeling"
timestamp: "2026-10-18T00:57:14Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Andrei Velichko"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18390"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "forecast-error-distribution-entropy"
    description: "A framework for quantifying predictive causality by measuring the entropy of the full signed forecast-error distribution rather than aggregate error magnitudes."
datasets:
  []
open_questions:
  - name: "model-form-sensitivity-in-predictive-causality"
    description: "How can predictive causality frameworks robustly detect nonlinear causal influences when the specific functional form of the interaction is unknown, specifically by mitigating the sensitivity of causality metrics to the choice of the underlying predictive model (e.g., linear vs. tree-based)?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:57:14Z"
created_at: "2026-10-18T00:57:14Z"
---

# Beyond RMSE and Granger Gain: Multi-Horizon Forecast-Error Entropy for Nonlinear Predictive Coupling

**Authors**: Andrei Velichko
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18390](https://arxiv.org/abs/2610.18390)

## Summary

This paper introduces Forecast-Error Distribution Entropy (FEDE), a novel framework for detecting nonlinear predictive causality in time series. By comparing the entropy of error distributions between target-only and target-plus-source forecasts, FEDE captures information gain that traditional RMSE-based metrics often miss, particularly when interactions are hidden by nonlinear transformations. The author demonstrates that nonlinear models like LightGBM, when integrated with FEDE, significantly outperform linear baselines and Convergent Cross Mapping (CCM) in identifying directional coupling across various noise levels and stochastic conditions.

## Key Contributions

- Proposed the Forecast-Error Distribution Entropy (FEDE) framework for quantifying predictive causality using the full signed error distribution rather than aggregate error magnitudes.
- Demonstrated that FEDE provides significantly higher response-sensitivity (avg. ~27.0) compared to log-RMSE gain (avg. ~12.5) across varied noise levels and nonlinearities.
- Showed that gradient-boosted models (LightGBM) can recover hidden nonlinear channels that linear models and polynomial approximations fail to detect.
- Established the robustness of FEDE across 108 combinations of history/horizon parameters in stochastic and non-invertible settings where Convergent Cross Mapping (CCM) is inconsistent.

## Limitations

The framework shows a strong dependence on the choice of the underlying predictive model's form, which must be capable of capturing the specific nonlinear interaction to be effective.

## Open Questions & Future Work

- [[model-form-sensitivity-in-predictive-causality]]

## Key Concepts

- [[forecast-error-distribution-entropy]]: A framework for quantifying predictive causality by measuring the entropy of the full signed forecast-error distribution rather than aggregate error magnitudes.

## Archivist Review

I have approved the core methodological contribution (FEDE) as it represents a distinct shift from magnitude-based error metrics to information-theoretic ones in the context of causality. I also approved the open question regarding model sensitivity, as it addresses a fundamental limitation in applying modern ML models to Granger-style causality. No datasets were approved as the paper utilizes synthetic benchmarks rather than established, named datasets.

### Approved Concepts
- Forecast-Error Distribution Entropy: FEDE shifts the focus from simple error magnitude (RMSE) to the full information content of the error distribution, allowing for more sensitive detection of nonlinear interactions that do not necessarily manifest as mean-squared error improvements.

### Approved Open Questions
- Model-Form Sensitivity in Predictive Causality: The dependence of causality detection on model architecture introduces a significant bottleneck for automated discovery in complex systems where the interaction physics are poorly understood.

### Rejected Candidates
- [concept] Predictive Causality Framework (`predictive-causality-framework`) - generic: This is a broad category of statistical methods (e.g., Granger causality) rather than a specific novel mechanism.
- [concept] Nonlinear Predictive Coupling (`nonlinear-predictive-coupling`) - generic: This describes the phenomenon being studied rather than a reusable methodological tool or architecture.

## Links

- [Abstract](https://arxiv.org/abs/2610.18390)
- [PDF](https://arxiv.org/pdf/2610.18390)

