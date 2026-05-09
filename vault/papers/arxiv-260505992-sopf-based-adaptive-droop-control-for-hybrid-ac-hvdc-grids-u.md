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
  - "time-series"
  - "probabilistic-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sopf-based-adaptive-droop-control"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-09T05:11:23Z"
created_at: "2026-05-09T05:11:23Z"
---

# SOPF-Based Adaptive Droop Control for Hybrid AC--HVDC Grids Under Offshore Wind Uncertainty

**Authors**: Hongjin Du, Aleksandra Lekić
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05992](https://arxiv.org/abs/2605.05992)

## Summary

This paper presents a stochastic optimal power flow (SOPF) framework to replace conventional fixed-gain droop control in hybrid AC-HVDC grids with high offshore wind integration. The authors model wind forecast uncertainty using zone-wise Beta distributions and utilize Polynomial Chaos Expansion (PCE) to analytically formulate system stochastic states. By extracting adaptive droop gains directly from PCE coefficients through sensitivity analysis, the framework provides robust DC voltage regulation and minimizes active-power tracking errors under extreme wind fluctuations.

## Key Contributions

- Introduced an SOPF-based adaptive droop framework that optimizes converter response to stochastic wind volatility.
- Modeled wind forecast uncertainty using a zone-wise Beta distribution to account for regime-specific heteroscedasticity.
- Achieved Jacobian-free extraction of adaptive droop gains via first-order Polynomial Chaos Expansion coefficients, ensuring statistical voltage security.

## Open Questions & Future Work

- [[n-1-security-integration-hvdc-grids]]

## Key Concepts

- [[sopf-based-adaptive-droop-control]]: A control framework that derives optimal adaptive droop gains from sensitivity analysis of a chance-constrained stochastic optimal power flow.

## Archivist Review

The approved concept provides a novel bridge between system-level stochastic optimization and converter-level control, which is highly reusable in power grid stability research. The approved open question addresses a specific architectural limitation in handling security contingencies, whereas the rejected HIL request is a standard engineering validation step rather than a fundamental scientific bottleneck.

### Approved Concepts
- SOPF-Based Adaptive Droop Control: The method directly integrates system-level SOPF optimization into local converter droop control to handle stochastic wind uncertainty.

### Approved Open Questions
- N-1 Security Integration HVDC Grids: Reliability and grid security in the face of equipment failure are essential for the practical deployment of multi-terminal HVDC systems.

### Rejected Candidates
- [open_question] Hardware-in-the-loop Control Validation (`hardware-in-the-loop-validation`) - other: Routine experimental validation requests are considered boilerplate and do not represent a substantial unresolved theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.05992)
- [PDF](https://arxiv.org/pdf/2605.05992)

