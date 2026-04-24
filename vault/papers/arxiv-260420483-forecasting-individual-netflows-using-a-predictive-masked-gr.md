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
domain: "nlp"
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
processed_at: "2026-04-24T05:10:25Z"
created_at: "2026-04-24T05:10:25Z"
---

# Forecasting Individual NetFlows using a Predictive Masked Graph Autoencoder

**Authors**: Georgios Anyfantis, Pere Barlet-Ros
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20483](https://arxiv.org/abs/2604.20483)

## Summary

This paper introduces a predictive masked graph autoencoder (GNN) for forecasting individual NetFlow traffic. By treating network traffic as evolving heterogeneous graphs of IPs, Ports, and connections, the model captures both structural dynamics and feature evolution. Evaluation shows the approach is particularly effective at identifying flow connectivity while maintaining competitive accuracy for traffic feature reconstruction.

## Key Contributions

- Introduces a predictive masked graph autoencoder for per-flow NetFlow traffic forecasting.
- Models network traffic as heterogeneous bidirectional graphs containing IP, Port, and Connection nodes.
- Demonstrates superior performance in predicting flow attachments to specific Ports and IPs compared to traditional forecasting baselines.

## Open Questions & Future Work

- [[variable-graph-size-gnns]]

## Key Concepts

- [[predictive-masked-graph-autoencoder]]: A Graph Neural Network framework for predicting per-flow network traffic by modeling the evolution of heterogeneous graphs.

## Archivist Review

I have approved the core architecture as a distinct approach to modeling graph-structured time series and added the question regarding variable graph size constraints as it represents a fundamental challenge for applying GNNs in highly dynamic, non-stationary networking environments. Other candidates were not submitted.

### Approved Concepts
- Predictive Masked Graph Autoencoder: The core methodological innovation, combining graph structure evolution and feature prediction for network traffic.

### Approved Open Questions
- Supporting Variable Graph Sizes: Static graph constraints significantly limit the real-world deployment of GNN-based forecasting models for network traffic.

## Links

- [Abstract](https://arxiv.org/abs/2604.20483)
- [PDF](https://arxiv.org/pdf/2604.20483)

