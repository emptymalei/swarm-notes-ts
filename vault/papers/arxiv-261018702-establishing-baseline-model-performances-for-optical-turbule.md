---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Establishing baseline model performances for optical turbulence forecasting"
description: "This study addresses the critical need for standardized baselines in optical turbulence (OT) forecasting, which is essential for optimizing telescope adaptive optics and scheduling. The authors propose two reference baseline models—one based on timescale averages and the other on temporal evolution—to provide a benchmark for evaluating complex numerical weather prediction and machine learning models. Using multi-year datasets from the Very Large Telescope (VLT) and Large Binocular Telescope (LBT), the research demonstrates that OT forecasting accuracy must be quantified relative to site-specific baselines rather than in absolute terms due to significant variability across sites, parameters, and timescales."
resource: "https://arxiv.org/abs/2610.18702"
tags:
  - "astrophysics"
  - "forecasting"
  - "benchmarking"
  - "time-series-analysis"
  - "evaluation-metrics"
  - "meteorology"
  - "time-series"
timestamp: "2026-10-18T00:54:09Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "M. De Sepibus"
  - literal: "E. Masciadri"
  - literal: "C. Weinberger"
  - literal: "A. Otarola"
  - literal: "S. Miesske"
  - literal: "C. Veillet"
  - literal: "S. Ragland"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18702"
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
processed_at: "2026-10-18T00:54:09Z"
created_at: "2026-10-18T00:54:09Z"
---

# Establishing baseline model performances for optical turbulence forecasting

**Authors**: M. De Sepibus, E. Masciadri, C. Weinberger, A. Otarola, S. Miesske, C. Veillet, S. Ragland
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18702](https://arxiv.org/abs/2610.18702)

## Summary

This study addresses the critical need for standardized baselines in optical turbulence (OT) forecasting, which is essential for optimizing telescope adaptive optics and scheduling. The authors propose two reference baseline models—one based on timescale averages and the other on temporal evolution—to provide a benchmark for evaluating complex numerical weather prediction and machine learning models. Using multi-year datasets from the Very Large Telescope (VLT) and Large Binocular Telescope (LBT), the research demonstrates that OT forecasting accuracy must be quantified relative to site-specific baselines rather than in absolute terms due to significant variability across sites, parameters, and timescales.

## Key Contributions

- Established standardized baseline performance thresholds for key astroclimatic parameters in optical turbulence (OT) forecasting.
- Proposed and evaluated two distinct baseline models: one focusing on parameter averages and another on temporal evolution over specific timescales.
- Demonstrated through multi-year analysis at VLT and LBT sites that forecasting accuracy is intrinsically tied to site-specific statistical characteristics.
- Formulated a framework for measuring the 'added value' of complex ML and numerical weather prediction models relative to simple statistical baselines.

## Limitations

The study notes that baseline predictive accuracy depends heavily on the specific parameter and observing site, making global absolute accuracy metrics unreliable.

## Archivist Review

The paper focus is on establishing domain-specific benchmarks for optical turbulence forecasting in astrophysics. While the rigorous application of statistical baselines (persistence and averages) is a best practice, it does not constitute a novel machine learning concept. The datasets and open questions are highly localized to telescope site management and do not provide reusable artifacts or research directions for the broader machine learning vault.

### Rejected Candidates
- [concept] Optical Turbulence Forecasting Baselines (`optical-turbulence-forecasting-baselines`) - paper_local: The study establishes benchmarking practices for a specific astronomical domain rather than proposing novel, reusable machine learning methods or architectures.
- [dataset] Very Large Telescope (VLT) Site Dataset (`very-large-telescope-vlt-site-dataset`) - paper_local: These are site-specific astronomical telemetry datasets used for domain-specific validation rather than generalized machine learning benchmarks.
- [dataset] Large Binocular Telescope (LBT) Site Dataset (`large-binocular-telescope-lbt-site-dataset`) - paper_local: These datasets represent local sensor readings from a specific geographic location and do not serve as broadly applicable benchmarks for the ML community.
- [open_question] Extrapolation of OT Reference Baselines (`ot-baseline-extrapolation`) - paper_local: The question focuses on extrapolating performance based on specific astroclimatic parameters (e.g., Fried parameter) rather than generalizable machine learning transfer or meta-learning mechanisms.

## Links

- [Abstract](https://arxiv.org/abs/2610.18702)
- [PDF](https://arxiv.org/pdf/2610.18702)

