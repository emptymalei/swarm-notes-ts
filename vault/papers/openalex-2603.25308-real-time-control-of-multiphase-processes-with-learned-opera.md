---
# CSL-compatible fields
title: "Real-time control of multiphase processes with learned operators"
author:
  - literal: "Paolo Guida"
  - literal: "Didier Barradas-Bautista"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25308"

# Custom fields
paper_id: "2603.25308"
paper_source: "openalex"
domain: "control-systems"
tags:
  - "control"
  - "model-order-reduction"
  - "operator learning"
  - "model-predictive-control"
architectures:
  - "Fourier Neural Operator"
datasets:
  []
concept_slugs:
  - "surrogate-assisted-mpc"
  - "fno-phase-field-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:17:55Z"
created_at: "2026-03-29T20:17:55Z"
---

# Real-time control of multiphase processes with learned operators

**Authors**: Paolo Guida, Didier Barradas-Bautista
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25308](https://arxiv.org/abs/2603.25308)

## Summary

This work introduces a surrogate-assisted Model Predictive Control (MPC) framework to enable real-time control of complex multiphase processes currently limited by the computational expense of high-fidelity numerical simulators. The core of the approach is a Fourier Neural Operator (FNO) trained to rapidly forecast the spatiotemporal evolution of a phase-indicator field (volume fraction) over a control horizon based on historical states and candidate actuation. This low-cost neural operator surrogate is then integrated into the MPC optimization loop to iteratively identify the optimal control sequence for regulating the process dynamics. The method is validated by tracking piecewise-constant liquid level setpoints in a two-phase Eulerian bubble column by adjusting the injected gas flow rate, demonstrating suitability for fast unit operations.

## Key Contributions

- Proposed a surrogate-assisted Model Predictive Control (MPC) framework using learned operators to address the computational cost of high-fidelity numerical models in multiphase flow control.
- Trained a Fourier Neural Operator (FNO) to forecast the spatiotemporal evolution of a phase-indicator field (volume fraction) over a finite horizon from recent states and actuation signals.
- Demonstrated the framework on an optimal control problem (OCP) for tracking liquid level setpoints in a two-phase Eulerian bubble column by adjusting gas flow rate.
- Showed that field-level forecasting with FNOs offers a low evaluation cost suitable for closed-loop optimization in fast multiphase unit operations.

## Limitations

The current work is demonstrated on a two-phase Eulerian bubble column, and future work will address partial observability and physics-informed operator learning.

## Key Concepts

- [[surrogate-assisted-mpc]]: A Model Predictive Control (MPC) framework where a learned operator surrogate model replaces the high-fidelity numerical simulation for fast prediction during optimization.
- [[fno-phase-field-forecasting]]: Using a Fourier Neural Operator (FNO) to learn the governing dynamics and forecast the spatiotemporal evolution of a phase-indicator field for control purposes.

## Archivist Review

Two core concepts were approved: the overarching control paradigm of Surrogate-Assisted MPC and the specific modeling technique used, the FNO applied to phase-field forecasting. The framework is a significant contribution to accelerating simulation-heavy control loops. The specific application of FNO to phase-field dynamics is also deemed a reusable mechanism in complex system modeling. No datasets or open questions warranted inclusion based on the scarcity and specificity criteria.

### Approved Concepts
- Surrogate-Assisted Model Predictive Control (MPC): This is the overarching control framework that integrates the learned model (FNO) to enable real-time, high-fidelity control.
- Learned Operator for Phase Evolution Forecasting: The FNO is the core learned component, specifically trained to model the complex spatiotemporal dynamics of the multiphase process for control prediction.

## Links

- [Abstract](https://arxiv.org/abs/2603.25308)
- [PDF](https://arxiv.org/pdf/2603.25308)

