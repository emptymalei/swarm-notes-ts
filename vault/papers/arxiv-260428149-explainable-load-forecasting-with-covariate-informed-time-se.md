---
# CSL-compatible fields
title: "Explainable Load Forecasting with Covariate-Informed Time Series Foundation Models"
author:
  - literal: "Matthias Hertel"
  - literal: "Alexandra Nikoltchovska"
  - literal: "Sebastian Pütz"
  - literal: "Ralf Mikut"
  - literal: "Benjamin Schäfer"
  - literal: "Veit Hagenmeyer"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28149"

# Custom fields
paper_id: "2604.28149"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:21:56Z"
created_at: "2026-05-01T05:21:56Z"
---

# Explainable Load Forecasting with Covariate-Informed Time Series Foundation Models

**Authors**: Matthias Hertel, Alexandra Nikoltchovska, Sebastian Pütz, Ralf Mikut, Benjamin Schäfer, Veit Hagenmeyer
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28149](https://arxiv.org/abs/2604.28149)

## Summary

This paper addresses the interpretability challenge of applying Time Series Foundation Models (TSFMs) in critical energy infrastructure by introducing an efficient SHAP-based explanation algorithm. The approach exploits the flexible input-context capabilities of TSFMs to perform targeted temporal and covariate masking, enabling scalable feature attribution. Experiments on day-ahead transmission system operator (TSO) load forecasting show that Chronos-2 and TabPFN-TS perform competitively against specialized models while providing explanations consistent with domain-specific expectations. The findings suggest that TSFMs can reliably integrate into operational forecasting workflows when paired with transparent explanation mechanisms.

## Key Contributions

- Proposes a computationally efficient Shapley Additive Explanations (SHAP) algorithm specifically designed for Time Series Foundation Models (TSFMs).
- Demonstrates that Chronos-2 and TabPFN-TS in a zero-shot setting achieve predictive performance matching domain-specific trained Transformers on TSO load forecasting.
- Validates that TSFM-generated SHAP explanations align with established energy domain knowledge by confirming the model's reliance on relevant weather and calendar covariates.

## Open Questions & Future Work

- [[efficient-shap-estimation-for-tsfms]]
- [[explaining-probabilistic-tsfm-forecasts]]

## Archivist Review

The review focused on identifying core challenges in the explainability of time series foundation models. The two approved open questions capture substantial bottlenecks in computational scalability and the extension of explainability to probabilistic forecasts, which are critical for the deployment of TSFMs in real-world infrastructure. The proposed masking technique was rejected as a concept because it is an implementation detail of the SHAP explanation workflow rather than a standalone theoretical contribution.

### Approved Open Questions
- Efficient SHAP Estimation for TSFMs: This addresses a primary bottleneck in making foundation models transparent for operational energy forecasting where feature sets are often large and diverse.
- Explaining Probabilistic TSFM Forecasts: Transparency in uncertainty is a fundamental requirement for the integration of AI models into grid operations and other risk-sensitive systems.

### Rejected Candidates
- [concept] Temporal and Covariate Masking Explanation Mechanism (`temporal-and-covariate-masking-explanation-mechanism`) - subcomponent_of_broader_mechanism: This is an application-specific heuristic for implementing SHAP rather than a standalone, reusable architectural concept or theoretical mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.28149)
- [PDF](https://arxiv.org/pdf/2604.28149)

