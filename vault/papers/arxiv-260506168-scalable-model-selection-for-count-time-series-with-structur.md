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
  - "forecasting"
  - "time-series"
  - "count-data"
  - "model-selection"
  - "structural-breaks"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:19:16Z"
created_at: "2026-05-10T05:19:16Z"
---

# Scalable model selection for count time series with structural breaks: application to solid-organ transplantation during and after COVID-19 in the USA and Italy

**Authors**: Tobia Filosi, Emiliano Ceccarelli, Emilio Porcu, Elena Del Sordo, Libia Lara-Carrion, Giuseppe Iuppa, Francesca Puoti, Silvia Trapani, Silvia Testa, Giovanna Jona Lasinio
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06168](https://arxiv.org/abs/2605.06168)

## Summary

This paper introduces a scalable framework for modelling and forecasting healthcare count time series, focusing on the impact of major external shocks like the COVID-19 pandemic on solid-organ transplant activity. The methodology involves an automated model selection process that evaluates Poisson and negative-binomial specifications, accounting for structural breaks, calendar effects, and short-term temporal dependencies. Through extensive empirical validation on data from the USA and Italy, the study finds that autoregressive components significantly outperform models augmented with external COVID-burden covariates. Results indicate that these donation processes are largely self-contained phenomena, facilitating more focused post-pandemic resource management.

## Key Contributions

- Proposes a scalable model selection framework for count time series featuring structural breaks, specifically tailored for healthcare data subject to system-wide disruptions.
- Systematically evaluates Poisson and negative-binomial models across multiple healthcare strata, demonstrating robust performance using expanding-window validation on horizons of 4, 8, and 12 weeks.
- Provides empirical evidence that for solid-organ transplant activity, intrinsic temporal dynamics and calendar effects are more predictive than exogenous pandemic-related auxiliary covariates.

## Open Questions & Future Work

- [[causal-inference-healthcare-shocks]]

## Archivist Review

I reviewed the paper's framework for modeling healthcare count data. The proposed model selection framework is fundamentally standard econometric practice for count data and thus does not constitute a novel, reusable research concept worthy of the vault. The open question regarding causal inference in healthcare shocks represents a substantial, tracking-worthy challenge in forecasting methodology and was approved.

### Approved Open Questions
- Causal Inference for Healthcare Shocks: Moving from descriptive intervention models to explicit causal identification is critical for informing policy and clinical practice in post-disaster healthcare recovery.

### Rejected Candidates
- [concept] Scalable model selection framework for count time series (`scalable-model-selection-for-count-time-series`) - not_novel: The proposed model selection framework is a standard implementation detail for statistical forecasting and lacks a unique, reusable methodological identity beyond being a common practice in econometrics.

## Links

- [Abstract](https://arxiv.org/abs/2605.06168)
- [PDF](https://arxiv.org/pdf/2605.06168)

