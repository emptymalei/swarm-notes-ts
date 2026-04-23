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
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:06:29Z"
created_at: "2026-04-23T05:06:29Z"
---

# Forecasting Individual NetFlows using a Predictive Masked Graph Autoencoder

**Authors**: Georgios Anyfantis, Pere Barlet-Ros
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20483](https://arxiv.org/abs/2604.20483)

## Summary

This paper introduces a Graph Neural Network-based approach for predicting individual network flow-level traffic (NetFlow). The methodology uses sliding windows to represent network traffic as heterogeneous bidirectional graphs, effectively capturing both structural evolution and feature dynamics. Empirical results indicate that this model outperforms traditional baselines in identifying connection-to-node relationships, while maintaining competitive feature reconstruction accuracy.

## Key Contributions

- Proposes a predictive masked graph autoencoder for per-flow network traffic forecasting.
- Introduces a heterogeneous graph construction method representing IP, Port, and Connection entities for NetFlow prediction.
- Demonstrates superior performance in identifying connection-to-node attachment compared to standard forecasting baselines.

## Open Questions & Future Work

- [[variable-graph-size-forecasting]]

## Archivist Review

The paper demonstrates a specific application of GNNs to network traffic forecasting. I approved the open question regarding variable graph size forecasting, as it represents a fundamental limitation of current GNN implementations in high-variability time-series domains. The proposed model and graph construction method were rejected as they are domain-specific applications rather than generalizable architectural primitives.

### Approved Open Questions
- Variable Graph Size Forecasting: Most graph neural network architectures require fixed input dimensions for efficient batch processing, while network traffic exhibits high temporal variability, limiting the deployment of GNNs in dynamic environments.

### Rejected Candidates
- [concept] Predictive Masked Graph Autoencoder (`predictive-masked-graph-autoencoder`) - not_novel: This is a standard application of existing masked autoencoder architectures to a specific domain (NetFlow), lacking sufficient novelty for a standalone concept note.
- [concept] Heterogeneous Graph Construction for NetFlow (`heterogeneous-graph-construction-for-netflow`) - paper_local: Representing specific entities like IP and Port as nodes is a task-specific implementation detail rather than a reusable architectural primitive.

## Links

- [Abstract](https://arxiv.org/abs/2604.20483)
- [PDF](https://arxiv.org/pdf/2604.20483)

