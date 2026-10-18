---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Velocity-field estimation techniques for on-disk solar coronal bright fronts (CBFs) and shock-wave propagation"
description: "This paper evaluates and optimizes several computer vision algorithms—Lucas–Kanade, Horn–Schunck, Farneback, and Fourier Local Correlation Tracking (FLCT)—for estimating the velocity fields of solar Coronal Bright Fronts (CBFs). Using the X1.5-class solar flare event of May 10, 2022, as a case study, the authors demonstrate how these techniques can map the spatial distribution and deformation of shock waves when applied to wavelet-processed solar imagery. The findings provide a practical framework for automated solar event analysis, which is essential for improving the accuracy and lead time of Solar Energetic Particle (SEP) forecasting."
resource: "https://arxiv.org/abs/2610.19032"
tags:
  - "astrophysics"
  - "computer-vision"
  - "optical-flow"
  - "wavelet-analysis"
  - "spatiotemporal-analysis"
  - "forecasting"
  - "solar-physics"
timestamp: "2026-10-18T00:50:20Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Oleg Stepanyuk"
  - literal: "Kamen Kozarev"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.19032"
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
processed_at: "2026-10-18T00:50:20Z"
created_at: "2026-10-18T00:50:20Z"
---

# Velocity-field estimation techniques for on-disk solar coronal bright fronts (CBFs) and shock-wave propagation

**Authors**: Oleg Stepanyuk, Kamen Kozarev
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.19032](https://arxiv.org/abs/2610.19032)

## Summary

This paper evaluates and optimizes several computer vision algorithms—Lucas–Kanade, Horn–Schunck, Farneback, and Fourier Local Correlation Tracking (FLCT)—for estimating the velocity fields of solar Coronal Bright Fronts (CBFs). Using the X1.5-class solar flare event of May 10, 2022, as a case study, the authors demonstrate how these techniques can map the spatial distribution and deformation of shock waves when applied to wavelet-processed solar imagery. The findings provide a practical framework for automated solar event analysis, which is essential for improving the accuracy and lead time of Solar Energetic Particle (SEP) forecasting.

## Key Contributions

- Benchmarks four classical velocity-field estimation algorithms (Lucas–Kanade, Horn–Schunck, FLCT, and Farneback) specifically for tracking solar Coronal Bright Fronts (CBFs).
- Identifies optimal hyperparameter configurations for these algorithms to facilitate automated shock-wave tracking in operational pipelines without per-event manual tuning.
- Demonstrates the utility of wavelet-based Wavetrack preprocessing in capturing high-resolution velocity distributions and deformations across coronal shock-wave fronts.

## Limitations

The study focuses on a single high-intensity solar event; the derived parameters may require further validation across a wider variety of solar flare classes and background noise levels.

## Archivist Review

The paper is an applied study using established computer vision algorithms for solar physics. It does not introduce novel ML architectures, generalizable concepts, or reusable benchmark datasets. The open question provided is highly specific to the application domain and does not represent a broader research bottleneck in machine learning.

### Rejected Candidates
- [concept] Wavetrack (`wavetrack`) - paper_local: Wavetrack is a domain-specific preprocessing tool for solar physics rather than a novel machine learning architecture or reusable ML technique.
- [concept] Fourier Local Correlation Tracking (FLCT) (`flct`) - not_novel: FLCT is a standard, established algorithm in heliophysics and does not represent a new machine learning contribution.
- [dataset] X1.5-class solar event (10 May 2022) (`x1-5-class-solar-event-dataset`) - low_impact: This is a single solar event used for demonstration, not a structured or widely reusable benchmark dataset.
- [open_question] Automated Parameter Generalization for Solar Tracking (`automated-solar-tracking-generalization`) - other: This is a domain-specific engineering challenge (parameter tuning for solar physics) rather than a fundamental ML research question.

## Links

- [Abstract](https://arxiv.org/abs/2610.19032)
- [PDF](https://arxiv.org/pdf/2610.19032)

