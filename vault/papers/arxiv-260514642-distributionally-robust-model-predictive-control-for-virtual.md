---
# CSL-compatible fields
title: "Distributionally Robust Model Predictive Control for Virtual Power Plants"
author:
  - literal: "Nikolas Recke"
  - literal: "Mathias Hudoba de Badyn"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14642"

# Custom fields
paper_id: "2605.14642"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "uncertainty-quantification"
  - "robust-optimization"
  - "model-predictive-control"
architectures:
  []
datasets:
  []
concept_slugs:
  - "wasserstein-ambiguity-sets"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:12:07Z"
created_at: "2026-05-16T05:12:07Z"
---

# Distributionally Robust Model Predictive Control for Virtual Power Plants

**Authors**: Nikolas Recke, Mathias Hudoba de Badyn
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14642](https://arxiv.org/abs/2605.14642)

## Summary

This paper introduces a distributionally robust model predictive control (DRMPC) framework to optimize Virtual Power Plant (VPP) operations amidst electricity price uncertainty. By utilizing quantile-based uncertainty quantification, the method constructs time-varying Wasserstein ambiguity sets that adapt to changing forecast conditions and distributional shifts. Evaluated on real-world Nordic market and weather data, the framework demonstrates improved economic performance over standard MPC, emphasizing the trade-off between robustness and performance in operational scheduling.

## Key Contributions

- Proposes a distributionally robust model predictive control (DRMPC) framework for Virtual Power Plant (VPP) operation under price uncertainty.
- Introduces a method to construct time-varying Wasserstein ambiguity sets from quantile-based uncertainty quantification, enabling adaptation to forecast dispersion and distributional shifts.
- Demonstrates through a Nordic case study that the DR-MPC approach yields consistent revenue improvements of up to 0.8% compared to standard MPC while highlighting the impact of radius selection on conservatism.

## Open Questions & Future Work

- [[temporal-dependency-dro-bottleneck]]

## Key Concepts

- [[wasserstein-ambiguity-sets]]: A time-varying uncertainty set construction method for robust optimization that adapts to forecast dispersion and distributional shifts.

## Archivist Review

The paper's contribution of adapting Wasserstein ambiguity sets for MPC via quantile forecasts is a distinct and reusable mechanism. The open question regarding the stage-wise independence of these sets correctly identifies a significant limitation in current DRO implementations for multi-horizon control. No other candidates met the strict criteria for retention.

### Approved Concepts
- Wasserstein Ambiguity Sets: The method provides a tractable way to incorporate predictive uncertainty into real-time decision-making by adapting the ambiguity set radius to current forecast conditions.

### Approved Open Questions
- Temporal Dependencies in DRO Ambiguity Sets: This is a critical bottleneck in applying distributionally robust control to energy systems, as it directly impacts the trade-off between robustness (constraint satisfaction) and performance (economic efficiency). Addressing this is crucial for the deployment of truly uncertainty-aware control strategies in VPPs.

## Links

- [Abstract](https://arxiv.org/abs/2605.14642)
- [PDF](https://arxiv.org/pdf/2605.14642)

