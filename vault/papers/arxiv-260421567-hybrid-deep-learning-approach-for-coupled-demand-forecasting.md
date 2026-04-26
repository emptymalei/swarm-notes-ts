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
  - "supply-chain-optimization"
  - "hybrid-modeling"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "haf-ds"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:09:16Z"
created_at: "2026-04-26T05:09:16Z"
---

# Hybrid Deep Learning Approach for Coupled Demand Forecasting and Supply Chain Optimization

**Authors**: Nusrat Yasmin Nadia, Md Habibul Arif, Habibor Rahman Rabby, Md Iftekhar Monzur Tanvir, Md. Jakir Hossen, M. F. Mridha
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21567](https://arxiv.org/abs/2604.21567)

## Summary

This paper introduces HAF-DS, a hybrid AI framework that integrates LSTM-based demand forecasting with an MILP optimization layer to address supply chain volatility. By jointly optimizing for forecast accuracy and operational efficiency, the framework effectively minimizes replenishment costs and stockouts. Evaluations on textile and PPE supply chain datasets demonstrate that the coupled approach significantly outperforms standard statistical and deep learning baselines in both predictive accuracy and key supply chain performance metrics.

## Key Contributions

- Introduces HAF-DS, a hybrid framework that couples LSTM demand forecasting with MILP optimization for supply chain resilience.
- Demonstrates a 14.7% reduction in MAE and a 12.4% reduction in RMSE compared to baseline models on textile sales datasets.
- Achieves significant operational improvements including a 27.5% reduction in stockouts and a 2.3% increase in service level.

## Open Questions & Future Work

- [[robustness-rare-events-supply-chain-optimization]]

## Key Concepts

- [[haf-ds]]: A framework that couples LSTM-based demand forecasting with MILP optimization for supply chain replenishment and allocation.

## Archivist Review

The paper introduces a well-defined hybrid forecasting-optimization framework. I approved HAF-DS as it represents a distinct approach to coupling predictive and prescriptive layers. I also approved the open question regarding robustness to demand shocks, as it captures a critical bottleneck in deploying these models for real-world, high-stakes supply chain scenarios. No datasets were approved as they were not named explicitly enough to constitute a reusable resource.

### Approved Concepts
- HAF-DS: Integrates demand forecasting with supply chain optimization to minimize forecasting error and operational cost jointly.

### Approved Open Questions
- Robustness to Demand Shocks: Addressing rare-event robustness and scalability to complex, multi-echelon networks is essential for moving these hybrid frameworks from academic benchmarks to reliable, industrial-scale deployment.

## Links

- [Abstract](https://arxiv.org/abs/2604.21567)
- [PDF](https://arxiv.org/pdf/2604.21567)

