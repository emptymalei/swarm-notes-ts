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
  - "graph-neural-networks"
  - "multivariate-time-series"
  - "telecommunications"
architectures:
  []
datasets:
  - "TELCO"
concept_slugs:
  - "context-aware-graph-attention-anomaly-detection"
dataset_slugs:
  - "telco"
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:24:11Z"
created_at: "2026-05-01T05:24:11Z"
---

# Context-Aware Graph Attention for Unsupervised Telco Anomaly Detection

**Authors**: Sara Malacarne, Eirik Hoel-Høiseth, Erlend Aune, David Zsolt Biro, Massimiliano Ruocco
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27172](https://arxiv.org/abs/2604.27172)

## Summary

This paper introduces C-MTAD-GAT, an unsupervised anomaly detection framework for multivariate mobile network telemetry. The model leverages graph attention and context embeddings through a dual-head architecture consisting of a deterministic reconstruction head and a multi-step forecaster. By automating anomaly threshold calibration using validation residuals, the method eliminates the need for labeled data while demonstrating state-of-the-art performance on the TELCO benchmark and real-world industrial deployments.

## Key Contributions

- C-MTAD-GAT achieves superior event-level and pointwise F1 performance compared to MTAD-GAT and DC-VAE on the public TELCO dataset.
- The framework utilizes a combination of deterministic reconstruction and multi-step forecasting to generate robust anomaly scores without supervision.
- Implements an automated, label-free threshold calibration mechanism based on validation residuals for practical, zero-label deployment.

## Open Questions & Future Work

- [[explicit-shift-aware-anomaly-detection]]
- [[principled-uncertainty-quantification-ad]]

## Key Concepts

- [[context-aware-graph-attention-anomaly-detection]]: An unsupervised framework for multivariate anomaly detection that uses context-aware graph attention with dual reconstruction and forecasting heads.

## Archivist Review

The paper proposes an anomaly detection framework using a dual-head approach (reconstruction and forecasting) with graph-based context awareness. I have approved the framework as a concept and included the two open questions regarding shift-awareness and uncertainty quantification, as these are significant, long-standing bottlenecks in operational industrial anomaly detection. The TELCO dataset was approved for its role in benchmarking industrial performance.

### Approved Concepts
- Context-Aware Graph Attention for Anomaly Detection: Integrates context embeddings with graph attention mechanisms for time-series anomaly detection, providing a generalizable pattern for multi-source telemetry data analysis.

### Approved Open Questions
- Explicit Shift-Aware Anomaly Detection: Industrial anomaly detection systems must be robust to non-stationary environments; addressing distribution shifts directly is necessary to maintain high precision and low false-positive rates over time.
- Principled Uncertainty Quantification for AD: Operators require reliable signals to manage large-scale systems effectively; uncertainty quantification directly addresses the critical bottleneck of actionable alarm generation.

### Rejected Candidates
- [concept] C-MTAD-GAT (`c-mtad-gat`) - subcomponent_of_broader_mechanism: This is a specific model implementation; the underlying architecture and approach are better captured by a broader concept slug.

## Datasets

- [[telco]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27172)
- [PDF](https://arxiv.org/pdf/2604.27172)

