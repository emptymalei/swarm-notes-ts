---
# CSL-compatible fields
title: "Development of Multivariate Attention LSTM Model For Dynamic Line Rating Forecasting"
author:
  - literal: "Anushka Bandara"
  - literal: "Sahan Siriwardena"
  - literal: "Akila Wijethunge"
  - literal: "Janaka Ekanayake"
issued:
  date-parts:
    - [2026, 5, 1]
url: "https://arxiv.org/abs/2605.00486"

# Custom fields
paper_id: "2605.00486"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series"
  - "deep-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-04T05:15:23Z"
created_at: "2026-05-04T05:15:23Z"
---

# Development of Multivariate Attention LSTM Model For Dynamic Line Rating Forecasting

**Authors**: Anushka Bandara, Sahan Siriwardena, Akila Wijethunge, Janaka Ekanayake
**Date**: 2026-05-01
**Paper ID**: [arxiv:2605.00486](https://arxiv.org/abs/2605.00486)

## Summary

This paper introduces a multivariate attention-enhanced LSTM model designed to improve Dynamic Line Rating (DLR) forecasting in power transmission networks. By capturing nonlinear interdependencies among diverse environmental variables—including ambient temperature, wind speed, humidity, and solar irradiance—the model effectively addresses the sensitivity and complexity of DLR predictions. The attention mechanism dynamically prioritizes relevant features, resulting in improved forecast precision and superior performance compared to standard LSTM architectures.

## Key Contributions

- Proposes a multivariate LSTM with attention mechanism to capture nonlinear interdependencies among ambient temperature, wind speed, humidity, and solar irradiance.
- Demonstrates a 95.84% prediction accuracy on real-world DLR data, outperforming the baseline LSTM model (94.62%).
- Provides a mechanism for enhancing Dynamic Line Rating (DLR) to improve power transmission infrastructure utilization and renewable energy integration.

## Archivist Review

The paper proposes a standard application of an attention-augmented LSTM for Dynamic Line Rating (DLR) forecasting. While the model shows improved performance over a baseline, it relies on well-established deep learning building blocks without introducing a novel architectural paradigm, inductive bias, or unique calibration framework that would provide long-term utility in the knowledge vault. Consequently, no concepts, open questions, or datasets were approved.

### Rejected Candidates
- [concept] Multivariate Attention LSTM (`multivariate-attention-lstm`) - not_novel: The proposed architecture is a routine combination of existing standard deep learning components (LSTM and attention) and does not constitute a distinct, novel, or transformative forecasting mechanism deserving of a permanent vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2605.00486)
- [PDF](https://arxiv.org/pdf/2605.00486)

