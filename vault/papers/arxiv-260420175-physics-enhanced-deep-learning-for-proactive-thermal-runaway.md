---
# CSL-compatible fields
title: "Physics-Enhanced Deep Learning for Proactive Thermal Runaway Forecasting in Li-Ion Batteries"
author:
  - literal: "Salman Khan"
  - literal: "Muhammad Zunair Zamir"
  - literal: "Syed Sajid Ullah"
  - literal: "Jie Li"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20175"

# Custom fields
paper_id: "2604.20175"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "physics-informed-machine-learning"
  - "time-series-forecasting"
  - "battery-management-systems"
architectures:
  []
datasets:
  []
concept_slugs:
  - "physics-informed-lstm-pi-lstm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:07:42Z"
created_at: "2026-04-23T05:07:42Z"
---

# Physics-Enhanced Deep Learning for Proactive Thermal Runaway Forecasting in Li-Ion Batteries

**Authors**: Salman Khan, Muhammad Zunair Zamir, Syed Sajid Ullah, Jie Li
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20175](https://arxiv.org/abs/2604.20175)

## Summary

This paper introduces a Physics-Informed Long Short-Term Memory (PI-LSTM) framework for proactive thermal runaway forecasting in lithium-ion batteries. By incorporating heat transfer governing equations directly into the training loss function as a regularization term, the model ensures physical consistency and mitigates the erratic oscillations typical of pure data-driven approaches. Evaluated across thirteen battery datasets, the PI-LSTM significantly outperforms standard LSTM, CNN-LSTM, and MLP architectures in prediction accuracy while maintaining computational efficiency for real-time monitoring.

## Key Contributions

- Introduces a Physics-Informed Long Short-Term Memory (PI-LSTM) model that embeds heat transfer equations into the loss function to ensure physical consistency in battery thermal forecasting.
- Demonstrates an 81.9% reduction in RMSE and 81.3% reduction in MAE for temperature evolution prediction compared to standard LSTM baselines.
- Provides an interpretable, real-time capable thermal management framework that eliminates non-physical temperature oscillations common in pure data-driven models.

## Open Questions & Future Work

- [[multidimensional-physics-informed-forecasting-scaling]]
- [[unified-electrochemical-thermal-forecasting]]

## Key Concepts

- [[physics-informed-lstm-pi-lstm]]: A deep learning architecture that integrates governing physical differential equations as a regularization term in the loss function to enforce physical consistency in temporal forecasting.

## Archivist Review

I have approved the PI-LSTM concept, focusing on its mechanism of incorporating governing equations as regularization for temporal networks rather than just its application to batteries. I approved two open questions that highlight fundamental bottlenecks in scaling physics-informed models: the trade-off between spatial dimensionality and real-time computation, and the integration of multi-scale physical processes (electrochemical-thermal). I rejected no candidates because the initial list was high-quality and directly relevant to my criteria.

### Approved Concepts
- Physics-Informed Long Short-Term Memory (PI-LSTM): It provides a novel approach to battery thermal management by constraining deep learning temporal forecasting with thermodynamic principles.

### Approved Open Questions
- Multidimensional physics-informed forecasting scaling: Capturing spatial variations in heat distribution is essential for accurate thermal safety monitoring, yet such modeling often conflicts with real-time requirements.
- Unified electrochemical-thermal forecasting: Decoupling chemical reactions from thermal diffusion limits the predictive accuracy and lead time of safety-critical prognostic models.

## Links

- [Abstract](https://arxiv.org/abs/2604.20175)
- [PDF](https://arxiv.org/pdf/2604.20175)

