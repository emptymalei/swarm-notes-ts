---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Learning and Forecasting Multiscale Spatiotemporal Epidemic Dynamics with Lagrangian-Eulerian Graph Neural ODEs"
description: "The paper introduces LE-EpiGNODE, a novel Graph Neural ODE framework for long-range epidemic forecasting that decomposes spatiotemporal dynamics into Lagrangian (internal infection generation) and Eulerian (spatial population transport) components. By replacing standard GNN message passing with mechanism-guided operators that incorporate age-contact and mobility data, the model enforces physical structure preservation within a Universal Differential Equation (UDE) framework. Evaluations across 14 synthetic scenarios and three COVID-19 datasets demonstrate that LE-EpiGNODE significantly outperforms 21 baseline models, particularly at longer horizons, while providing verifiable mechanistic interpretability of the learned state fluxes."
resource: "https://arxiv.org/abs/2610.21223"
tags:
  - "epidemiological-modeling"
  - "spatiotemporal-modeling"
  - "neural-odes"
  - "graph-neural-networks"
  - "long-term-forecasting"
  - "forecasting"
  - "mechanistic-interpretability"
  - "differentiable-programming"
timestamp: "2026-10-18T00:24:03Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jinyi Duan"
  - literal: "Qian Li"
  - literal: "Biao Tang"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21223"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "lagrangian-eulerian-gnn-decomposition"
    description: "A spatiotemporal modeling strategy that separates internal state evolution within nodes from conservative mass/population transfer between nodes in a graph structure."
datasets:
  []
open_questions:
  - name: "structure-preservation-flexibility-tradeoff"
    description: "What are the trade-offs between strict structure preservation (e.g., conservative Eulerian transport) and the flexibility needed to capture highly non-stationary or anomalous behavior in real-world spatiotemporal systems?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:24:03Z"
created_at: "2026-10-18T00:24:03Z"
---

# Learning and Forecasting Multiscale Spatiotemporal Epidemic Dynamics with Lagrangian-Eulerian Graph Neural ODEs

**Authors**: Jinyi Duan, Qian Li, Biao Tang
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21223](https://arxiv.org/abs/2610.21223)

## Summary

The paper introduces LE-EpiGNODE, a novel Graph Neural ODE framework for long-range epidemic forecasting that decomposes spatiotemporal dynamics into Lagrangian (internal infection generation) and Eulerian (spatial population transport) components. By replacing standard GNN message passing with mechanism-guided operators that incorporate age-contact and mobility data, the model enforces physical structure preservation within a Universal Differential Equation (UDE) framework. Evaluations across 14 synthetic scenarios and three COVID-19 datasets demonstrate that LE-EpiGNODE significantly outperforms 21 baseline models, particularly at longer horizons, while providing verifiable mechanistic interpretability of the learned state fluxes.

## Key Contributions

- Proposed LE-EpiGNODE, a structure-preserving Graph Neural ODE framework that integrates Lagrangian and Eulerian perspectives for epidemic forecasting.
- Developed mechanism-guided neural operators that align neural message-passing with specific epidemiological processes (age-contact and mobility).
- Achieved a 17.7-40.0% reduction in WMAPE on long-horizon COVID-19 forecasting benchmarks compared to 21 state-of-the-art baselines.
- Demonstrated through synthetic benchmarks that the model's learned operators accurately track known ground-truth mechanistic fluxes, providing interpretability beyond trajectory accuracy.

## Limitations

The model's performance and interpretability depend on the availability of process-specific priors like mobility and age-contact data, which may be noisy or missing in real-world scenarios.

## Open Questions & Future Work

- [[structure-preservation-flexibility-tradeoff]]

## Key Concepts

- [[lagrangian-eulerian-gnn-decomposition]]: A spatiotemporal modeling strategy that separates internal state evolution within nodes from conservative mass/population transfer between nodes in a graph structure.

## Archivist Review

The review focuses on the core methodological innovation of separating spatiotemporal dynamics into Lagrangian and Eulerian components, a principle with broad utility in physical GNN applications. The specific model name was rejected in favor of this general strategy to ensure vault reusability. An open question regarding the inherent trade-offs in structure-preserving models was approved as it represents a fundamental challenge in the intersection of deep learning and differential equations.

### Approved Concepts
- Lagrangian-Eulerian GNN Decomposition: The decomposition allows for individual modeling of internal state changes (Lagrangian) versus spatial interaction/flow (Eulerian), providing a more physically consistent inductive bias than standard message passing.

### Approved Open Questions
- Structure Preservation vs. Modeling Flexibility: Understanding these trade-offs is critical for deploying Universal Differential Equations in safety-critical public health monitoring.

### Rejected Candidates
- [concept] LE-EpiGNODE (`le-epignode`) - paper_local: This is the specific model instance rather than the broader architectural principle; the underlying Lagrangian-Eulerian decomposition is the primary reusable contribution.
- [open_question] Generalization to Unseen Pathogens and Sparse Data (`epidemic-generalization-novel-pathogens`) - paper_local: The question is framed too specifically around epidemiological forecasting; a more reusable open question would address out-of-distribution generalization in non-stationary spatiotemporal systems generally.

## Links

- [Abstract](https://arxiv.org/abs/2610.21223)
- [PDF](https://arxiv.org/pdf/2610.21223)

