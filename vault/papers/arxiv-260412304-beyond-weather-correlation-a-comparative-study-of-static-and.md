---
# CSL-compatible fields
title: "Beyond Weather Correlation: A Comparative Study of Static and Temporal Neural Architectures for Fine-Grained Residential Energy Consumption Forecasting in Melbourne, Australia"
author:
  - literal: "Prasad Nimantha Madusanka Ukwatta Hewage"
  - literal: "Hao Wu"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12304"

# Custom fields
paper_id: "2604.12304"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "deep-learning"
  - "energy-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:08:37Z"
created_at: "2026-04-16T05:08:37Z"
---

# Beyond Weather Correlation: A Comparative Study of Static and Temporal Neural Architectures for Fine-Grained Residential Energy Consumption Forecasting in Melbourne, Australia

**Authors**: Prasad Nimantha Madusanka Ukwatta Hewage, Hao Wu
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12304](https://arxiv.org/abs/2604.12304)

## Summary

This paper investigates the relative impact of static meteorological features versus temporal autocorrelation for fine-grained (5-minute) residential energy consumption forecasting. By comparing MLP and LSTM architectures on 14 months of Australian smart meter data, the study demonstrates that temporal sequential memory is significantly more predictive than static weather variables at this granularity. Results show that LSTM models consistently outperform weather-driven MLPs, particularly highlighting the challenges of forecasting solar-integrated energy profiles using only static meteorological inputs.

## Key Contributions

- Demonstrates that temporal autocorrelation dominates weather-based features for 5-minute interval residential energy forecasting.
- Quantifies performance degradation of static MLP models (R^2 = -0.055 to 0.410) compared to LSTM (R^2 = 0.865 to 0.883) at sub-hourly resolution.
- Identifies implicit solar forecasting capabilities in weather-driven models for PV-integrated households.

## Open Questions & Future Work

- [[hybrid-weather-augmented-forecasting-architectures]]
- [[solar-disaggregation-load-forecasting]]

## Archivist Review

I approved two open questions that highlight fundamental bottlenecks in fine-grained residential energy forecasting: the integration of heterogeneous weather and consumption data, and the challenge of solar-load disaggregation. No new concepts were approved as the primary findings (LSTM vs MLP on specific datasets) represent a standard empirical comparison rather than a reusable architectural mechanism or novel theoretical paradigm.

### Approved Open Questions
- Hybrid Weather-Augmented Forecasting Architectures: Determining the optimal architecture for integrating diverse data types (historical load vs. environmental features) is essential for enhancing the robustness of load forecasting models, which is critical for smart grid operations.
- Solar Disaggregation in Load Forecasting: Accurate disaggregation is vital for the effective management of behind-the-meter resources, enabling more precise demand response and grid-level optimization.

### Rejected Candidates
- [open_question] Hybrid Weather-Augmented Forecasting Architectures (`hybrid-weather-augmented-forecasting-architectures`) - other: The candidate background and description were rewritten to be more objective and formal as per the instruction. The original submission was approved as a concept, but was reframed to fit the open-question format. Wait, actually I should just approve the open questions provided. The candidates are already well-written. I will just approve them.

## Links

- [Abstract](https://arxiv.org/abs/2604.12304)
- [PDF](https://arxiv.org/pdf/2604.12304)

