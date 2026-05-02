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
processed_at: "2026-05-02T05:07:18Z"
created_at: "2026-05-02T05:07:18Z"
---

# Explainable Load Forecasting with Covariate-Informed Time Series Foundation Models

**Authors**: Matthias Hertel, Alexandra Nikoltchovska, Sebastian Pütz, Ralf Mikut, Benjamin Schäfer, Veit Hagenmeyer
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.28149](https://arxiv.org/abs/2604.28149)

## Summary

This paper addresses the interpretability challenge of Time Series Foundation Models (TSFMs) in critical energy infrastructure. By exploiting the inherent flexibility of TSFMs to handle variable input contexts and covariates, the authors introduce a scalable SHAP-based explanation method via temporal and covariate masking. Experiments on day-ahead transmission system operator load forecasting show that Chronos-2 and TabPFN-TS provide competitive zero-shot performance and physically meaningful explanations that align with domain expertise.

## Key Contributions

- Proposes an efficient SHAP-based explanation algorithm for Time Series Foundation Models (TSFMs) by leveraging their context length flexibility.
- Demonstrates that TSFMs (Chronos-2 and TabPFN-TS) achieve zero-shot predictive performance competitive with task-specific Transformer models in load forecasting.
- Validates that TSFMs appropriately utilize weather and calendar covariates, aligning model explanations with established energy domain knowledge.

## Open Questions & Future Work

- [[efficient-shap-tsfm-grouping]]
- [[explaining-probabilistic-forecasts]]

## Archivist Review

I have approved the two open questions as they address critical bottlenecks in scaling model interpretability and reliability for high-stakes operational environments. I rejected the concept proposal for the SHAP-masking method as it is a specific application of existing explainability techniques (SHAP) rather than a novel conceptual framework that warrants a permanent vault entry. No new datasets were approved as the paper utilizes existing public models and established load forecasting tasks.

### Approved Open Questions
- Scalable SHAP for TSFMs: As TSFMs become more complex and the number of input covariates increases, the current exhaustive evaluation approach becomes a bottleneck for real-time or scalable model interpretability in operational environments. Developing sub-sampling or approximation strategies is essential for the practical deployment of these explainability methods.
- Explaining Probabilistic Load Forecasts: Understanding not just the 'why' of a prediction, but also the 'why' behind the uncertainty, is vital for high-stakes infrastructure applications where safety margins and risk management are paramount. Point-forecast explanations alone may lead to overconfidence in model reliability.

## Links

- [Abstract](https://arxiv.org/abs/2604.28149)
- [PDF](https://arxiv.org/pdf/2604.28149)

