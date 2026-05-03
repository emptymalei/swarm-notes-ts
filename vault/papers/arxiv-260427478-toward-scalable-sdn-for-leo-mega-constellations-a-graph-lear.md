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
  - "graph-neural-networks"
  - "software-defined-networking"
  - "leo-satellite-networks"
  - "spatio-temporal-forecasting"
architectures:
  []
datasets:
  - "starlink"
concept_slugs:
  - "graph-koopman-autoencoder"
dataset_slugs:
  - "starlink"
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:15:13Z"
created_at: "2026-05-03T05:15:13Z"
---

# Toward Scalable SDN for LEO Mega-Constellations: A Graph Learning Approach

**Authors**: Sivaram Krishnan, Bassel Al Homssi, Zhouyou Gu, Jihong Park, Sung-Min Oh, Jinho Choi
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27478](https://arxiv.org/abs/2604.27478)

## Summary

This paper presents a scalable, hierarchical software-defined networking (SDN) framework for LEO satellite constellations. To overcome the computational complexity of managing thousands of satellites, the authors utilize a Graph Koopman Autoencoder (GKAE) that combines GNN-based topology modeling with Koopman-theoretic linearization. This approach enables efficient spatio-temporal forecasting of constellation behavior, significantly improving both spatial compression and temporal accuracy compared to existing baselines.

## Key Contributions

- Introduces a hierarchical SDN framework for LEO satellite constellations that employs GNNs for topological representation.
- Proposes the Graph Koopman Autoencoder (GKAE) to linearize non-linear network dynamics within a latent subspace.
- Demonstrates that the GKAE achieves a 42.8% improvement in spatial compression and a 10.81% improvement in temporal forecasting on the Starlink constellation benchmark.

## Open Questions & Future Work

- [[controller-placement-tradeoffs-sdn-leo]]
- [[heterogeneous-graph-learning-6g-ntn]]

## Key Concepts

- [[graph-koopman-autoencoder]]: A model architecture that integrates GNNs with Koopman theory to linearize and forecast non-linear spatio-temporal dynamics in network topologies.

## Archivist Review

The proposed Graph Koopman Autoencoder (GKAE) is approved as a reusable architecture for spatiotemporal network modeling. Two open questions addressing controller placement trade-offs and heterogeneous graph learning requirements in 6G/NTN contexts were approved for their significance to future large-scale satellite networking research. Starlink was approved as a named dataset central to the evaluation of LEO constellation management strategies.

### Approved Concepts
- Graph Koopman Autoencoder: GKAE is central to the paper's novel approach of combining GNN topology representation with Koopman linearization for forecasting constellation dynamics.

### Approved Open Questions
- Controller Placement in SDN-LEO: The controller placement determines the feasibility of real-time network orchestration and the overall resilience of the software-defined architecture in mega-constellations.
- Heterogeneous Graph Learning for 6G: Heterogeneity is an essential characteristic of 6G non-terrestrial networks, and current homogeneous GNN models cannot effectively optimize resources across multi-domain environments.

## Datasets

- [[starlink]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27478)
- [PDF](https://arxiv.org/pdf/2604.27478)

