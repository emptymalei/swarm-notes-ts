---
# CSL-compatible fields
title: "Storm Surge Modeling, Bias Correction, Graph Neural Networks, Graph Convolution Networks"
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
  - "time-series-forecasting"
  - "graph-neural-networks"
  - "spatiotemporal-modeling"
  - "climate-modeling"
  - "bias-correction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "stormnet"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:05:53Z"
created_at: "2026-04-23T05:05:53Z"
---

# Storm Surge Modeling, Bias Correction, Graph Neural Networks, Graph Convolution Networks

**Authors**: Noujoud Nader, Stefanos Giaremis, Clint Dawson, Carola Kaiser, Karame Mohammadiporshokooh, Hartmut Kaiser
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20688](https://arxiv.org/abs/2604.20688)

## Summary

StormNet is a spatio-temporal graph neural network developed to address bias and uncertainty in numerical storm surge models. By integrating graph convolutional and graph attention layers with LSTM units, the model captures complex spatio-temporal interactions between coastal water-level gauge stations. Validated against Hurricane Idalia (2023), StormNet demonstrates significant RMSE reductions compared to sequential LSTM baselines, offering a scalable and efficient solution for operational storm surge forecasting.

## Key Contributions

- Introduces StormNet, a spatio-temporal GNN combining GCN, GAT, and LSTM components to bias-correct storm surge forecasts.
- Achieves over 70% reduction in RMSE for 48-hour forecasts and over 50% for 72-hour forecasts during Hurricane Idalia (2023).
- Demonstrates superior performance over sequential LSTM baselines and provides computational efficiency suitable for real-time operational systems.

## Open Questions & Future Work

- [[bias-correction-ungauged-locations]]

## Key Concepts

- [[stormnet]]: A spatio-temporal graph neural network combining GCN, GAT, and LSTM mechanisms for the bias correction of numerical model forecasts.

## Archivist Review

The review process focused on identifying reusable modeling frameworks and substantial research bottlenecks in climate-related time-series forecasting. StormNet was approved as a representative architecture for spatio-temporal bias correction, while the open question regarding ungauged locations was approved due to its significance for scaling environmental hazard systems. Other candidates were rejected as they were either paper-local or represented routine performance reporting.

### Approved Concepts
- StormNet: It provides a specific framework for integrating GCN, GAT, and LSTM architectures to perform bias correction in spatio-temporal sensor networks.

### Approved Open Questions
- Bias correction at ungauged locations: Generalizing model outputs to regions lacking physical sensors is critical for scaling disaster response frameworks beyond existing observation points.

### Rejected Candidates
- [concept] StormNet (`stormnet`) - duplicate_existing: The concept is being approved; however, this is a redundant entry record.

## Links

- [Abstract](https://arxiv.org/abs/2604.20688)
- [PDF](https://arxiv.org/pdf/2604.20688)

