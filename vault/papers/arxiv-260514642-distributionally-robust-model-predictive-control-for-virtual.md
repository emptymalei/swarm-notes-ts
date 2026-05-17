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
processed_at: "2026-05-17T05:23:47Z"
created_at: "2026-05-17T05:23:47Z"
---

# Distributionally Robust Model Predictive Control for Virtual Power Plants

**Authors**: Nikolas Recke, Mathias Hudoba de Badyn
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14642](https://arxiv.org/abs/2605.14642)

## Summary

This paper introduces a distributionally robust model predictive control (DRMPC) framework for optimizing Virtual Power Plant (VPP) operations amidst electricity price uncertainty. By integrating data-driven forecasts with time-varying Wasserstein ambiguity sets, the approach adapts to real-time distributional shifts and forecast dispersion. Evaluated on real-world Nordic energy data, the framework achieves superior economic performance compared to standard MPC by effectively balancing risk and conservatism.

## Key Contributions

- Introduces a distributionally robust model predictive control (DRMPC) framework for VPP operation under price uncertainty.
- Develops a method to construct time-varying Wasserstein ambiguity sets that adapt to forecast dispersion and distributional shifts.
- Demonstrates that DR-MPC yields consistent economic performance improvements of up to 0.8% over standard forecast-based MPC in a Nordic case study.

## Open Questions & Future Work

- [[joint-wasserstein-ambiguity-sets-temporal-dependencies]]

## Archivist Review

I evaluated the submission against existing vault entries. The core methodology (DR-MPC with Wasserstein sets) is well-covered by existing concepts, so I focused on the specific theoretical limitation identified regarding joint ambiguity sets. The approved open question addresses a fundamental, reusable research bottleneck in robust control and time-series forecasting.

### Approved Open Questions
- Joint Ambiguity Sets for Temporal Dependencies: Addressing temporal correlation is critical for improving the accuracy and reducing the conservatism of DR-MPC in systems with energy storage, as current independent stage-wise formulations fail to leverage the full structure of the underlying uncertainty.

### Rejected Candidates
- [concept] Distributionally Robust Model Predictive Control for VPPs (`dr-mpc-for-vpp`) - paper_local: This is a specific application instance of DR-MPC rather than a novel conceptual mechanism.
- [concept] Time-Varying Wasserstein Ambiguity Sets (`time-varying-wasserstein-ambiguity-sets`) - duplicate_existing: While a core contribution, it is closely related to existing concepts regarding Wasserstein ambiguity sets and robust estimation, and thus does not require a new standalone entry.

## Links

- [Abstract](https://arxiv.org/abs/2605.14642)
- [PDF](https://arxiv.org/pdf/2605.14642)

