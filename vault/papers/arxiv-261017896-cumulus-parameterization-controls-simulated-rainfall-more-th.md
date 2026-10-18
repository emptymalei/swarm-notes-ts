---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Cumulus parameterization controls simulated rainfall more than microphysics, but not at heavy thresholds: a 3 * 2 factorial WRF study over the Western Himalaya"
description: "This study employs a 3x2 factorial experimental design using the Weather Research and Forecasting (WRF) model to disentangle the contributions of cumulus and microphysics parameterizations to rainfall simulation errors in the Western Himalaya. The authors demonstrate that cumulus schemes generally dominate the simulated precipitation signal, but this control weakens at heavy rainfall thresholds where microphysics becomes equally or more influential. These results suggest that improving extreme weather forecasts in complex terrain requires a specific focus on microphysical processes rather than just convective parameterization."
resource: "https://arxiv.org/abs/2610.17896"
tags:
  - "weather-forecasting"
  - "meteorology"
  - "climate-modeling"
  - "sensitivity-analysis"
  - "spatio-temporal-modeling"
  - "physics-informed-machine-learning"
timestamp: "2026-10-18T01:01:21Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Satyam Kumar"
  - literal: "Akshay Sunil"
  - literal: "Devesh Sheoran"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.17896"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-18T01:01:21Z"
created_at: "2026-10-18T01:01:21Z"
---

# Cumulus parameterization controls simulated rainfall more than microphysics, but not at heavy thresholds: a 3 * 2 factorial WRF study over the Western Himalaya

**Authors**: Satyam Kumar, Akshay Sunil, Devesh Sheoran
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.17896](https://arxiv.org/abs/2610.17896)

## Summary

This study employs a 3x2 factorial experimental design using the Weather Research and Forecasting (WRF) model to disentangle the contributions of cumulus and microphysics parameterizations to rainfall simulation errors in the Western Himalaya. The authors demonstrate that cumulus schemes generally dominate the simulated precipitation signal, but this control weakens at heavy rainfall thresholds where microphysics becomes equally or more influential. These results suggest that improving extreme weather forecasts in complex terrain requires a specific focus on microphysical processes rather than just convective parameterization.

## Key Contributions

- Conducted a systematic 3x2 factorial sensitivity analysis of the WRF model to evaluate the impact of cumulus and microphysics parameterizations over the Western Himalaya.
- Quantified that cumulus parameterization schemes exert significantly more control over simulated rainfall totals than microphysics schemes for standard precipitation intensities.
- Discovered a regime shift at heavy rainfall thresholds where the dominant influence of cumulus parameterization diminishes, highlighting the critical role of microphysics for extreme event forecasting.

## Limitations

The study is limited to a specific geographic region (Western Himalaya) and the findings may be sensitive to the horizontal resolution used in the WRF simulations.

## Archivist Review

The paper is a domain-specific sensitivity study in meteorology using traditional numerical weather prediction (WRF). It lacks novel machine learning contributions, and the proposed open questions are specific to meteorological parameterization rather than ML methodology or generalized physics-informed modeling.

### Rejected Candidates
- [open_question] Parameterization Sensitivity at Convection-Permitting Scales (`convection-permitting-microphysics-sensitivity`) - paper_local: This question is specific to numerical weather prediction parameterization schemes and does not address a fundamental bottleneck in machine learning.
- [open_question] Universality of Parameterization Dominance in Orographic Precipitation (`orographic-precipitation-parameterization-universality`) - paper_local: This is a domain-specific question in meteorology/climatology rather than a reusable research direction for ML.

## Links

- [Abstract](https://arxiv.org/abs/2610.17896)
- [PDF](https://arxiv.org/pdf/2610.17896)

