---
# CSL-compatible fields
title: "StormNet: Improving storm surge predictions with a GNN-based spatio-temporal offset forecasting model"
author:
  - literal: "Noujoud Nader"
  - literal: "Stefanos Giaremis"
  - literal: "Clint Dawson"
  - literal: "Carola Kaiser"
  - literal: "Karame Mohammadiporshokooh"
  - literal: "Hartmut Kaiser"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20688"

# Custom fields
paper_id: "2604.20688"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "spatio-temporal forecasting"
  - "bias correction"
  - "graph neural networks"
  - "storm surge prediction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "stormnet"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:09:42Z"
created_at: "2026-04-24T05:09:42Z"
---

# StormNet: Improving storm surge predictions with a GNN-based spatio-temporal offset forecasting model

**Authors**: Noujoud Nader, Stefanos Giaremis, Clint Dawson, Carola Kaiser, Karame Mohammadiporshokooh, Hartmut Kaiser
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20688](https://arxiv.org/abs/2604.20688)

## Summary

StormNet is a spatio-temporal graph neural network designed to address the inherent prediction errors of numerical storm surge models like ADCIRC. By combining GCN, GAT, and LSTM mechanisms, the model effectively learns spatial dependencies across water-level gauges and temporal patterns in hurricane dynamics. Empirical evaluation on Hurricane Idalia (2023) demonstrates substantial improvements in forecast accuracy over sequential baselines, particularly for 48-72 hour horizons. The framework's computational efficiency enables rapid deployment in real-time operational settings.

## Key Contributions

- Proposes StormNet, a hybrid GNN-LSTM framework that reduces RMSE in water-level predictions by over 70% for 48-hour forecasts.
- Demonstrates significant accuracy gains over sequential LSTM baselines for long-range (48-72h) storm surge prediction horizons.
- Provides a computationally efficient bias correction method suitable for real-time operational storm surge forecasting systems.

## Open Questions & Future Work

- [[bias-correction-ungauged-locations]]

## Key Concepts

- [[stormnet]]: A spatio-temporal graph neural network architecture designed for bias correction in storm surge numerical models.

## Archivist Review

I approved the StormNet architecture as a reusable concept for bias-correcting physical models, and the open question regarding ungauged locations as it highlights a clear limitation in scaling such systems. I rejected the Hurricane Idalia dataset because it is a single-event evaluation case rather than a comprehensive, reusable research dataset.

### Approved Concepts
- StormNet: It provides a reusable framework for bias-correcting high-fidelity numerical models using spatio-temporal dependencies.

### Approved Open Questions
- Bias-correction ungauged locations: This represents a fundamental bottleneck for scaling predictive storm surge models to data-sparse coastal regions.

## Links

- [Abstract](https://arxiv.org/abs/2604.20688)
- [PDF](https://arxiv.org/pdf/2604.20688)

