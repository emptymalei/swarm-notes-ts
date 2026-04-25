---
# CSL-compatible fields
title: "Hybrid Deep Learning Approach for Coupled Demand Forecasting and Supply Chain Optimization"
author:
  - literal: "Nusrat Yasmin Nadia"
  - literal: "Md Habibul Arif"
  - literal: "Habibor Rahman Rabby"
  - literal: "Md Iftekhar Monzur Tanvir"
  - literal: "Md. Jakir Hossen"
  - literal: "M. F. Mridha"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21567"

# Custom fields
paper_id: "2604.21567"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "optimization"
  - "supply-chain"
architectures:
  []
datasets:
  []
concept_slugs:
  - "haf-ds"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:54:32Z"
created_at: "2026-04-25T04:54:32Z"
---

# Hybrid Deep Learning Approach for Coupled Demand Forecasting and Supply Chain Optimization

**Authors**: Nusrat Yasmin Nadia, Md Habibul Arif, Habibor Rahman Rabby, Md Iftekhar Monzur Tanvir, Md. Jakir Hossen, M. F. Mridha
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21567](https://arxiv.org/abs/2604.21567)

## Summary

This paper addresses the decoupling of demand forecasting and supply chain optimization by introducing a hybrid framework (HAF-DS). HAF-DS utilizes an LSTM architecture for temporal demand modeling and a MILP layer for cost-efficient replenishment and allocation. By jointly training and optimizing these components, the model achieves superior predictive accuracy and significant operational improvements in textile and PPE supply chain management.

## Key Contributions

- Proposed HAF-DS, a coupled framework integrating LSTM demand forecasting with MILP-based prescriptive optimization.
- Achieved a 14.7% reduction in MAE, 12.4% reduction in RMSE, and 14.2% reduction in MAPE compared to existing baselines on textile and PPE supply chain datasets.
- Demonstrated operational improvements, specifically a 5.4% decrease in inventory costs and a 27.5% reduction in stockouts, highlighting the efficacy of jointly optimizing forecasts and supply chain decisions.

## Open Questions & Future Work

- [[robust-forecasting-for-anomalous-demand]]

## Key Concepts

- [[haf-ds]]: A coupled framework integrating LSTM-based temporal demand forecasting with MILP-based inventory optimization for supply chain resilience.

## Archivist Review

The HAF-DS framework is approved for its representative approach of coupling neural forecasting with classical MILP optimization, a pattern that is technically significant for supply chain management. The open question regarding robust forecasting under demand shocks addresses a critical, non-trivial limitation in current time-series modeling for industrial settings. No datasets were approved as they were described as general domain datasets rather than specific named benchmarks.

### Approved Concepts
- Hybrid AI Framework for Demand-Supply Forecasting and Optimization (HAF-DS): It introduces an architecture that bridges deep learning-based forecasting with mathematical optimization for supply chain management.

### Approved Open Questions
- Robust Forecasting for Anomalies: This is a significant bottleneck for real-world supply chain reliability where unexpected disruptions are common.

## Links

- [Abstract](https://arxiv.org/abs/2604.21567)
- [PDF](https://arxiv.org/pdf/2604.21567)

