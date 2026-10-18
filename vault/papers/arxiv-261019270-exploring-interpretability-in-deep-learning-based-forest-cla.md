---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Exploring Interpretability in Deep Learning-Based Forest Classification - Separating Similar Forest Classes using Sentinel-2 Time Series"
description: "This paper evaluates the performance of Recurrent Neural Networks (RNNs) for pixel-level tree-species classification using Sentinel-2 satellite time series, specifically targeting the difficult task of separating pure Norway spruce from mixed forest pixels. To overcome the black-box nature of deep learning, the authors utilize Integrated Gradients to identify the spectral bands and temporal windows most critical for discrimination. Results indicate that RNNs (0.851 Macro-F1) outperform traditional baselines, and attribution analysis reveals that Short-Wave Infrared bands and late spring phenological stages are the most informative features for accurate species mapping."
resource: "https://arxiv.org/abs/2610.19270"
tags:
  - "time-series-classification"
  - "remote-sensing"
  - "explainable-ai"
  - "interpretability"
  - "computer-vision"
  - "time-series-analysis"
timestamp: "2026-10-18T00:47:08Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Maximilian Kirsch"
  - literal: "Christine Preisach"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.19270"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:47:08Z"
created_at: "2026-10-18T00:47:08Z"
---

# Exploring Interpretability in Deep Learning-Based Forest Classification - Separating Similar Forest Classes using Sentinel-2 Time Series

**Authors**: Maximilian Kirsch, Christine Preisach
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.19270](https://arxiv.org/abs/2610.19270)

## Summary

This paper evaluates the performance of Recurrent Neural Networks (RNNs) for pixel-level tree-species classification using Sentinel-2 satellite time series, specifically targeting the difficult task of separating pure Norway spruce from mixed forest pixels. To overcome the black-box nature of deep learning, the authors utilize Integrated Gradients to identify the spectral bands and temporal windows most critical for discrimination. Results indicate that RNNs (0.851 Macro-F1) outperform traditional baselines, and attribution analysis reveals that Short-Wave Infrared bands and late spring phenological stages are the most informative features for accurate species mapping.

## Key Contributions

- Demonstrated that RNNs achieve a superior Macro-F1 score (0.851) for tree-species classification compared to Random Forest and XGBoost baselines.
- Applied Integrated Gradients to quantify spectral-temporal feature attributions, identifying that spectral band B11 (SWIR) is a primary driver for distinguishing spruce compositions.
- Identified that the most informative phenological window for separating pure and mixed Norway spruce pixels begins after approximately Day of Year 125.

## Limitations

The study focuses on a specific geographic region and forest type (Norway spruce), and it is unclear how well these spectral-temporal patterns generalize to other species or climates.

## Archivist Review

The paper is a domain-specific application of existing ML techniques (RNNs and Integrated Gradients) to forest classification. It does not introduce novel architectures, reusable mechanisms, or benchmark datasets that meet the criteria for permanent vault notes. The proposed open question is a standard generalization inquiry common in remote sensing and does not represent a new fundamental research direction for the ML vault.

### Rejected Candidates
- [open_question] Geographic Generalization of Spectral-Temporal Features (`geographic-generalization-forest-classification`) - generic: The question essentially calls for more empirical validation across different geographic regions, which falls under standard future work/more experiments rather than a fundamental unresolved ML bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2610.19270)
- [PDF](https://arxiv.org/pdf/2610.19270)

