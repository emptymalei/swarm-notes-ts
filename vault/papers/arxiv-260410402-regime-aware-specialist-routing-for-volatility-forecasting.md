---
# CSL-compatible fields
title: "Regime-Aware Specialist Routing for Volatility Forecasting"
author:
  - literal: "Tenghan Zhong"
issued:
  date-parts:
    - [2026, 4, 12]
url: "https://arxiv.org/abs/2604.10402"

# Custom fields
paper_id: "2604.10402"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "regime-aware-specialist-routing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:06:04Z"
created_at: "2026-04-14T05:06:04Z"
---

# Regime-Aware Specialist Routing for Volatility Forecasting

**Authors**: Tenghan Zhong
**Date**: 2026-04-12
**Paper ID**: [arxiv:2604.10402](https://arxiv.org/abs/2604.10402)

## Summary

This paper presents a regime-aware specialist routing framework designed to improve volatility forecasting in ETF markets by dynamically adapting to shifting market conditions. By employing online risk-sensitive evaluation and state-dependent gating, the approach effectively switches between forecasting specialists suited for either calm or stressed market states. Evaluations on a daily panel of six ETFs using a rolling walk-forward design demonstrate that this architecture significantly outperforms static global models, particularly in mitigating high-volatility forecast losses.

## Key Contributions

- Introduces a regime-aware specialist routing framework that dynamically selects forecasting models based on market volatility states.
- Demonstrates that the optimal volatility forecaster is regime-dependent rather than global across different market conditions.
- Achieves a 24% reduction in high-volatility forecast loss and a 22% reduction in underprediction loss compared to the rolling-best baseline using a daily ETF panel.

## Open Questions & Future Work

- [[data-driven-regime-representation]]

## Key Concepts

- [[regime-aware-specialist-routing]]: A forecasting architecture that dynamically routes inputs to specialist models based on identified regime-specific market conditions.

## Archivist Review

The paper contributes a clear, reusable architectural pattern for dynamic model selection (Regime-Aware Specialist Routing) which generalizes well beyond volatility forecasting. The open question regarding data-driven regime representation is a substantial, non-boilerplate bottleneck for adaptive forecasting systems. No other candidates were proposed.

### Approved Concepts
- Regime-Aware Specialist Routing: Provides a reusable architecture for dynamic model selection in time-series forecasting, moving beyond static global model paradigms.

### Approved Open Questions
- Data-Driven Regime Representation Learning: Manual regime definition is prone to misspecification and limits adaptability in complex, high-dimensional forecasting tasks.

## Links

- [Abstract](https://arxiv.org/abs/2604.10402)
- [PDF](https://arxiv.org/pdf/2604.10402)

