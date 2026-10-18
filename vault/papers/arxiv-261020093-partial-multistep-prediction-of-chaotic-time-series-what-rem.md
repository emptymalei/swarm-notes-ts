---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Partial Multistep Prediction of Chaotic Time Series: What Remains Predictable beyond the Horizon of Predictability?"
description: "This paper proposes 'partial multistep prediction' to address the fragility of long-term forecasting in chaotic systems. By omitting unreliable intermediate predictions rather than propagating their errors, the authors show that a lightweight local predictor can recover meaningful information far beyond the Lyapunov-limited predictability horizon. Experiments on the Lorenz system and other chaotic datasets reveal that while geometric accuracy eventually fails, topological structures (like attractor scroll identification) persist, and an agreement-based ensemble can reliably extend the effective forecasting range."
resource: "https://arxiv.org/abs/2610.20093"
tags:
  - "time-series"
  - "chaotic-systems"
  - "long-term-forecasting"
  - "dynamical-systems"
  - "ensemble-learning"
  - "nonlinear-dynamics"
  - "forecasting-horizon"
timestamp: "2026-10-18T00:36:06Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Vasilii A. Gromov"
  - literal: "Maksim Lomakin"
  - literal: "Aleksei Kudryashov"
  - literal: "Korney K. Tomashchuk"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20093"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "partial-multistep-prediction"
    description: "A forecasting strategy for chaotic systems that omits unreliable intermediate time steps to prevent error propagation, enabling the recovery of information beyond traditional predictability horizons."
  - name: "admissible-masks"
    description: "Temporal omission patterns in partial prediction that allow a model to maintain geometric or topological accuracy beyond the Lyapunov-limited horizon."
datasets:
  []
open_questions:
  - name: "analytical-derivation-of-admissible-masks"
    description: "How can the optimal omission patterns (admissible masks) be determined analytically from the system's Jacobian or Lyapunov spectrum instead of through empirical search?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:36:06Z"
created_at: "2026-10-18T00:36:06Z"
---

# Partial Multistep Prediction of Chaotic Time Series: What Remains Predictable beyond the Horizon of Predictability?

**Authors**: Vasilii A. Gromov, Maksim Lomakin, Aleksei Kudryashov, Korney K. Tomashchuk
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20093](https://arxiv.org/abs/2610.20093)

## Summary

This paper proposes 'partial multistep prediction' to address the fragility of long-term forecasting in chaotic systems. By omitting unreliable intermediate predictions rather than propagating their errors, the authors show that a lightweight local predictor can recover meaningful information far beyond the Lyapunov-limited predictability horizon. Experiments on the Lorenz system and other chaotic datasets reveal that while geometric accuracy eventually fails, topological structures (like attractor scroll identification) persist, and an agreement-based ensemble can reliably extend the effective forecasting range.

## Key Contributions

- Introduces 'partial multistep prediction', a method that skips intermediate time steps to mitigate error propagation in recursive rollouts for chaotic systems.
- Demonstrates that topological information, such as the specific scroll occupied in a Lorenz attractor, remains predictable even after geometric point-accuracy is lost.
- Develops an agreement-based ensemble of local predictors that successfully identifies predictable future states without requiring future observations, extending the $R^2$ horizon across multiple chaotic systems.

## Limitations

The method requires a trade-off where a significant fraction of future time steps are 'rejected' or classified as non-predictable to maintain accuracy at long horizons.

## Open Questions & Future Work

- [[analytical-derivation-of-admissible-masks]]

## Key Concepts

- [[partial-multistep-prediction]]: A forecasting strategy for chaotic systems that omits unreliable intermediate time steps to prevent error propagation, enabling the recovery of information beyond traditional predictability horizons.
- [[admissible-masks]]: Temporal omission patterns in partial prediction that allow a model to maintain geometric or topological accuracy beyond the Lyapunov-limited horizon.

## Archivist Review

The approved concepts (Partial Multistep Prediction and Admissible Masks) capture the paper's primary methodological innovation and its most significant empirical discovery regarding the structure of predictability in chaos. The open question identifies a rigorous mathematical gap between these empirical findings and established dynamical systems theory. Generic concepts and standard mathematical models were rejected to preserve the vault's focus on novel, reusable ML mechanisms.

### Approved Concepts
- Partial Multistep Prediction: It challenges the standard recursive rollout paradigm in chaotic forecasting by explicitly modeling the trade-off between prediction density and long-horizon accuracy.
- Admissible Masks: Identifies specific temporal patterns (masks) that are structurally capable of carrying information through the 'chaos barrier', suggesting that predictability in chaos is non-uniform over time.

### Approved Open Questions
- Analytical Basis for Admissible Masks: Understanding the mathematical properties of these masks would allow for more efficient predictor design without exhaustive ensemble testing and could reveal new insights into the topology of chaotic attractors.

### Rejected Candidates
- [concept] Agreement-based Ensemble (`agreement-based-ensemble`) - not_novel: Ensemble agreement for uncertainty estimation and rejection is a standard technique in machine learning and not sufficiently novel as a standalone concept.
- [concept] Predictability Horizon (`predictability-horizon`) - duplicate_existing: This is a well-established fundamental concept in dynamical systems and chaos theory, not a contribution of this paper.
- [dataset] Lorenz system (`lorenz-system`) - generic: The Lorenz system is a standard mathematical model/differential equation rather than a specific, curated dataset note worth tracking in this context.

## Links

- [Abstract](https://arxiv.org/abs/2610.20093)
- [PDF](https://arxiv.org/pdf/2610.20093)

