---
# CSL-compatible fields
title: "Context-Aware Graph Attention for Unsupervised Telco Anomaly Detection"
author:
  - literal: "Sara Malacarne"
  - literal: "Eirik Hoel-Høiseth"
  - literal: "Erlend Aune"
  - literal: "David Zsolt Biro"
  - literal: "Massimiliano Ruocco"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.27172"

# Custom fields
paper_id: "2604.27172"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "multivariate-time-series"
  - "graph-neural-networks"
  - "unsupervised-learning"
architectures:
  []
datasets:
  - "telco"
concept_slugs:
  - "c-mtad-gat"
dataset_slugs:
  - "telco"
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:09:11Z"
created_at: "2026-05-02T05:09:11Z"
---

# Context-Aware Graph Attention for Unsupervised Telco Anomaly Detection

**Authors**: Sara Malacarne, Eirik Hoel-Høiseth, Erlend Aune, David Zsolt Biro, Massimiliano Ruocco
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27172](https://arxiv.org/abs/2604.27172)

## Summary

C-MTAD-GAT is an unsupervised framework for anomaly detection in multivariate telco time series, leveraging graph attention mechanisms augmented by context embeddings. The architecture employs both a reconstruction head and a multi-step forecaster, with anomaly thresholds derived automatically from validation residuals. Empirical results on the TELCO dataset confirm that the model outperforms state-of-the-art baselines like MTAD-GAT and DC-VAE while maintaining efficiency and resilience in live industrial environments.

## Key Contributions

- Introduces C-MTAD-GAT, an unsupervised framework combining graph attention, context embeddings, and joint reconstruction-forecasting for anomaly detection in mobile networks.
- Demonstrates superior performance over MTAD-GAT and DC-VAE on the TELCO dataset, specifically in event-level and pointwise F1 metrics.
- Validates the approach's robustness and operational viability through deployment in a real-world national mobile operator's core network.

## Open Questions & Future Work

- [[shift-aware-anomaly-detection]]
- [[principled-uncertainty-quantification-ad]]

## Key Concepts

- [[c-mtad-gat]]: A graph-attention based unsupervised framework for multivariate time-series anomaly detection that incorporates external context embeddings and joint reconstruction-forecasting objectives.

## Archivist Review

The C-MTAD-GAT framework is approved for its reusable approach to context-augmented graph-based anomaly detection. The open questions regarding shift-awareness and principled uncertainty in AD are approved as they address fundamental bottlenecks in deployed industrial ML systems. The TELCO dataset is approved as a central evaluation benchmark for this domain.

### Approved Concepts
- Context-Aware Graph Attention for Anomaly Detection (C-MTAD-GAT): The paper introduces a novel architecture that fuses graph attention mechanisms with context embeddings for unsupervised multivariate time-series anomaly detection.

### Approved Open Questions
- Explicitly Shift-Aware Anomaly Detection: Manual or periodic retraining is resource-intensive and potentially slow to react to abrupt shifts, making adaptive, shift-aware models critical for autonomous industrial operations.
- Principled Uncertainty Quantification in AD: Reducing false positive rates is a primary operational challenge in large-scale network monitoring, and uncertainty-aware alerts provide a mechanism to improve human-in-the-loop decision-making.

## Datasets

- [[telco]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27172)
- [PDF](https://arxiv.org/pdf/2604.27172)

