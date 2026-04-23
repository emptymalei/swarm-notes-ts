---
# CSL-compatible fields
title: "Adaptive Conformal Anomaly Detection with Time Series Foundation Models for Signal Monitoring"
author:
  - literal: "Natalia Martinez Gil"
  - literal: "Fearghal O'Donncha"
  - literal: "Wesley M. Gifford"
  - literal: "Nianjun Zhou"
  - literal: "Dhaval C. Patel"
  - literal: "Roman Vaculin"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20122"

# Custom fields
paper_id: "2604.20122"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "anomaly-detection"
  - "time-series-forecasting"
  - "conformal-prediction"
  - "foundation-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-conformal-anomaly-detection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:07:50Z"
created_at: "2026-04-23T05:07:50Z"
---

# Adaptive Conformal Anomaly Detection with Time Series Foundation Models for Signal Monitoring

**Authors**: Natalia Martinez Gil, Fearghal O'Donncha, Wesley M. Gifford, Nianjun Zhou, Dhaval C. Patel, Roman Vaculin
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20122](https://arxiv.org/abs/2604.20122)

## Summary

This paper presents a post-hoc conformal anomaly detection framework designed to calibrate outputs from pre-trained time series foundation models. The method provides interpretable, statistical p-values (false alarm rates) by adaptively updating quantile weights based on recent prediction history, allowing for reliable monitoring even under distribution shifts. By avoiding the need for model fine-tuning, the approach enables robust, model-agnostic anomaly detection suitable for rapid deployment in resource-limited industrial settings.

## Key Contributions

- Introduces a post-hoc adaptive conformal calibration framework that converts foundation model predictions into interpretable p-values for anomaly detection.
- Implements weighted quantile conformal prediction with online parameter learning to maintain false alarm control under distribution shifts.
- Demonstrates that the approach operates effectively in resource-constrained, zero-fine-tuning scenarios on diverse time series signals.

## Open Questions & Future Work

- [[context-aware-conformal-weighting-for-time-series]]

## Key Concepts

- [[adaptive-conformal-anomaly-detection]]: A post-hoc framework for calibrating foundation model-based anomaly scores into valid, interpretable false alarm rates.

## Archivist Review

The paper introduces a well-defined post-hoc calibration method that directly addresses the integration of non-fine-tuned foundation models with formal statistical uncertainty quantification. I have approved the adaptive conformal anomaly detection concept as a reusable, model-agnostic pattern. The open question was reframed to focus specifically on the bottleneck of conditioning adaptive weighting on contextual features beyond historical score aggregation, which is a known limitation in current adaptive conformal approaches.

### Approved Concepts
- Adaptive Conformal Anomaly Detection: It introduces a model-agnostic calibration framework that turns time series foundation model outputs into formal statistical p-values for anomaly detection, enabling validity guarantees in zero-shot settings.

### Approved Open Questions
- Context-aware conformal weighting: This research area is critical for deploying robust monitoring systems in industrial environments, where temporal data often exhibits complex, non-periodic, or exogenous-driven distribution shifts that current history-based methods struggle to manage.

### Rejected Candidates
- [open_question] Context-aware conformal weighting research (`context-aware-conformal-weighting-for-time-series-future-work`) - duplicate_existing: This is a duplicate of the contextual refinement question but formatted as an generic observation.

## Links

- [Abstract](https://arxiv.org/abs/2604.20122)
- [PDF](https://arxiv.org/pdf/2604.20122)

