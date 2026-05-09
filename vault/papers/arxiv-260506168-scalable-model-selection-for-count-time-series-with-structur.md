---
# CSL-compatible fields
title: "Scalable model selection for count time series with structural breaks: application to solid-organ transplantation during and after COVID-19 in the USA and Italy"
author:
  - literal: "Tobia Filosi"
  - literal: "Emiliano Ceccarelli"
  - literal: "Emilio Porcu"
  - literal: "Elena Del Sordo"
  - literal: "Libia Lara-Carrion"
  - literal: "Giuseppe Iuppa"
  - literal: "Francesca Puoti"
  - literal: "Silvia Trapani"
  - literal: "Silvia Testa"
  - literal: "Giovanna Jona Lasinio"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06168"

# Custom fields
paper_id: "2605.06168"
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
processed_at: "2026-05-09T05:11:09Z"
created_at: "2026-05-09T05:11:09Z"
---

# Scalable model selection for count time series with structural breaks: application to solid-organ transplantation during and after COVID-19 in the USA and Italy

**Authors**: Tobia Filosi, Emiliano Ceccarelli, Emilio Porcu, Elena Del Sordo, Libia Lara-Carrion, Giuseppe Iuppa, Francesca Puoti, Silvia Trapani, Silvia Testa, Giovanna Jona Lasinio
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06168](https://arxiv.org/abs/2605.06168)

## Summary

This paper addresses the challenges of forecasting non-negative count time series affected by structural breaks, specifically focusing on solid-organ transplantation activity during and after the COVID-19 pandemic. The authors propose a portfolio-based model selection strategy using BIC, comparing Poisson and negative-binomial specifications that incorporate autoregressive dynamics, calendar effects, and pandemic-specific indicators. Empirical validation on US and Italian datasets demonstrates that autoregressive structures are sufficient for capturing recovery trajectories, rendering exogenous COVID-related covariates largely redundant for this specific application.

## Key Contributions

- Developed a scalable model selection framework for non-negative count time series subject to system-wide structural breaks and external shocks.
- Evaluated predictive performance using an expanding-window design across 4, 8, and 12-week horizons for SOT activity in the USA and Italy.
- Demonstrated that for SOT donation counts, autoregressive and calendar-effect models outperform specifications incorporating exogenous COVID-burden covariates, simplifying post-pandemic forecasting.

## Open Questions & Future Work

- [[hierarchical-modeling-count-time-series]]

## Archivist Review

The paper addresses a specific, narrow forecasting application. I rejected the concept candidate because the proposed model selection framework is standard and lacks novelty. I approved a rewritten open question that generalizes the hierarchical modeling requirement to the broader domain of count time-series forecasting, making it a valuable research direction for future systemic work.

### Approved Open Questions
- Hierarchical Count Time Series: Hierarchical models are essential for capturing latent sources of variance in medical and operational domains that aggregate models routinely overlook.

### Rejected Candidates
- [open_question] Hierarchical Modeling for Transplants (`hierarchical-modeling-transplant-series`) - other: The question was rewritten to be more general and reusable beyond the specific domain of organ transplants.

## Links

- [Abstract](https://arxiv.org/abs/2605.06168)
- [PDF](https://arxiv.org/pdf/2605.06168)

