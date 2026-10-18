---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "PING: physics informed graph neural network for advection-diffusion processes with applications to solar power forecasting"
description: "This paper presents PING (Physics Informed Graph Neural Network), a framework for forecasting advection-diffusion processes on irregular spatial grids. By modeling particles as signals on a graph and incorporating discretized partial differential equations into the loss function, the model ensures physical consistency while handling non-Euclidean sensor layouts. The authors demonstrate its efficacy in predicting cloud motion and sea surface temperatures, showing that coupling PING with satellite and ground-based data significantly improves intra-day solar power production forecasts."
resource: "https://arxiv.org/abs/2610.18280"
tags:
  - "physics-informed-machine-learning"
  - "graph-neural-networks"
  - "spatiotemporal-forecasting"
  - "solar-power-forecasting"
  - "time-series"
  - "physics-informed-ml"
timestamp: "2026-10-18T00:58:34Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Jelena Simeunović"
  - literal: "Baptiste Schubnel"
  - literal: "Pierre-Jean Alet"
  - literal: "Pascal Frossard"
  - literal: "Rafael E. Carrillo"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18280"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "physics-informed-graph-neural-network"
    description: "A neural network architecture that incorporates physical laws, such as discretized partial differential equations, as constraints within a graph-based framework to model dynamics on irregular spatial domains."
datasets:
  []
open_questions:
  - name: "physics-loss-weight-optimization"
    description: "Determining the optimal hyperparameter weighting between data-driven loss and physical penalty terms is a persistent bottleneck. Improper balancing can lead to models that either overfit noisy data or fail to converge to physically plausible solutions across different spatial and temporal scales."
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:58:34Z"
created_at: "2026-10-18T00:58:34Z"
---

# PING: physics informed graph neural network for advection-diffusion processes with applications to solar power forecasting

**Authors**: Jelena Simeunović, Baptiste Schubnel, Pierre-Jean Alet, Pascal Frossard, Rafael E. Carrillo
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18280](https://arxiv.org/abs/2610.18280)

## Summary

This paper presents PING (Physics Informed Graph Neural Network), a framework for forecasting advection-diffusion processes on irregular spatial grids. By modeling particles as signals on a graph and incorporating discretized partial differential equations into the loss function, the model ensures physical consistency while handling non-Euclidean sensor layouts. The authors demonstrate its efficacy in predicting cloud motion and sea surface temperatures, showing that coupling PING with satellite and ground-based data significantly improves intra-day solar power production forecasts.

## Key Contributions

- Introduces PING, a Graph Neural Network that incorporates a discretized advection-diffusion equation as a soft constraint to maintain physical consistency in forecasts.
- Develops a graph signal processing approach to handle transport phenomena on spatially irregular sensor networks, such as distributed weather stations.
- Achieves state-of-the-art results on synthetic transport data and real-world datasets including sea surface temperature and cloud index.
- Demonstrates a hybrid solar power forecasting approach that fuses ground-based PV sensor data with satellite cloud concentration images.

## Limitations

The abstract does not specify performance under extreme weather events or the computational cost of the physics-informed constraint on very large graphs.

## Open Questions & Future Work

- [[physics-loss-weight-optimization]]

## Key Concepts

- [[physics-informed-graph-neural-network]]: A neural network architecture that incorporates physical laws, such as discretized partial differential equations, as constraints within a graph-based framework to model dynamics on irregular spatial domains.

## Archivist Review

Approved the Physics-Informed Graph Neural Network (PIGNN) as a central concept because it addresses the critical challenge of maintaining physical consistency in forecasts over irregular spatial domains. The open question regarding physics-data loss balancing was approved as it represents a fundamental, unresolved optimization bottleneck common across the physics-informed ML field. No datasets were approved as none were formally named or provided in the analysis.

### Approved Concepts
- Physics-Informed Graph Neural Network: Enables the application of physical laws (PDEs) to data sampled from irregular, non-Euclidean sensor networks, bridging graph signal processing and physics-informed ML.

### Approved Open Questions
- Optimization of Physics-Data Loss Trade-offs: The trade-off between physical fidelity and empirical accuracy is a critical challenge in deploying hybrid models for complex, real-world atmospheric and environmental dynamics.

### Rejected Candidates
- [concept] Advection-Diffusion on Graphs (`advection-diffusion-graph-signals`) - subcomponent_of_broader_mechanism: This is a specific application/formulation of the broader PIGNN concept rather than a standalone reusable architectural paradigm.

## Links

- [Abstract](https://arxiv.org/abs/2610.18280)
- [PDF](https://arxiv.org/pdf/2610.18280)

