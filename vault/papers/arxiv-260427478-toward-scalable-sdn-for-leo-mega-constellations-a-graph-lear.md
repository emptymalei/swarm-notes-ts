---
# CSL-compatible fields
title: "Toward Scalable SDN for LEO Mega-Constellations: A Graph Learning Approach"
author:
  - literal: "Sivaram Krishnan"
  - literal: "Bassel Al Homssi"
  - literal: "Zhouyou Gu"
  - literal: "Jihong Park"
  - literal: "Sung-Min Oh"
  - literal: "Jinho Choi"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27478"

# Custom fields
paper_id: "2604.27478"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "graph-neural-networks"
  - "koopman-theory"
  - "sdn"
  - "leo-constellations"
architectures:
  []
datasets:
  - "starlink"
concept_slugs:
  - "graph-koopman-autoencoder"
dataset_slugs:
  - "starlink"
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:23:19Z"
created_at: "2026-05-01T05:23:19Z"
---

# Toward Scalable SDN for LEO Mega-Constellations: A Graph Learning Approach

**Authors**: Sivaram Krishnan, Bassel Al Homssi, Zhouyou Gu, Jihong Park, Sung-Min Oh, Jinho Choi
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27478](https://arxiv.org/abs/2604.27478)

## Summary

This paper addresses network management bottlenecks in LEO mega-constellations by proposing a hierarchical software-defined networking (SDN) framework. The core of the approach, the Graph Koopman Autoencoder (GKAE), uses GNNs and Koopman theory to linearize complex spatio-temporal dynamics at the orbital shell level. By decomposing the constellation, the central controller can perform globally coordinated management with significantly reduced model complexity. Evaluations on the Starlink constellation demonstrate superior spatial compression and temporal forecasting accuracy compared to existing methods.

## Key Contributions

- Introduces a hierarchical SDN framework for LEO mega-constellations to mitigate management bottlenecks in massive scale networks.
- Develops the Graph Koopman Autoencoder (GKAE) to model satellite constellation dynamics within a linear subspace.
- Achieves 42.8% improvement in spatial compression and 10.81% improvement in temporal forecasting over established baselines on the Starlink dataset.

## Open Questions & Future Work

- [[sdn-controller-placement-tradeoffs]]

## Key Concepts

- [[graph-koopman-autoencoder]]: A neural architecture that combines graph neural networks with Koopman theory to linearize and forecast nonlinear spatio-temporal dynamics in complex, large-scale networks.

## Archivist Review

Approved the Graph Koopman Autoencoder as a reusable mechanism for linearized spatiotemporal forecasting on graphs. The Starlink dataset was approved as a specific, large-scale constellation benchmark. Finally, the controller placement question was selected for its universal relevance to space-based network management.

### Approved Concepts
- Graph Koopman Autoencoder: It is the core architectural innovation, combining graph representations with Koopman operator theory for scalable spatiotemporal forecasting in complex dynamic systems.

### Approved Open Questions
- SDN Controller Placement Trade-offs: Effective controller placement is critical for managing the high-latency and dynamic nature of large-scale LEO networks while ensuring consistent and stable network operations.

## Datasets

- [[starlink]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27478)
- [PDF](https://arxiv.org/pdf/2604.27478)

