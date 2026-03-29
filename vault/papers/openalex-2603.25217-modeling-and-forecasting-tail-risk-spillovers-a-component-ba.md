---
# CSL-compatible fields
title: "Modeling and Forecasting Tail Risk Spillovers: A Component-Based CAViaR Approach"
author:
  - literal: "Demetrio Lacava"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25217"

# Custom fields
paper_id: "2603.25217"
paper_source: "openalex"
domain: "time-series"
tags:
  - "quantile regression"
  - "tail risk"
  - "volatility forecasting"
  - "risk management"
  - "time series econometrics"
architectures:
  []
datasets:
  - "Dow Jones Industrial Average stocks"
concept_slugs:
  - "caviar-with-spillover-effects-caviar-se"
  - "recursive-partial-correlation-spillover-selection"
dataset_slugs:
  - "dow-jones-industrial-average-stocks"
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:16:17Z"
created_at: "2026-03-29T20:16:17Z"
---

# Modeling and Forecasting Tail Risk Spillovers: A Component-Based CAViaR Approach

**Authors**: Demetrio Lacava
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25217](https://arxiv.org/abs/2603.25217)

## Summary

This paper proposes CAViaR with Spillover Effects (CAViaR-SE), a novel econometric model extending the conditional Value at Risk (CAViaR) framework for improved tail risk forecasting. The model decomposes the conditional VaR into a self-risk term and a spillover term driven by a linear combination of influential external asset tail risks, selected using a recursive partial correlation algorithm. This spillover component functions as a predictable quantile shifter, directly influencing the quantile dynamics rather than the scale of volatility. Empirical tests on Dow Jones Industrial Average stocks confirm that CAViaR-SE significantly outperforms standard and augmented CAViaR models in out-of-sample forecasting and calibration, indicating the substantial role of systemic spillover effects in tail risk generation.

## Key Contributions

- Introduction of the component-based CAViaR with Spillover Effects (CAViaR-SE) model, which decomposes conditional Value at Risk into a proper-risk component and an exogenous spillover component.
- Development of a recursive partial correlation algorithm to identify influential spillover sources with minimal parameterization.
- Demonstration that spillover effects account for a substantial portion of total tail risk in financial asset returns.
- Empirical validation showing CAViaR-SE significantly improves out-of-sample tail risk forecasts and provides well-calibrated risk measures compared to standard CAViaR models using MCS analysis.

## Limitations

The paper focuses solely on Dow Jones Industrial Average stocks, and generalizability to other asset classes or financial markets is not explicitly tested.

## Open Questions & Future Work

- [[caviar-se-persistence-identifiability]]

## Key Concepts

- [[caviar-with-spillover-effects-caviar-se]]: An extension of the Conditional Autoregressive Value at Risk (CAViaR) model that decomposes the conditional VaR into a proper-risk component and a spillover component from influential assets.
- [[recursive-partial-correlation-spillover-selection]]: An algorithm used to select influential assets whose tail risks drive the spillover component in the CAViaR-SE model using recursive partial correlation.

## Archivist Review

I approved the two central methodological contributions: the novel CAViaR-SE model and the specialized recursive algorithm used for component selection, as both represent reusable econometric techniques. One significant open question regarding the model's parameter identifiability constraints ($\beta_1 > \varphi_1$) was approved due to its technical importance for the model's structure. The single named dataset was approved for completeness, while general concepts and standard evaluation methods were rejected as per policy.

### Approved Concepts
- CAViaR with Spillover Effects (CAViaR-SE): This is the novel, central econometric model proposed in the paper for forecasting tail risk that incorporates explicit spillover components.
- Recursive Partial Correlation Algorithm for Spillover Selection: This is the novel method proposed for identifying and selecting the most influential spillover sources with parsimonious parameterization.

### Approved Open Questions
- CAViaR-SE persistence identifiability: The specified parameter relationship ($\\beta_1 > \\varphi_1$) is necessary for the formal identifiability and economic interpretation of the component-based model, separating persistent proper risk from temporary spillover risk.

### Rejected Candidates
- [concept] Tail Risk Spillovers (`tail risk spillovers`) - subcomponent_of_broader_mechanism: 'Tail Risk Spillovers' is a general concept in finance, and the specific mechanism is captured by the CAViaR-SE concept.
- [concept] Predictable Quantile Shifter (`quantile shifter`) - paper_local: This is a mechanism of action within the CAViaR-SE model, not a standalone, reusable, generalizable concept.
- [concept] Model Confidence Set (MCS) Analysis (`model confidence set analysis`) - not_novel: MCS is a standard statistical evaluation procedure, not a novel contribution of this specific paper.

## Datasets

- [[dow-jones-industrial-average-stocks]]

## Links

- [Abstract](https://arxiv.org/abs/2603.25217)
- [PDF](https://arxiv.org/pdf/2603.25217)

