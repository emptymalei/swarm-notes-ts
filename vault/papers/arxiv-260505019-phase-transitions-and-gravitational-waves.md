---
# CSL-compatible fields
title: "Phase Transitions and Gravitational Waves"
author:
  - literal: "Diego Rios"
  - literal: "William H. Kinney"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.05019"

# Custom fields
paper_id: "2605.05019"
paper_source: "arxiv"
domain: "astrophysics"
tags:
  - "gravitational-waves"
  - "cosmology"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-07T05:13:41Z"
created_at: "2026-05-07T05:13:41Z"
---

# Phase Transitions and Gravitational Waves

**Authors**: Diego Rios, William H. Kinney
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.05019](https://arxiv.org/abs/2605.05019)

## Summary

This paper provides a Fisher-matrix analysis of the detectability of stochastic gravitational wave backgrounds originating from first-order phase transitions in the early universe. By modeling the signal spectrum as a function of transition strength, inverse duration, temperature, and bubble wall velocity, the authors forecast the parameter estimation precision for the DECIGO and LISA space-based detectors. The results highlight the high sensitivity of these detectors and characterize the significant degeneracy between the transition strength and inverse duration parameters.

## Key Contributions

- Fisher-matrix forecast for detecting stochastic gravitational wave backgrounds from first-order phase transitions using LISA and DECIGO.
- Characterized parameter estimation uncertainties and strong correlations between transition strength (α) and inverse duration (β/H*) for phase transition signals.
- Demonstrated DECIGO's precision in estimating phase transition parameters with marginalized uncertainties σ(ln α) ≈ 0.12 and σ(ln β/H*) ≈ 0.145.
- Quantified parameter estimation performance for LISA, showing Δα/α ≈ 4% and Δ(β/H*)/(β/H*) ≈ 11% under fiducial model assumptions.

## Open Questions & Future Work

- [[full-parameter-space-phase-transition-forecasting]]
- [[realistic-detector-response-modeling]]

## Archivist Review

The paper presents standard Fisher-matrix forecasting for cosmological phase transitions. While the analysis is solid, it does not propose a reusable methodology or architectural pattern that warrants a permanent concept note. The proposed open questions regarding parameter space completeness and detector response realism identify significant, non-boilerplate bottlenecks in astrophysical forecasting and are approved for tracking.

### Approved Open Questions
- Full Parameter Space Forecasting: Full parameter estimation is essential to determine whether current constraints, derived from fixed-parameter assumptions, are overly optimistic and to understand how these physical variables interact with the primary transition parameters.
- Realistic Detector Response Modeling: Idealized sensitivity models provide potentially optimistic bounds; realistic instrument modeling is necessary for reliable, mission-specific performance predictions that account for complex hardware responses.

### Rejected Candidates
- [open_question] Full Parameter Space Forecasting (`full-parameter-space-phase-transition-forecasting`) - duplicate_existing: This is a re-submission of the analysis, already approved.
- [open_question] Realistic Detector Response Modeling (`realistic-detector-response-modeling`) - duplicate_existing: This is a re-submission of the analysis, already approved.

## Links

- [Abstract](https://arxiv.org/abs/2605.05019)
- [PDF](https://arxiv.org/pdf/2605.05019)

