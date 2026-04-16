---
# CSL-compatible fields
title: "Outperforming Self-Attention Mechanisms in Solar Irradiance Forecasting via Physics-Guided Neural Networks"
author:
  - literal: "Mohammed Ezzaldin Babiker Abdullah"
  - literal: "Rufaidah Abdallah Ibrahim Mohammed"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13455"

# Custom fields
paper_id: "2604.13455"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "physics-informed-ml"
  - "meteorological-forecasting"
architectures:
  []
datasets:
  - "nasa-power"
concept_slugs:
  - "complexity-paradox-meteorological-forecasting"
dataset_slugs:
  - "nasa-power"
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:06:51Z"
created_at: "2026-04-16T05:06:51Z"
---

# Outperforming Self-Attention Mechanisms in Solar Irradiance Forecasting via Physics-Guided Neural Networks

**Authors**: Mohammed Ezzaldin Babiker Abdullah, Rufaidah Abdallah Ibrahim Mohammed
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13455](https://arxiv.org/abs/2604.13455)

## Summary

This paper introduces a physics-informed hybrid CNN-BiLSTM architecture for Global Horizontal Irradiance (GHI) forecasting, challenging the reliance on complex Transformer-based models. By integrating domain-specific knowledge—such as solar zenith angles and clear-sky indices—as engineered features, the model achieves superior accuracy in high-noise meteorological environments. The results demonstrate a 'Complexity Paradox,' showing that lightweight, physics-guided models provide more robust and efficient performance than computationally intensive self-attention mechanisms.

## Key Contributions

- Introduces a lightweight, physics-informed hybrid CNN-BiLSTM architecture that outperforms Transformer-based models in solar irradiance forecasting.
- Demonstrates that integrating 15 engineered physical features (e.g., Clear-Sky index, Solar Zenith Angle) significantly reduces forecasting error in high-noise environments compared to pure data-driven approaches.
- Achieves a Root Mean Square Error (RMSE) of 19.53 W/m^2 on NASA POWER data, providing empirical evidence for the 'Complexity Paradox' where physical constraints supersede architectural depth.

## Key Concepts

- [[complexity-paradox-meteorological-forecasting]]: The observation that in high-noise meteorological tasks, lightweight models with explicit physical constraints outperform complex, data-hungry attention-based architectures.

## Archivist Review

I approved the 'Complexity Paradox' concept as it represents a significant, reusable heuristic for evaluating architectural choices in high-noise forecasting tasks. I rejected the CNN-BiLSTM architecture candidate as it is a specific implementation choice rather than a broadly reusable concept. The NASA POWER dataset was approved as a standard benchmark source.

### Approved Concepts
- Complexity Paradox (Meteorological Forecasting): Captures a recurring empirical observation in time-series forecasting where domain-specific inductive biases outperform generic, computationally expensive deep learning architectures.

### Rejected Candidates
- [concept] Physics-Informed Hybrid CNN-BiLSTM (`physics-informed-hybrid-cnn-bilstm`) - subcomponent_of_broader_mechanism: This is a specific architectural implementation that does not rise to the level of a foundational concept compared to the overarching 'Complexity Paradox' it demonstrates.

## Datasets

- [[nasa-power]]

## Links

- [Abstract](https://arxiv.org/abs/2604.13455)
- [PDF](https://arxiv.org/pdf/2604.13455)

