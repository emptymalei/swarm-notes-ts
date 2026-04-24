---
created_at: '2026-04-24T05:08:47Z'
source_papers:
- '[[arxiv-260421101-a-hybridizable-neural-time-integrator-for-stable-autoregress]]'
title: Stability in Transformer-Based Forecasting
---

**Background:** While Transformer architectures have demonstrated empirical success in forecasting spatiotemporal dynamics, they currently lack the mathematical structure required to provide theoretical stability guarantees for long-horizon rollouts.

**Question / Future Work:** Reconciling the high expressivity of transformer-based architectures with the rigorous stability guarantees provided by structure-preserving numerical methods (such as those derived from FEEC) remains a fundamental challenge. Future work is required to extend these architectures to complex engineering geometries beyond rectilinear domains and to develop field evolution models capable of extrapolation beyond standard autoregressive forecasting.

**Why It Matters:** The lack of mathematical grounding for transformer stability poses a significant barrier to their reliable application in high-stakes scientific simulation, where catastrophic failures during rollout are unacceptable.

**Evidence:** Yet producing stable forecasts over horizons significantly exceeding the training window remains an open challenge [25, 29]: transformers lack mathematical structure for stability analysis, while neural ODEs suffer exploding gradients during long-horizon training.