---
# CSL-compatible fields
title: "Graph Neural ODE Digital Twins for Control-Oriented Reactor Thermal-Hydraulic Forecasting Under Partial Observability"
author:
  - literal: "Akzhol Almukhametov"
  - literal: "Doyeong Lim"
  - literal: "Rui Hu"
  - literal: "Yang Liu"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07292"

# Custom fields
paper_id: "2604.07292"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "physics-informed-ml"
  - "graph-neural-networks"
  - "neural-odes"
  - "forecasting"
  - "digital-twin"
architectures:
  []
datasets:
  []
concept_slugs:
  - "graph-neural-ode"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:53:02Z"
created_at: "2026-04-09T04:53:02Z"
---

# Graph Neural ODE Digital Twins for Control-Oriented Reactor Thermal-Hydraulic Forecasting Under Partial Observability

**Authors**: Akzhol Almukhametov, Doyeong Lim, Rui Hu, Yang Liu
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07292](https://arxiv.org/abs/2604.07292)

## Summary

This paper introduces a GNN-ODE surrogate model for real-time thermal-hydraulic forecasting in advanced reactors characterized by partial sensor observability. The architecture integrates spatial message-passing with continuous-time latent dynamics and employs a topology-guided initializer to reconstruct uninstrumented nodes. The model demonstrates high predictive fidelity and physical consistency, successfully recovering underlying heat-transfer correlations while enabling ensemble-based uncertainty quantification.

## Key Contributions

- Introduces a GNN-ODE architecture for thermal-hydraulic state forecasting that reconstructs uninstrumented nodes through a topology-guided initializer.
- Achieves millisecond-scale inference (105x faster than simulated time) while maintaining high accuracy (0.91 K MAE at 60s for uninstrumented states).
- Demonstrates physics-informed learning beyond trajectory fitting by recovering established Reynolds-number heat-transfer correlations using minimal experimental fine-tuning.

## Open Questions & Future Work

- [[node-robustness-noise-mitigation]]
- [[surrogate-topology-transfer]]

## Key Concepts

- [[graph-neural-ode]]: A surrogate architecture that leverages GNNs for topology-aware message passing and Neural ODEs for modeling continuous-time latent dynamics in physical systems.

## Archivist Review

I have approved the GNN-ODE architecture as a central concept for capturing physics-informed spatiotemporal dynamics. I also approved two research questions that identify critical barriers to real-world deployment of such continuous-time models: robustness against noise in the derivative space and generalizability across different network topologies. No datasets were approved as none were explicitly provided with canonical names that would serve as durable references.

### Approved Concepts
- Graph Neural ODE: Combines spatial GNN message passing with continuous-time Neural ODE latent dynamics for physics-informed forecasting under partial observability.

### Approved Open Questions
- Robust NODE-based Dynamics Modeling: Real-world deployment of NODE-based digital twins in safety-critical systems like reactors requires stability guarantees against high-frequency sensor noise, which is inherently amplified during the continuous-time differentiation process.
- Topology Transfer in Surrogates: Validating topology transfer would significantly reduce the computational cost and data requirements for deploying digital twins across diverse reactor designs and experimental facilities.

## Links

- [Abstract](https://arxiv.org/abs/2604.07292)
- [PDF](https://arxiv.org/pdf/2604.07292)

