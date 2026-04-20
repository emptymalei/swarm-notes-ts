---
# CSL-compatible fields
title: "Extrapolation of max-stable random fields with Fréchet marginals"
author:
  - literal: "Vitalii Makogin"
  - literal: "Evgeny Spodarev"
  - literal: "Ilja Sukhanov"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.16206"

# Custom fields
paper_id: "2604.16206"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "extreme-value-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "extrapolation-via-level-sets"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:08:41Z"
created_at: "2026-04-20T05:08:41Z"
---

# Extrapolation of max-stable random fields with Fréchet marginals

**Authors**: Vitalii Makogin, Evgeny Spodarev, Ilja Sukhanov
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.16206](https://arxiv.org/abs/2604.16206)

## Summary

This paper introduces a novel extrapolation method for predicting stationary max-stable random fields with α-Fréchet marginal distributions. By leveraging a level-set approach, the method effectively manages heavy-tailed data (α ∈ (0, 2)) without requiring standard moment assumptions. The authors prove the existence of the predictor, characterize the relationship between the excursion metric and Davis-Resnick distance, and demonstrate the method's performance on synthetic series and historical precipitation data.

## Key Contributions

- Develops a prediction method for stationary max-stable random fields with α-Fréchet marginals that bypasses traditional moment assumptions.
- Establishes a rigorous link between the excursion metric and the Davis-Resnick distance to validate the proposed extrapolation approach.
- Demonstrates the framework's practical utility for extreme event forecasting using simulated data and real-world annual maximum precipitation datasets.

## Open Questions & Future Work

- [[non-uniqueness-of-max-stable-forecasts]]

## Key Concepts

- [[extrapolation-via-level-sets]]: A prediction method for stationary max-stable random fields that utilizes excursion sets to perform extrapolation in the presence of heavy tails.

## Archivist Review

I approved the extrapolation via level sets concept as it provides a distinct, non-moment-based approach to heavy-tailed forecasting. I approved the open question regarding the non-uniqueness of these forecasts, as this is a fundamental theoretical challenge for this specific class of models. I rejected the SGD step-size candidate as it is a generic optimization concern unrelated to the specific methodological contributions of the paper.

### Approved Concepts
- Extrapolation via level sets: This is the primary methodological novelty for handling heavy-tailed max-stable fields without moment constraints.

### Approved Open Questions
- Uniqueness of max-stable forecasts: Non-uniqueness of the predictor poses significant challenges for practical applications, as different optimal weight vectors could lead to substantially different forecasts, necessitating further study on regularization or selection criteria.

### Rejected Candidates
- [open_question] Optimal step size for SGD (`sgd-step-size-optimization`) - generic: Generic hyperparameter tuning problem common to most gradient-based optimization methods, not specific to max-stable fields.

## Links

- [Abstract](https://arxiv.org/abs/2604.16206)
- [PDF](https://arxiv.org/pdf/2604.16206)

