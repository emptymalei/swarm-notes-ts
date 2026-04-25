---
# CSL-compatible fields
title: "Forecasting Individual NetFlows using a Predictive Masked Graph Autoencoder"
author:
  - literal: "Georgios Anyfantis"
  - literal: "Pere Barlet-Ros"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20483"

# Custom fields
paper_id: "2604.20483"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "predictive-masked-graph-autoencoder"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:56:38Z"
created_at: "2026-04-25T04:56:38Z"
---

# Forecasting Individual NetFlows using a Predictive Masked Graph Autoencoder

**Authors**: Georgios Anyfantis, Pere Barlet-Ros
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20483](https://arxiv.org/abs/2604.20483)

## Summary

This paper introduces a Graph Neural Network (GNN) framework for forecasting individual network flow (NetFlow) traffic by representing traffic as a series of heterogeneous graphs containing IP, Port, and Connection nodes. By leveraging sliding-window sequences of these graphs, the model effectively captures the dynamic evolution of both the network's structural topology and specific connection features. Results demonstrate that the approach significantly outperforms baselines in identifying connection attachment points while remaining competitive in feature reconstruction tasks. The work highlights the efficacy of using GNNs to handle the structured nature of per-flow network traffic prediction.

## Key Contributions

- Introduced a GNN-based model that treats network traffic as a sequence of heterogeneous graphs (IP, Port, Connection nodes) for per-flow forecasting.
- Demonstrated superior performance in identifying connection-to-IP and connection-to-Port associations compared to traditional time-series baselines.
- Established a novel framework for modeling the evolution of network traffic structure alongside connection-level features.

## Open Questions & Future Work

- [[variable-graph-size-forecasting]]

## Key Concepts

- [[predictive-masked-graph-autoencoder]]: A GNN-based framework for forecasting network flow traffic by modeling the evolution of heterogeneous IP, Port, and Connection graph structures.

## Archivist Review

I have approved the core GNN architecture and the open research question concerning dynamic graph sizes. These represent a distinct methodological shift for NetFlow forecasting and a concrete, non-boilerplate research bottleneck. No datasets were approved as none were cited as reusable public benchmarks.

### Approved Concepts
- Predictive Masked Graph Autoencoder: This architecture is the core contribution of the paper, enabling prediction of individual NetFlow traffic patterns by treating network flows as heterogeneous graphs.

### Approved Open Questions
- Supporting variable graph sizes: Supporting variable graph sizes is essential for making GNN-based per-flow forecasting models robust and applicable to real-world network environments where the number of active flows and participants changes over time.

## Links

- [Abstract](https://arxiv.org/abs/2604.20483)
- [PDF](https://arxiv.org/pdf/2604.20483)

