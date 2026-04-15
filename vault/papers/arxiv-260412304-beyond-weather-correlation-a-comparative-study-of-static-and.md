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
  - "time-series-forecasting"
  - "energy-consumption-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:04:31Z"
created_at: "2026-04-15T05:04:31Z"
---

# Beyond Weather Correlation: A Comparative Study of Static and Temporal Neural Architectures for Fine-Grained Residential Energy Consumption Forecasting in Melbourne, Australia

**Authors**: Prasad Nimantha Madusanka Ukwatta Hewage, Hao Wu
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12304](https://arxiv.org/abs/2604.12304)

## Summary

This paper provides a comparative study between static MLP architectures and temporal LSTM models for short-term residential energy forecasting at a fine-grained 5-minute resolution. Using 14 months of smart meter data from two Melbourne households, the study finds that temporal autocorrelation is a more dominant driver of consumption accuracy than static meteorological variables. The results show that while LSTMs effectively capture consumption sequences, weather-driven MLPs struggle, particularly in standard grid-connected dwellings. The work highlights the necessity of sequence-aware modeling for high-frequency energy demand forecasting.

## Key Contributions

- Empirically demonstrates that temporal autocorrelation in consumption sequences significantly outperforms weather-based features for 5-minute residential energy forecasting.
- Establishes that LSTMs achieve R^2 values of 0.883 and 0.865 for grid-connected and PV-integrated households, respectively, vastly outperforming static MLP benchmarks.
- Quantifies the performance gap between temporal and static architectures, revealing a 93.8% improvement for standard households and 45.5% for solar-integrated dwellings.

## Open Questions & Future Work

- [[solar-integrated-load-disaggregation]]
- [[federated-residential-load-forecasting]]

## Archivist Review

The paper provides a standard empirical comparison between static MLP and temporal LSTM models for short-term energy forecasting, which, while useful for the authors' specific context, does not introduce novel concepts worthy of permanent vault status. The open questions regarding solar load disaggregation and federated privacy in residential settings are significant, recurring challenges in the field and have been approved.

### Approved Open Questions
- Solar-Integrated Load Disaggregation: Separating these signals is critical for enabling precise demand response, battery optimization, and grid management in solar-dense residential areas.
- Federated Residential Load Forecasting: Federated learning is vital for developing generalized, robust forecasting models that respect consumer privacy and institutional data restrictions.

### Rejected Candidates
- [concept] Temporal vs. Static Architecture Comparison (`temporal-vs-static-architecture-comparison`) - not_novel: Comparative performance of MLP and LSTM is a well-known result in time-series literature and does not represent a reusable, novel architectural mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.12304)
- [PDF](https://arxiv.org/pdf/2604.12304)

