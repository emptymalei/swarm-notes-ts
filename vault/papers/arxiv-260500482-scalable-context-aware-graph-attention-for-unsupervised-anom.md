---
# CSL-compatible fields
title: "Scalable Context-Aware Graph Attention for Unsupervised Anomaly Detection in Large-Scale Mobile Networks"
author:
  - literal: "Sara Malacarne"
  - literal: "Eirik Hoel-Høiseth"
  - literal: "Erlend Aune"
  - literal: "David Zsolt Biró"
  - literal: "Massimiliano Ruocco"
issued:
  date-parts:
    - [2026, 5, 1]
url: "https://arxiv.org/abs/2605.00482"

# Custom fields
paper_id: "2605.00482"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "graph-neural-networks"
  - "time-series-forecasting"
architectures:
  []
datasets:
  - "TELCO"
concept_slugs:
  - "c-mtad-gat"
dataset_slugs:
  - "telco"
skill: "TimeSeriesSkill"
processed_at: "2026-05-04T05:15:31Z"
created_at: "2026-05-04T05:15:31Z"
---

# Scalable Context-Aware Graph Attention for Unsupervised Anomaly Detection in Large-Scale Mobile Networks

**Authors**: Sara Malacarne, Eirik Hoel-Høiseth, Erlend Aune, David Zsolt Biró, Massimiliano Ruocco
**Date**: 2026-05-01
**Paper ID**: [arxiv:2605.00482](https://arxiv.org/abs/2605.00482)

## Summary

The paper introduces C-MTAD-GAT, a scalable, unsupervised anomaly detection framework for large-scale mobile network KPI time series. The model leverages joint temporal and feature-wise graph attention, augmented by context conditioning, to provide per-element and per-feature anomaly insights. Evaluations on the TELCO dataset and real-world nation-scale deployment show that C-MTAD-GAT effectively handles nonstationarity and scale without requiring labeled incident data.

## Key Contributions

- Introduces C-MTAD-GAT, an unsupervised graph attention framework for multivariate anomaly detection capable of operating as a single shared model across diverse network elements.
- Integrates temporal and feature-wise graph attention with static and dynamic context conditioning to maintain robustness against nonstationarity and context shifts.
- Demonstrates superior event-level affiliation and pointwise F1 performance on the TELCO benchmark compared to existing graph-attention and VAE-based approaches while reducing false alarm rates.

## Open Questions & Future Work

- [[operational-integration-anomaly-detection]]

## Key Concepts

- [[c-mtad-gat]]: A framework combining temporal and feature-wise graph attention with context conditioning for unsupervised anomaly detection in large-scale time-series networks.

## Archivist Review

I have approved the core anomaly detection framework and the primary dataset used for evaluation. The open question was approved for capturing the critical, unresolved challenge of bridging statistical model outputs with real-world operational workflows. I maintained a strict standard, rejecting any submodules or general terminology in favor of the overarching framework and the most high-impact research bottleneck.

### Approved Concepts
- C-MTAD-GAT: It serves as the core framework proposed by the paper for unsupervised anomaly detection in complex, heterogeneous mobile networks using graph attention.

### Approved Open Questions
- Operational integration of anomaly detection: Closing the loop between statistical model output and actionable operational workflows is essential for the sustainable deployment of AI-based anomaly detection systems in industrial environments.

## Datasets

- [[telco]]

## Links

- [Abstract](https://arxiv.org/abs/2605.00482)
- [PDF](https://arxiv.org/pdf/2605.00482)

