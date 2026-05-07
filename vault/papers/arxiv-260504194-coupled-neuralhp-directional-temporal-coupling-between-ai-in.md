---
# CSL-compatible fields
title: "Coupled-NeuralHP: Directional Temporal Coupling Between AI Innovation Exposure and Public Response"
author:
  - literal: "Amir Rafe"
  - literal: "Subasish Das"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.04194"

# Custom fields
paper_id: "2605.04194"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "coupled-neuralhp"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:17:03Z"
created_at: "2026-05-07T05:17:03Z"
---

# Coupled-NeuralHP: Directional Temporal Coupling Between AI Innovation Exposure and Public Response

**Authors**: Amir Rafe, Subasish Das
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.04194](https://arxiv.org/abs/2605.04194)

## Summary

Coupled-NeuralHP is a hybrid neural Hawkes process model designed to analyze the directional coupling between irregular streams of AI patent publications and longitudinal public response data. By integrating event-driven innovation metrics with monthly state-based indicators, the model outperforms traditional benchmarks in forecasting innovation counts and reconstructing innovation-to-response dynamics. Through extensive ablation and semi-synthetic testing, the study demonstrates that innovation significantly drives response, while the reverse influence remains statistically unsupported in held-out predictions.

## Key Contributions

- Proposed Coupled-NeuralHP, a hybrid model linking irregular AI patent event streams with monthly Google Trends response indices.
- Achieved superior held-out innovation count forecasting (RMSE 471 vs. 532) compared to registered benchmarks.
- Demonstrated superior causal link recovery (F1 = 0.734 vs. 0.386) in semi-synthetic experiments compared to VARX.

## Open Questions & Future Work

- [[coupling-event-level-innovation-aggregate-response]]

## Key Concepts

- [[coupled-neuralhp]]: A hybrid model combining neural Hawkes processes with state-based time series to capture directional causal coupling between irregular events and continuous signals.

## Archivist Review

I approved the Coupled-NeuralHP model as a distinct architectural contribution to cross-resolution time-series forecasting. The proposed open question was refined to capture the theoretical challenge of reconciling continuous event streams with discrete aggregate indicators rather than focusing on the specific domain of AI patents. The proposed datasets were rejected as they represent generic data sources rather than specific, archival benchmarks.

### Approved Concepts
- Coupled-NeuralHP: It provides a novel, learnable neural architecture for coupling irregular event processes with regularly sampled time series.

### Approved Open Questions
- Event-State Causal Coupling Modeling: Characterizing the directional interplay between technological output and latent social response is a fundamental challenge for quantitative social science and innovation forecasting.

### Rejected Candidates
- [dataset] USPTO AI patent publication streams (`uspto-ai-patent-publication-streams`) - generic: This is a broad class of government data rather than a specific, cited benchmark dataset with a fixed versioning history.
- [dataset] Google Trends response index (`google-trends-response-index`) - generic: This refers to a general data source/platform index rather than a distinct, standardized evaluation dataset.

## Links

- [Abstract](https://arxiv.org/abs/2605.04194)
- [PDF](https://arxiv.org/pdf/2605.04194)

