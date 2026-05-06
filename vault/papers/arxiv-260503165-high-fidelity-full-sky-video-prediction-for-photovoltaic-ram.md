---
# CSL-compatible fields
title: "High-Fidelity Full-Sky Video Prediction for Photovoltaic Ramp Event Forecasting"
author:
  - literal: "Siyuan Wang"
  - literal: "Fengqi You"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.03165"

# Custom fields
paper_id: "2605.03165"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "attention-mechanism"
  - "generative-models"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:13:04Z"
created_at: "2026-05-06T05:13:04Z"
---

# High-Fidelity Full-Sky Video Prediction for Photovoltaic Ramp Event Forecasting

**Authors**: Siyuan Wang, Fengqi You
**Date**: 2026-05-04
**Paper ID**: [arxiv:2605.03165](https://arxiv.org/abs/2605.03165)

## Summary

This paper introduces a multimodal forecasting framework, PhyDiffNet-RaPVFormer, to predict photovoltaic (PV) ramp events by modeling cloud motion dynamics. The system generates high-fidelity full-sky video frames to anticipate cloud-induced irradiance variability up to 16 minutes ahead. By integrating generative video prediction with a ramp-aware PV model, the framework outperforms existing methods in both video quality metrics and critical ramp event detection accuracy.

## Key Contributions

- Proposes a coupled framework linking high-fidelity generative sky video prediction with PV ramp event forecasting.
- Achieves a 10% improvement in Critical Success Index (CSI) for ultra-short-term PV ramp detection (16-minute horizon, 1-minute resolution).
- Enhances model interpretability via attention visualization to identify specific cloud occlusion regions affecting irradiance.

## Archivist Review

The proposed concepts are architecture-specific model names rather than broader, reusable methodological contributions. The paper demonstrates an application of generative video prediction to solar ramp forecasting, but does not introduce a standalone or reusable paradigm beyond this domain-specific integration. No datasets were identified as central or distinct enough to warrant a standalone entry.

### Rejected Candidates
- [concept] PhyDiffNet (`phydiffnet`) - paper_local: This is a paper-specific architecture name rather than a reusable forecasting mechanism or principle.
- [concept] RaPVFormer (`rapvformer`) - paper_local: This is a paper-specific architecture name rather than a reusable forecasting mechanism or principle.

## Links

- [Abstract](https://arxiv.org/abs/2605.03165)
- [PDF](https://arxiv.org/pdf/2605.03165)

