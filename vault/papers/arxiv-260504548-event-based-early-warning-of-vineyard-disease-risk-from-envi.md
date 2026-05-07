---
# CSL-compatible fields
title: "Event-Based Early Warning of Vineyard Disease Risk from Environmental Time Series"
author:
  - literal: "Ivica Dimitrovski"
  - literal: "Ivan Kitanovski"
  - literal: "Danco Davcev"
  - literal: "Slobodan Kalajdziski"
  - literal: "Kosta Mitreski"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04548"

# Custom fields
paper_id: "2605.04548"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "event-based-disease-risk-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:15:49Z"
created_at: "2026-05-07T05:15:49Z"
---

# Event-Based Early Warning of Vineyard Disease Risk from Environmental Time Series

**Authors**: Ivica Dimitrovski, Ivan Kitanovski, Danco Davcev, Slobodan Kalajdziski, Kosta Mitreski
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04548](https://arxiv.org/abs/2605.04548)

## Summary

This paper addresses the limitations of current vineyard disease prediction models that rely on persistent daily classification. The authors propose an event-based framework that focuses on predicting the onset of risk periods within a 3-7 day window, specifically designed to capture environmental precursors of infection. Through extensive experiments with multiple architectures and an event-oriented evaluation protocol, the study demonstrates that this formulation yields more actionable results than traditional daily classification benchmarks.

## Key Contributions

- Reformulates vineyard disease prediction from daily binary classification to an event-based task predicting risk transitions within a 3-7 day horizon.
- Introduces a minimum disease-free gap constraint to reduce label fragmentation and force the model to learn environmental precursors of disease.
- Benchmarks classical (XGBoost) and deep learning (LSTM, TCN) methods on multi-year agro-meteorological data using an event-oriented evaluation protocol.

## Open Questions & Future Work

- [[pathological-ground-truth-validation-agricultural-forecasting]]

## Key Concepts

- [[event-based-disease-risk-forecasting]]: A forecasting paradigm that predicts the onset of risk periods rather than status to avoid persistence bias and provide actionable early warnings.

## Archivist Review

The paper's event-based reformulation of disease risk prediction effectively addresses persistence bias in environmental forecasting. I approved the concept for its reusable methodological shift. The open question was refined to be more broadly applicable to agricultural forecasting, focusing on the critical validation gap between management proxies and biological ground truth.

### Approved Concepts
- Event-based Disease Risk Forecasting: Shifts the paradigm from standard binary classification of daily states to event detection to mitigate persistence bias in disease warning systems, favoring actionable lead times.

### Approved Open Questions
- Pathological ground truth validation: Bridging the gap between proxy labels and true biological ground truth is critical for moving from experimental models to robust, high-stakes decision support in precision agriculture.

## Links

- [Abstract](https://arxiv.org/abs/2605.04548)
- [PDF](https://arxiv.org/pdf/2605.04548)

