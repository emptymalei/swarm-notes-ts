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
  - "hybrid-modeling"
  - "time-series-analysis"
architectures:
  []
datasets:
  - "nasa-power"
concept_slugs:
  - "complexity-paradox-meteorological-forecasting"
dataset_slugs:
  - "nasa-power"
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:54:43Z"
created_at: "2026-04-18T04:54:43Z"
---

# Outperforming Self-Attention Mechanisms in Solar Irradiance Forecasting via Physics-Guided Neural Networks

**Authors**: Mohammed Ezzaldin Babiker Abdullah, Rufaidah Abdallah Ibrahim Mohammed
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13455](https://arxiv.org/abs/2604.13455)

## Summary

This paper presents a physics-informed hybrid CNN-BiLSTM framework designed for Global Horizontal Irradiance (GHI) forecasting in arid regions. By integrating 15 domain-specific features, such as Clear-Sky indices, the model bypasses the need for computationally heavy Transformer architectures. Experimental results on NASA POWER data show that this approach achieves superior accuracy over attention-based baselines, supporting the 'Complexity Paradox' where physical guidance outperforms purely data-driven complexity in high-noise environments.

## Key Contributions

- Introduces a lightweight, Physics-Informed Hybrid CNN-BiLSTM framework for Global Horizontal Irradiance (GHI) forecasting.
- Achieves an RMSE of 19.53 W/m^2, significantly outperforming transformer-based baselines (RMSE 30.64 W/m^2) on the NASA POWER dataset.
- Demonstrates that integrating 15 physics-based features (e.g., Clear-Sky indices) provides superior performance compared to pure data-driven self-attention approaches.

## Key Concepts

- [[complexity-paradox-meteorological-forecasting]]: The observation that explicit physical constraints can outperform deep self-attention models in high-noise meteorological forecasting tasks.

## Archivist Review

I have approved the 'Complexity Paradox' concept as it represents a significant, recurring theme in time-series forecasting research regarding the balance of model complexity and inductive bias. The NASA POWER dataset is approved as it is a widely recognized resource for solar energy modeling. Other components were rejected as they represent specific implementation choices rather than generalizable architectural or methodological advancements.

### Approved Concepts
- Complexity Paradox in Meteorological Forecasting: Provides a theoretical justification for choosing lighter, physics-guided models over larger, attention-based architectures in noisy settings.

### Rejected Candidates
- [concept] Physics-Informed Hybrid CNN-BiLSTM Framework (`physics-informed-cnn-bilstm-framework`) - subcomponent_of_broader_mechanism: This is a specific architectural implementation that is less broadly applicable than the overarching physical guidance principle.

## Datasets

- [[nasa-power]]

## Links

- [Abstract](https://arxiv.org/abs/2604.13455)
- [PDF](https://arxiv.org/pdf/2604.13455)

