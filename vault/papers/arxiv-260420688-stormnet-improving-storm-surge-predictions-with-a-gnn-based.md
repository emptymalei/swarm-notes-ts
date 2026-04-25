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
  - "forecasting"
  - "graph-neural-networks"
  - "bias-correction"
  - "spatio-temporal-modeling"
  - "operational-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "stormnet"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:56:03Z"
created_at: "2026-04-25T04:56:03Z"
---

# StormNet: Improving storm surge predictions with a GNN-based spatio-temporal offset forecasting model

**Authors**: Noujoud Nader, Stefanos Giaremis, Clint Dawson, Carola Kaiser, Karame Mohammadiporshokooh, Hartmut Kaiser
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20688](https://arxiv.org/abs/2604.20688)

## Summary

StormNet is a spatio-temporal graph neural network designed to address the inaccuracies inherent in traditional numerical storm surge models like ADCIRC. By combining graph convolutional and attention layers with LSTM units, the model effectively captures the dependencies between coastal water-level gauge stations. It significantly outperforms standard sequential LSTM baselines in long-range forecasting, offering a computationally efficient tool for operational surge prediction.

## Key Contributions

- Introduces StormNet, a hybrid GNN-LSTM architecture that performs bias correction on traditional numerical storm surge models.
- Achieves over 70% RMSE reduction for 48-hour forecasts and over 50% for 72-hour forecasts on Hurricane Idalia (2023) data.
- Demonstrates superior performance over sequential LSTM baselines while maintaining computational efficiency suitable for real-time operational use.

## Open Questions & Future Work

- [[bias-correction-ungauged-locations]]

## Key Concepts

- [[stormnet]]: A spatio-temporal GNN that integrates GCN, GAT, and LSTM components for bias correction in storm surge forecasting.

## Archivist Review

StormNet is approved as it provides a clear, reusable framework for combining GNNs and LSTMs for bias correction in spatio-temporal systems. The open question regarding ungauged locations is approved as it addresses a fundamental, non-boilerplate limitation in geospatial time-series forecasting that limits real-world operational scalability.

### Approved Concepts
- StormNet: It is the primary novel architecture proposed for correcting bias in physical numerical storm surge models.

### Approved Open Questions
- Bias Correction at Ungauged Locations: Extending predictive capabilities to ungauged locations is critical for providing comprehensive coastal flood risk assessments and operational warnings in regions that lack dense gauge station networks.

## Links

- [Abstract](https://arxiv.org/abs/2604.20688)
- [PDF](https://arxiv.org/pdf/2604.20688)

