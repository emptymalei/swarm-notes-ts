---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Forecast lead time and the timing of crew deployment for weather-driven power outages using AI weather models"
description: "This paper investigates the efficacy of using AI-based weather models, specifically GraphCast and FourCastNet, to predict weather-driven power outages and optimize utility crew deployment across the United States. Through an analysis of lead times from 1 to 5 days, the authors demonstrate that while forecast accuracy (captured burden) degrades significantly after 72 hours, the benefit of securing more crews early often outweighs the cost of forecast errors. The study also identifies critical methodological pitfalls in using land surface predictors and highlights a severe miscalibration of uncertainty intervals during extreme events like tropical cyclones, suggesting a need for improved real-time calibration techniques."
resource: "https://arxiv.org/abs/2610.20918"
tags:
  - "weather-forecasting"
  - "energy-systems"
  - "time-series-forecasting"
  - "uncertainty-quantification"
  - "decision-making"
  - "risk-management"
  - "spatiotemporal-forecasting"
timestamp: "2026-10-18T00:28:33Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Mohammad Kian Golkar"
  - literal: "Luciano Alves de Oliveira"
  - literal: "Mohamad Alipour"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20918"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "captured-burden"
    description: "A spatiotemporal evaluation metric measuring the proportion of total event impact occurring in locations where resources were pre-allocated based on model predictions."
datasets:
  []
open_questions:
  - name: "static-dynamic-feature-imbalance-in-spatiotemporal-models"
    description: "How can spatiotemporal models be architected to prevent static geographic predictors from overshadowing dynamic inputs, ensuring that resource staging decisions are responsive to the specific characteristics of an incoming event rather than just long-term regional vulnerabilities?"
  - name: "proactive-calibration-for-latent-event-classes"
    description: "How can models perform proactive uncertainty calibration when the optimal calibration parameters depend on a latent hazard class that is uncertain at the time of prediction?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:28:33Z"
created_at: "2026-10-18T00:28:33Z"
---

# Forecast lead time and the timing of crew deployment for weather-driven power outages using AI weather models

**Authors**: Mohammad Kian Golkar, Luciano Alves de Oliveira, Mohamad Alipour
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20918](https://arxiv.org/abs/2610.20918)

## Summary

This paper investigates the efficacy of using AI-based weather models, specifically GraphCast and FourCastNet, to predict weather-driven power outages and optimize utility crew deployment across the United States. Through an analysis of lead times from 1 to 5 days, the authors demonstrate that while forecast accuracy (captured burden) degrades significantly after 72 hours, the benefit of securing more crews early often outweighs the cost of forecast errors. The study also identifies critical methodological pitfalls in using land surface predictors and highlights a severe miscalibration of uncertainty intervals during extreme events like tropical cyclones, suggesting a need for improved real-time calibration techniques.

## Key Contributions

- Evaluated the operational utility of AI weather models (GraphCast and FourCastNet) for power outage prediction at lead times of 24 to 120 hours.
- Quantified the trade-off between forecast accuracy and crew availability, demonstrating that early deployment with higher crew numbers often offsets the lower accuracy of long-lead forecasts.
- Identified significant data leakage in standard computations of antecedent land surface predictors, showing that correct computation reduces their apparent advantage at long lead times.
- Discovered a major calibration gap in prediction intervals for extreme events (covering only 47.6% of tropical cyclones vs. 90% nominal) and evaluated post-hoc calibration strategies.

## Limitations

Calibration by hazard class is currently retrospective as the hazard type is often confirmed only after the event occurs. Static components in land surface predictors limit their effectiveness in shifting spatial staging decisions.

## Open Questions & Future Work

- [[static-dynamic-feature-imbalance-in-spatiotemporal-models]]
- [[proactive-calibration-for-latent-event-classes]]

## Key Concepts

- [[captured-burden]]: A spatiotemporal evaluation metric measuring the proportion of total event impact occurring in locations where resources were pre-allocated based on model predictions.

## Archivist Review

I approved 'Captured Burden' as a reusable concept for evaluating resource-allocation models. I also approved two open questions that address the fundamental ML challenges identified in the paper: the dominance of static features in spatiotemporal models and the difficulty of proactive calibration for latent event classes. The dataset was rejected as it is a specific data compilation for this study rather than a general-purpose benchmark.

### Approved Concepts
- Captured Burden: Standard accuracy metrics often fail to reflect the operational value of spatial predictions in resource allocation; captured burden directly links model performance to the effectiveness of staging decisions.

### Approved Open Questions
- Static-Dynamic Feature Imbalance in Spatiotemporal Models: Resolving this imbalance is critical for infrastructure resilience models, where the goal is to predict the unique spatial footprint of a specific storm rather than merely identifying high-risk counties in general.
- Proactive Calibration for Latent Event Classes: Reliable prediction intervals are most critical during extreme, rare events where standard calibration typically fails; current methods often require post-hoc knowledge to reach nominal coverage.

### Rejected Candidates
- [dataset] US-County-Power-Outages (`us-county-power-outages`) - paper_local: This is a domain-specific data compilation from existing utility records rather than a named, reusable benchmark dataset for the broader ML community.
- [concept] Hazard-Class Calibration (`hazard-class-calibration`) - subcomponent_of_broader_mechanism: This is treated more as a diagnostic observation in the paper than a novel, reusable ML method; the underlying challenge is captured in the approved open questions.

## Links

- [Abstract](https://arxiv.org/abs/2610.20918)
- [PDF](https://arxiv.org/pdf/2610.20918)

