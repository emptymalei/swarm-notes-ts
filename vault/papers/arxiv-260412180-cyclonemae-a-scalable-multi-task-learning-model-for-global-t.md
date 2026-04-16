---
# CSL-compatible fields
title: "CycloneMAE: A Scalable Multi-Task Learning Model for Global Tropical Cyclone Probabilistic Forecasting"
author:
  - literal: "Renlong Hang"
  - literal: "Zihao Xu"
  - literal: "Jiuwei Zhao"
  - literal: "Runling Yu"
  - literal: "Leye Cheng"
  - literal: "Qingshan Liu"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12180"

# Custom fields
paper_id: "2604.12180"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "multi-modal"
  - "probabilistic-forecasting"
  - "spatiotemporal-modeling"
  - "interpretability"
  - "deep-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "structure-aware-masked-autoencoder"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:08:50Z"
created_at: "2026-04-16T05:08:50Z"
---

# CycloneMAE: A Scalable Multi-Task Learning Model for Global Tropical Cyclone Probabilistic Forecasting

**Authors**: Renlong Hang, Zihao Xu, Jiuwei Zhao, Runling Yu, Leye Cheng, Qingshan Liu
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12180](https://arxiv.org/abs/2604.12180)

## Summary

CycloneMAE is a multi-task masked autoencoder architecture designed for probabilistic tropical cyclone forecasting using multi-modal data. The model utilizes a structure-aware representation learning approach combined with a discrete probabilistic gridding mechanism to overcome the limitations of deterministic deep learning models and high-cost numerical weather prediction systems. Evaluation across five global ocean basins indicates significant improvements in accuracy for pressure, wind, and track forecasting, while integrated gradient analysis confirms the model's ability to interpretably weigh internal and external meteorological drivers over varying horizons.

## Key Contributions

- Introduces CycloneMAE, a multi-task masked autoencoder model that concurrently provides deterministic and probabilistic tropical cyclone forecasts.
- Demonstrates state-of-the-art performance against NWP systems in pressure and wind forecasting (up to 120h) and track forecasting (up to 24h) across five global basins.
- Uncovers distinct spatiotemporal attention patterns where short-term predictions prioritize internal convective structures while long-term predictions favor external environmental drivers.

## Open Questions & Future Work

- [[global-context-integration-forecasting-bottlenecks]]

## Key Concepts

- [[structure-aware-masked-autoencoder]]: A masked autoencoder architecture that incorporates domain-specific spatial structural constraints to learn better representations for high-dimensional, multi-modal spatiotemporal data.

## Archivist Review

I approved the concept of structure-aware masked autoencoders as a generalized mechanism for incorporating spatial inductive bias into reconstruction-based models. I also approved a refined version of the open question regarding global-local context integration in forecasting, as this represents a significant structural challenge for modern deep learning weather models. Tropical cyclone-specific terminology was abstracted to allow for broader applicability.

### Approved Concepts
- Structure-Aware Masked Autoencoder: Provides a generalized approach for injecting domain-specific spatial inductive biases into masked autoencoders for spatiotemporal forecasting.

### Approved Open Questions
- Global Context Integration Bottlenecks: This bottleneck defines the fundamental limitation of current data-driven approaches in meteorology compared to physics-based dynamical cores.

### Rejected Candidates
- [concept] TC structure-aware masked autoencoder (`tc-structure-aware-masked-autoencoder`) - duplicate_existing: Renamed to a more generalized version 'structure-aware-masked-autoencoder' to improve reusability across domains.

## Links

- [Abstract](https://arxiv.org/abs/2604.12180)
- [PDF](https://arxiv.org/pdf/2604.12180)

