---
# CSL-compatible fields
title: "SBBTS: A Unified Schrödinger-Bass Framework for Synthetic Financial Time Series"
author:
  - literal: "Alexandre Alouadi"
  - literal: "Grégoire Loeper"
  - literal: "Célian Marsala"
  - literal: "Othmane Mazhar"
  - literal: "Huyên Pham"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07159"

# Custom fields
paper_id: "2604.07159"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "generative-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "schrodinger-bass-bridge-for-time-series"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:53:35Z"
created_at: "2026-04-09T04:53:35Z"
---

# SBBTS: A Unified Schrödinger-Bass Framework for Synthetic Financial Time Series

**Authors**: Alexandre Alouadi, Grégoire Loeper, Célian Marsala, Othmane Mazhar, Huyên Pham
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07159](https://arxiv.org/abs/2604.07159)

## Summary

The paper introduces the Schrödinger-Bass Bridge for Time Series (SBBTS), a framework designed to generate realistic synthetic financial time series by jointly modeling drift and stochastic volatility. Unlike previous methods that decouple these dynamics or rely solely on martingale transport, SBBTS enables efficient learning through a tractable decomposition into conditional transport problems. Empirical results on the Heston model and real-world S&P 500 data demonstrate superior performance in parameter recovery and downstream utility for data augmentation in financial forecasting.

## Key Contributions

- Introduced SBBTS, a novel generative framework that jointly calibrates drift and stochastic volatility for synthetic time series.
- Demonstrated that SBBTS captures stochastic volatility and correlation parameters on the Heston model where previous Schrödinger Bridge methods fail.
- Showed that SBBTS-generated data consistently improves downstream forecasting performance, classification accuracy, and Sharpe ratio in financial data augmentation tasks.

## Open Questions & Future Work

- [[sbbts-convergence-guarantees]]
- [[optimal-beta-calibration]]

## Key Concepts

- [[schrodinger-bass-bridge-for-time-series]]: A unified generative framework that extends the Schrödinger-Bass formulation to model both drift and stochastic volatility in multi-step financial time series.

## Archivist Review

Approved the core generative framework and two research questions regarding its convergence and hyperparameter sensitivity. The dataset (S&P 500) was rejected as it is a common real-world benchmark that does not require a standalone vault entry. Applied a selective approach to focus on the methodological innovations and theoretical bottlenecks introduced by the Schrödinger-Bass framework.

### Approved Concepts
- Schrödinger-Bass Bridge for Time Series: Provides a novel generative framework for financial time series that overcomes the limitations of existing diffusion and transport-based methods regarding joint drift and volatility modeling.

### Approved Open Questions
- Formal convergence of SBBTS training: Rigorous convergence proofs are necessary to validate the stability and reliability of the training process, especially when applied to complex, high-dimensional financial data where empirical success alone is insufficient for robust deployment.
- Systematic beta calibration for SBBTS: A systematic way to tune this hyperparameter is critical for practitioners to ensure consistent and optimal performance without relying on manual trial-and-error or heuristics across diverse financial contexts.

## Links

- [Abstract](https://arxiv.org/abs/2604.07159)
- [PDF](https://arxiv.org/pdf/2604.07159)

