---
# CSL-compatible fields
title: "Improvements to the post-processing of weather forecasts using machine learning and feature selection"
author:
  - literal: "Kazuma Iwase"
  - literal: "Tomoyuki Takenawa"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19340"

# Custom fields
paper_id: "2604.19340"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "meteorological-forecasting"
  - "feature-selection"
architectures:
  []
datasets:
  []
concept_slugs:
  - "event-weighted-training-strategy"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:04:00Z"
created_at: "2026-04-22T05:04:00Z"
---

# Improvements to the post-processing of weather forecasts using machine learning and feature selection

**Authors**: Kazuma Iwase, Tomoyuki Takenawa
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19340](https://arxiv.org/abs/2604.19340)

## Summary

This paper introduces an improved machine learning post-processing framework for weather forecasting, specifically targeting precipitation, temperature, and wind speed across diverse Japanese geographical locations. By leveraging correlation-based feature selection from surrounding grid points and applying LightGBM-based models, the authors outperform raw JMA model forecasts and standard neural network baselines. Additionally, the study addresses the inherent skewness of precipitation data through specialized Tweedie loss functions and event-weighted training, showing marked improvements for extreme rainfall events.

## Key Contributions

- Achieved lower RMSE on precipitation, temperature, and wind speed forecasts compared to raw MSM forecasts and standard CNN baselines.
- Demonstrated the efficacy of correlation-based feature selection utilizing grid-point spatial context for local weather post-processing.
- Enhanced precipitation forecasting at high rainfall thresholds by implementing Tweedie-based loss and event-weighted training strategies to address data skewness.

## Open Questions & Future Work

- [[integrating-site-specific-characteristics-weather-forecasting]]

## Key Concepts

- [[event-weighted-training-strategy]]: A training strategy focused on improving performance for high-threshold extreme events in highly skewed meteorological distributions.

## Archivist Review

The review focused on identifying reusable forecasting strategies for skewed meteorological distributions and the significant, recurring challenge of site-specific bias in weather post-processing. The 'event-weighted training' concept was approved for its broad applicability to extreme-value forecasting, while the open question regarding site-specific integration addresses a fundamental limitation in current spatial-temporal forecasting models. The MSM dataset was rejected as it is a regional proprietary dataset rather than a global research benchmark.

### Approved Concepts
- Event-weighted training strategy: Specifically designed to handle zero-inflated and highly skewed distributions common in precipitation forecasting.

### Approved Open Questions
- Integrating site-specific characteristics in weather forecasting: Addressing this gap is critical because weather forecast performance is inherently tied to local environmental factors, and failing to account for these leads to inconsistent post-processing gains across different geographical sites.

### Rejected Candidates
- [dataset] MSM Dataset (`msm-dataset`) - not_novel: This is a regional proprietary dataset that is not a widely adopted benchmark in the broader ML literature.

## Links

- [Abstract](https://arxiv.org/abs/2604.19340)
- [PDF](https://arxiv.org/pdf/2604.19340)

