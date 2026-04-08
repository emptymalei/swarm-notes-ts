---
# CSL-compatible fields
title: "EAGLE: Edge-Aware Graph Learning for Proactive Delivery Delay Prediction in Smart Logistics Networks"
author:
  - literal: "Zhiming Xue"
  - literal: "Menghao Huo"
  - literal: "Yujue Wang"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.05254"

# Custom fields
paper_id: "2604.05254"
paper_source: "arxiv"
domain: "time-series"
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
processed_at: "2026-04-08T04:57:02Z"
created_at: "2026-04-08T04:57:02Z"
---

# EAGLE: Edge-Aware Graph Learning for Proactive Delivery Delay Prediction in Smart Logistics Networks

**Authors**: Zhiming Xue, Menghao Huo, Yujue Wang
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.05254](https://arxiv.org/abs/2604.05254)

## Summary

EAGLE is a hybrid deep learning framework designed for proactive delivery delay prediction in logistics networks by jointly modeling temporal and spatial dependencies. It utilizes a Transformer-based patch encoder for order-flow dynamics and an Edge-Aware Graph Attention Network (E-GAT) to capture inter-hub relational dependencies. The framework is optimized via multi-task learning and demonstrates high predictive accuracy and training stability on the DataCo Smart Supply Chain dataset compared to standard tabular and anomaly detection approaches.

## Key Contributions

- Introduces EAGLE, a hybrid framework that integrates Transformer patch encoders for order-flow dynamics and E-GAT for inter-hub spatial dependencies.
- Achieves an F1-score of 0.8762 and AUC-ROC of 0.9773 on the DataCo Smart Supply Chain dataset, outperforming existing tabular and time-series baselines.
- Demonstrates superior training stability with a cross-seed F1 standard deviation of 0.0089, showing a 3.8x improvement over ablated variants.

## Open Questions & Future Work

- [[cold-start-delay-prediction-robustness]]
- [[logistics-model-generalization-limits]]

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 0 concept(s), 2 open question(s), and 0 dataset(s), with 1 rejected candidate note(s).

### Approved Open Questions
- Cold-start delay prediction robustness: Maintaining operational reliability in the presence of data scarcity at individual nodes is a critical challenge for industrial supply chain forecasting.
- Logistics model generalization limits: Adaptability to varying network architectures is a fundamental requirement for the broad industrial adoption of supply chain forecasting models.

### Rejected Candidates
- [concept] Edge-Aware Graph Attention Network (E-GAT) (`edge-aware-graph-attention-network-e-gat`) - not_novel: The proposed E-GAT is a specific architectural application that does not represent a sufficiently novel or generalizable mechanism beyond standard graph attention variants.

## Links

- [Abstract](https://arxiv.org/abs/2604.05254)
- [PDF](https://arxiv.org/pdf/2604.05254)

