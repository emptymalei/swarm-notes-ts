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
  - "time-series-forecasting"
  - "graph-neural-networks"
  - "software-defined-networking"
  - "spatio-temporal-forecasting"
  - "network-management"
architectures:
  []
datasets:
  - "starlink"
concept_slugs:
  - "graph-koopman-autoencoder"
dataset_slugs:
  - "starlink"
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:08:28Z"
created_at: "2026-05-02T05:08:28Z"
---

# Toward Scalable SDN for LEO Mega-Constellations: A Graph Learning Approach

**Authors**: Sivaram Krishnan, Bassel Al Homssi, Zhouyou Gu, Jihong Park, Sung-Min Oh, Jinho Choi
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27478](https://arxiv.org/abs/2604.27478)

## Summary

This paper addresses the scalability challenges of software-defined networking (SDN) in large-scale LEO satellite constellations by introducing a hierarchical, graph-based architecture. The core innovation is the Graph Koopman Autoencoder (GKAE), which uses Koopman theory to linearize complex, nonlinear satellite network dynamics into a more manageable linear subspace. By aggregating these shell-specific predictions, the system enables efficient, globally coordinated network control with reduced computational footprint. Experimental results using the Starlink topology confirm significant gains in both spatial data compression and temporal forecasting accuracy compared to existing baselines.

## Key Contributions

- Introduces a hierarchical SDN framework for LEO mega-constellations using Graph Koopman Autoencoders (GKAEs) to manage large-scale topology.
- Leverages Koopman theory to linearize nonlinear spatio-temporal dynamics within orbital shells, facilitating efficient global network control.
- Demonstrates a 42.8% improvement in spatial compression and 10.81% improvement in temporal forecasting over established baselines using the Starlink constellation as a benchmark.

## Open Questions & Future Work

- [[optimal-sdn-controller-placement-leo]]

## Key Concepts

- [[graph-koopman-autoencoder]]: A neural architecture that combines graph neural networks with Koopman theory to forecast spatio-temporal dynamics in complex, hierarchical network topologies.

## Archivist Review

I approved the Graph Koopman Autoencoder (GKAE) as a reusable architectural paradigm for nonlinear dynamical systems on graphs. The Starlink dataset was approved as a core benchmark for evaluating LEO constellation management, and the question regarding SDN controller placement was approved as a critical, multi-faceted engineering bottleneck for future satellite networking. The HeteroGNN candidate was rejected as a general evolution of graph learning rather than a paper-specific breakthrough.

### Approved Concepts
- Graph Koopman Autoencoder: It is the central methodological contribution, enabling the linearization of nonlinear satellite constellation dynamics within a graph-based latent space.

### Approved Open Questions
- Optimal SDN Controller Placement: The choice of controller placement fundamentally dictates the feasibility of real-time orchestration for mega-constellations; an suboptimal architecture would exacerbate latency bottlenecks or lead to network instability.

## Datasets

- [[starlink]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27478)
- [PDF](https://arxiv.org/pdf/2604.27478)

