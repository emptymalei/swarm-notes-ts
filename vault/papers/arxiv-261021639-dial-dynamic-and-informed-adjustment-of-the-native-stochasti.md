---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "DIAL: Dynamic and Informed Adjustment of the Native Stochastic Law for Reliable Weather Ensembles"
description: "This paper presents DIAL, a novel framework for improving the reliability of ensemble weather forecasts by dynamically adjusting the native stochasticity of a frozen model during inference. Unlike post-processing or retraining, DIAL learns to predict spread requirements per variable and scale, updating noise at each forecast step to correct for under- or overspread. Evaluated on FourCastNet 3 using ERA5 data, DIAL achieved an 8.27% improvement in multiscale CRPS, outperforming both native models and traditional calibration baselines."
resource: "https://arxiv.org/abs/2610.21639"
tags:
  - "weather-forecasting"
  - "ensemble-methods"
  - "uncertainty-quantification"
  - "reliability"
  - "era5"
  - "crps"
  - "spatiotemporal-forecasting"
  - "stochastic-modeling"
  - "online-learning"
timestamp: "2026-10-18T00:19:49Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Yucheng Wang"
  - literal: "Haonan Guo"
  - literal: "Tianhao Zhao"
  - literal: "Di Wang"
  - literal: "Yu Wu"
  - literal: "Zengmao Wang"
  - literal: "Bo Du"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21639"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "dial-stochastic-control"
    description: "An inference-time framework that dynamically adjusts the stochastic parameters of a frozen ensemble model to maintain reliability across different spatial scales and lead times."
datasets:
  []
open_questions:
  - name: "chaos-vs-model-error-attribution"
    description: "How can inference-time adjustment mechanisms effectively distinguish between natural atmospheric chaos and systematic model-induced spread errors to apply the correct amount of corrective stochasticity?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:19:49Z"
created_at: "2026-10-18T00:19:49Z"
---

# DIAL: Dynamic and Informed Adjustment of the Native Stochastic Law for Reliable Weather Ensembles

**Authors**: Yucheng Wang, Haonan Guo, Tianhao Zhao, Di Wang, Yu Wu, Zengmao Wang, Bo Du
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21639](https://arxiv.org/abs/2610.21639)

## Summary

This paper presents DIAL, a novel framework for improving the reliability of ensemble weather forecasts by dynamically adjusting the native stochasticity of a frozen model during inference. Unlike post-processing or retraining, DIAL learns to predict spread requirements per variable and scale, updating noise at each forecast step to correct for under- or overspread. Evaluated on FourCastNet 3 using ERA5 data, DIAL achieved an 8.27% improvement in multiscale CRPS, outperforming both native models and traditional calibration baselines.

## Key Contributions

- Introduced DIAL, a method for dynamic adjustment of ensemble stochasticity during inference that avoids the need for retraining weather models.
- Developed a multiscale and variable-specific spread prediction loop that estimates how noise changes influence future forecast accuracy and reliability.
- Demonstrated an 8.27% improvement in multiscale CRPS over the native FourCastNet 3 (FCN3) reference on ERA5 benchmark data.
- Showed superior scale-resolved reliability compared to standard learned postprocessing and reward-based control baselines.

## Limitations

The approach requires a feedback loop during inference which may introduce computational overhead, and its performance on extremely long-range (seasonal) horizons is not explicitly detailed.

## Open Questions & Future Work

- [[chaos-vs-model-error-attribution]]

## Key Concepts

- [[dial-stochastic-control]]: An inference-time framework that dynamically adjusts the stochastic parameters of a frozen ensemble model to maintain reliability across different spatial scales and lead times.

## Archivist Review

I approved the DIAL framework as it represents a significant shift in how ensemble reliability is managed—moving from post-hoc calibration to active inference-time control. I also approved the open question regarding the attribution of error to chaos versus model bias, as this is a fundamental theoretical challenge in spatiotemporal forecasting. I rejected the ERA5 dataset and the efficiency trade-off question as they are routine and generic to the field, respectively.

### Approved Concepts
- Dynamic and Informed Adjustment of the Native Stochastic Law (DIAL): DIAL introduces a novel paradigm for ensemble reliability by adjusting noise during the inference process rather than relying on static post-processing or expensive retraining.

### Approved Open Questions
- Attributing Spread to Chaos vs. Model Error: Differentiating these two sources of uncertainty is critical for long-range reliability, as misattribution can lead to over-damping or over-exciting the ensemble's variance.

### Rejected Candidates
- [dataset] ERA5 (`era5`) - not_novel: ERA5 is a routine, foundational reanalysis dataset in the meteorological domain and does not require a standalone note in this context unless a specific novel version was introduced.
- [open_question] Computational Efficiency of Dynamic Stochasticity Control (`stochastic-control-efficiency-tradeoff`) - generic: This identifies a standard engineering trade-off between frequency of updates and compute cost, which is a generic implementation concern rather than a fundamental research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.21639)
- [PDF](https://arxiv.org/pdf/2610.21639)

