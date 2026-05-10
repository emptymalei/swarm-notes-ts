---
# CSL-compatible fields
title: "SOPF-Based Adaptive Droop Control for Hybrid AC--HVDC Grids Under Offshore Wind Uncertainty"
author:
  - literal: "Hongjin Du"
  - literal: "Aleksandra Lekić"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05992"

# Custom fields
paper_id: "2605.05992"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "physics-informed-meta-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sopf-based-adaptive-droop-control"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-10T05:19:29Z"
created_at: "2026-05-10T05:19:29Z"
---

# SOPF-Based Adaptive Droop Control for Hybrid AC--HVDC Grids Under Offshore Wind Uncertainty

**Authors**: Hongjin Du, Aleksandra Lekić
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05992](https://arxiv.org/abs/2605.05992)

## Summary

This paper addresses the challenge of DC voltage regulation in hybrid AC-HVDC grids under volatile offshore wind conditions. It proposes an adaptive droop control framework that derives optimal gains through a chance-constrained Stochastic Optimal Power Flow (SOPF) model. By using Polynomial Chaos Expansion to represent wind uncertainty and sensitivity analysis for gain extraction, the approach replaces heuristic tuning with mathematically derived, scenario-adaptive control. Validation on a 4-terminal system demonstrates superior performance in maintaining voltage security and minimizing active-power tracking errors during extreme disturbances.

## Key Contributions

- Introduces an SOPF-based adaptive droop framework for DC voltage regulation in hybrid AC-HVDC grids.
- Models offshore wind forecast uncertainty using a zone-wise Beta distribution to capture heteroscedasticity across power regimes.
- Formulates stochastic states analytically using Polynomial Chaos Expansion (PCE) within a chance-constrained optimization.
- Enables Jacobian-free extraction of adaptive droop gains directly from PCE coefficients, embedding statistical voltage-security guarantees.

## Open Questions & Future Work

- [[n-1-contingency-integration-hybrid-grids]]

## Key Concepts

- [[sopf-based-adaptive-droop-control]]: An adaptive control framework that derives droop gains from chance-constrained stochastic optimal power flow using polynomial chaos expansion.

## Archivist Review

The paper proposes a novel bridge between high-level stochastic dispatch (SOPF) and low-level control (droop) using PCE to propagate uncertainty. I approved the adaptive droop framework as it presents a reusable control architecture for stochastic power systems, and the open question regarding N-1 contingency integration as it identifies a major technical bottleneck in current transmission grid security literature. No datasets were approved as the evaluation used standard/generic power system simulation models.

### Approved Concepts
- SOPF-based Adaptive Droop Control: It bridges system-level economic dispatch and converter-level control for robust DC voltage regulation under stochastic uncertainty.

### Approved Open Questions
- Integrating N-1 Contingencies in SOPF: N-1 security is a fundamental requirement for the reliable operation of large-scale transmission grids, and current stochastic dispatch frameworks often struggle to balance probabilistic uncertainty from renewables with deterministic contingency requirements.

## Links

- [Abstract](https://arxiv.org/abs/2605.05992)
- [PDF](https://arxiv.org/pdf/2605.05992)

