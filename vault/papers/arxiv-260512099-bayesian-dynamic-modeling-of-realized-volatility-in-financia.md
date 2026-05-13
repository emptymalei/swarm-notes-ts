---
# CSL-compatible fields
title: "Bayesian Dynamic Modeling of Realized Volatility in Financial Asset Price Forecasting"
author:
  - literal: "Patrick Woitschig"
  - literal: "Mike West"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12099"

# Custom fields
paper_id: "2605.12099"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-gaussian-chain-graph-models"
  - "bayesian-tensor-on-tensor-varying-coefficient-model"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dynamic-gamma-process-model-for-volatility"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:23:46Z"
created_at: "2026-05-13T05:23:46Z"
---

# Bayesian Dynamic Modeling of Realized Volatility in Financial Asset Price Forecasting

**Authors**: Patrick Woitschig, Mike West
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12099](https://arxiv.org/abs/2605.12099)

## Summary

This paper introduces a Bayesian dynamic modeling framework that couples dynamic gamma processes for realized volatility with traditional dynamic linear models for asset returns. By integrating high-frequency intraday volatility proxies into the conditional structure, the approach effectively models volatility leverage and feedback effects. The model maintains computational efficiency through conjugate-form analysis, offering a scalable solution for multivariate portfolio management and risk forecasting. Empirical evaluation using S&P sector ETFs demonstrates consistent improvements in predictive accuracy over standard forecasting baselines.

## Key Contributions

- Introduces a novel Bayesian dynamic model integrating dynamic gamma processes for realized volatility with dynamic linear models (DLMs) for asset prices.
- Captures volatility leverage and feedback effects by utilizing high-frequency intraday data proxies within a reduced-form framework.
- Demonstrates superior equity return forecasting performance on S&P sector ETF data compared to standard statistical benchmarks.
- Provides a computationally efficient framework for sequential filtering and forecasting that facilitates scaling to high-dimensional multivariate financial applications.

## Open Questions & Future Work

- [[adaptive-volatility-precision-modeling]]

## Key Concepts

- [[dynamic-gamma-process-model-for-volatility]]: A Bayesian modeling framework that uses dynamic gamma processes to model realized volatility proxies within conditional dynamic linear models.

## Archivist Review

The paper presents a clear, reusable Bayesian framework for coupling realized volatility with price series through conjugate-form dynamic gamma processes. I approved the core modeling concept and a research question concerning the adaptivity of volatility measurement precision, as these are theoretically significant and provide a clear path forward for research in financial time-series modeling. Other candidates were rejected for being routine extensions rather than fundamental bottlenecks.

### Approved Concepts
- Dynamic Gamma Process Model for Volatility: This represents a structurally distinct and reusable approach to integrating high-frequency volatility proxies into latent-variable forecasting frameworks.

### Approved Open Questions
- Adaptive Volatility Precision Modeling: Adaptive volatility precision is critical for maintaining robust state-tracking performance across diverse market regimes, particularly under sudden shifts in microstructure noise.

### Rejected Candidates
- [open_question] Multivariate Realized Volatility Modeling (`multivariate-rv-dlm-scaling`) - low_impact: The proposal focuses on scaling a specific model type to higher dimensions, which is a routine extension rather than a fundamental open research problem.

## Links

- [Abstract](https://arxiv.org/abs/2605.12099)
- [PDF](https://arxiv.org/pdf/2605.12099)

