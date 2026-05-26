---
# CSL-compatible fields
title: "Electricity Consumption Forecasting: An Approach Using Cooperative Ensemble Learning with SHapley Additive exPlanations"
author:
  - literal: "Eduardo Luiz Alba"
  - literal: "Gilson Adamczuk Oliveira"
  - literal: "Matheus Henrique Dal Molin Ribeiro"
  - literal: "Érick Oliveira Rodrigues"
issued:
  date-parts:
    - [2026, 5, 25]
url: "https://arxiv.org/abs/2605.25305"

# Custom fields
paper_id: "2605.25305"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "weaker-separator-booster-wsb"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-26T05:28:06Z"
created_at: "2026-05-26T05:28:06Z"
---

# Electricity Consumption Forecasting: An Approach Using Cooperative Ensemble Learning with SHapley Additive exPlanations

**Authors**: Eduardo Luiz Alba, Gilson Adamczuk Oliveira, Matheus Henrique Dal Molin Ribeiro, Érick Oliveira Rodrigues
**Date**: 2026-05-25
**Paper ID**: [arxiv:2605.25305](https://arxiv.org/abs/2605.25305)

## Summary

This paper introduces the Weaker Separator Booster (WSB), a cooperative ensemble learning framework designed for electricity consumption forecasting over a 12-month horizon. The approach leverages SHAP values for feature selection and genetic algorithms combined with particle swarm optimization to tune hyperparameter configurations across multiple base learners, including LSTM, RF, SVR, and XGBoost. Evaluation on electricity consumption data from two different campus locations highlights the model's effectiveness, revealing that historical lagged values significantly outperform climatic variables in predictive accuracy.

## Key Contributions

- Proposed the Weaker Separator Booster (WSB) cooperative ensemble learning approach for electricity demand forecasting.
- Demonstrated that SHAP-based feature selection combined with GA and PSO optimization effectively improves forecasting accuracy across different campus datasets.
- Achieved significant performance metrics (sMAPE 13.90% and 18.72%) on two real-world institutional electricity consumption datasets.

## Key Concepts

- [[weaker-separator-booster-wsb]]: A cooperative ensemble learning framework that integrates base forecasting models with SHAP-based feature selection and metaheuristic hyperparameter optimization.

## Archivist Review

The paper proposes a specific ensemble framework (WSB) which is approved as a novel concept due to its cooperative metaheuristic-driven approach. Other candidate concepts, such as SHAP-based feature selection, were rejected for being routine methodology rather than novel research contributions. No new datasets or open questions were approved as they either lacked sufficient distinctness or failed to meet the threshold for permanent archival status.

### Approved Concepts
- Weaker Separator Booster (WSB): WSB is the primary novel ensemble learning approach proposed and evaluated for electricity demand forecasting using cooperative optimization of base learners.

### Rejected Candidates
- [concept] SHAP-based feature selection for forecasting (`shap-based-feature-selection-for-forecasting`) - not_novel: SHAP is an existing standard interpretability technique, and its application as a feature selection heuristic is routine in time-series forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2605.25305)
- [PDF](https://arxiv.org/pdf/2605.25305)

