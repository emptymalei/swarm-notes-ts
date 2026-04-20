---
# CSL-compatible fields
title: "Enhancing AI and Dynamical Subseasonal Forecasts with Probabilistic Bias Correction"
author:
  - literal: "Hannah Guan"
  - literal: "Soukayna Mouatadid"
  - literal: "Paulo Orenstein"
  - literal: "Judah Cohen"
  - literal: "Haiyu Dong"
  - literal: "Zekun Ni"
  - literal: "Jeremy Berman"
  - literal: "Genevieve Flaspohler"
  - literal: "Alex Lu"
  - literal: "Jakob Schloer"
  - literal: "Joshua Talib"
  - literal: "Jonathan A. Weyn"
  - literal: "Lester Mackey"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.16238"

# Custom fields
paper_id: "2604.16238"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "probabilistic-forecasting"
  - "weather-forecasting"
  - "bias-correction"
  - "machine-learning-framework"
architectures:
  []
datasets:
  []
concept_slugs:
  - "probabilistic-bias-correction-pbc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:08:22Z"
created_at: "2026-04-20T05:08:22Z"
---

# Enhancing AI and Dynamical Subseasonal Forecasts with Probabilistic Bias Correction

**Authors**: Hannah Guan, Soukayna Mouatadid, Paulo Orenstein, Judah Cohen, Haiyu Dong, Zekun Ni, Jeremy Berman, Genevieve Flaspohler, Alex Lu, Jakob Schloer, Joshua Talib, Jonathan A. Weyn, Lester Mackey
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.16238](https://arxiv.org/abs/2604.16238)

## Summary

This paper introduces Probabilistic Bias Correction (PBC), a machine learning framework designed to mitigate the performance degradation of weather models at subseasonal timescales (2-6 weeks). By learning to correct historical probabilistic forecast outputs, PBC significantly improves the accuracy of both physics-based dynamical models and state-of-the-art AI forecasting systems. Extensive validation against ECMWF datasets and real-time competition results confirms that PBC consistently outperforms leading global forecasting systems across multiple weather variables and lead times.

## Key Contributions

- Introduced Probabilistic Bias Correction (PBC), a post-processing framework for correcting systemic errors in dynamical and AI weather models.
- PBC demonstrated substantial performance gains, doubling the subseasonal skill of the ECMWF AI Forecasting System and improving dynamical model skill across pressure, temperature, and precipitation.
- PBC achieved first place in the 2025 ECMWF real-time forecasting competition, outperforming 34 global teams and various state-of-the-art operational ensembles.

## Open Questions & Future Work

- [[pbc-seasonal-scale-extension]]

## Key Concepts

- [[probabilistic-bias-correction-pbc]]: A machine learning framework that reduces systematic errors in probabilistic weather forecasts by learning from historical forecast biases.

## Archivist Review

The paper introduces a highly effective, reusable post-processing framework for probabilistic forecasting. The concept of Probabilistic Bias Correction (PBC) is approved due to its strong performance and generalizability across diverse forecasting domains. The open question is approved for its significance in pushing the limits of this correction framework into seasonal horizons.

### Approved Concepts
- Probabilistic Bias Correction (PBC): The core novelty of the paper, providing a post-processing framework to mitigate systemic biases in subseasonal weather models.

### Approved Open Questions
- PBC for seasonal forecasting: Extending bias correction beyond subseasonal scales could improve long-term planning for agriculture and energy, which currently depend on forecasts with limited skill.

## Links

- [Abstract](https://arxiv.org/abs/2604.16238)
- [PDF](https://arxiv.org/pdf/2604.16238)

