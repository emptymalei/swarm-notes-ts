---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "conformalForecast: An R package for sequential conformal prediction in time series"
description: "The paper presents conformalForecast, an R package designed to provide reliable uncertainty quantification for multistep time series forecasting using conformal prediction. The framework is model-agnostic, allowing it to take point forecasts from any source and apply various calibration schemes, including feedback-based and dependence-aware approaches. A key feature is its support for sequential incremental updates, which maintains calibration states as new data arrives to avoid redundant computations. Experiments on Australian electricity price data demonstrate that the package maintains nominal coverage while significantly improving computational efficiency for rolling-origin forecasts."
resource: "https://arxiv.org/abs/2610.21648"
tags:
  - "conformal-prediction"
  - "uncertainty-quantification"
  - "time-series-forecasting"
  - "multistep-forecasting"
  - "open-source-software"
  - "r-package"
  - "electricity-price-forecasting"
  - "sequential-forecasting"
  - "calibration"
timestamp: "2026-10-18T00:19:28Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xiaoqian Wang"
  - literal: "Daniele Girolimetto"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21648"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "conformal-prediction-regime-shifts"
    description: "How can sequential conformal calibration schemes be optimally adapted to maintain nominal coverage during abrupt regime shifts or structural breaks in time series data?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:19:28Z"
created_at: "2026-10-18T00:19:28Z"
---

# conformalForecast: An R package for sequential conformal prediction in time series

**Authors**: Xiaoqian Wang, Daniele Girolimetto
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21648](https://arxiv.org/abs/2610.21648)

## Summary

The paper presents conformalForecast, an R package designed to provide reliable uncertainty quantification for multistep time series forecasting using conformal prediction. The framework is model-agnostic, allowing it to take point forecasts from any source and apply various calibration schemes, including feedback-based and dependence-aware approaches. A key feature is its support for sequential incremental updates, which maintains calibration states as new data arrives to avoid redundant computations. Experiments on Australian electricity price data demonstrate that the package maintains nominal coverage while significantly improving computational efficiency for rolling-origin forecasts.

## Key Contributions

- Introduces the first integrated R package that decouples point forecasting from calibration for multistep time series workflows.
- Implements a suite of time-series-specific conformal calibration schemes, including empirical-quantile, feedback-based, and dependence-aware methods.
- Develops an efficient incremental updating mechanism that allows for rolling-window updates without recomputing historical calibration states or intervals.
- Provides standardized evaluation tools for tracking coverage, interval width, and scoring rules across multiple forecast horizons.

## Limitations

The paper focuses on the software implementation and evaluation on electricity price data; it does not introduce new theoretical coverage guarantees for non-stationary environments.

## Open Questions & Future Work

- [[conformal-prediction-regime-shifts]]

## Archivist Review

The paper introduces a software package for time-series conformal prediction. While the tool is a contribution to the R ecosystem, specific software implementations are generally excluded from the vault in favor of underlying concepts. The open question regarding regime shifts is approved as it addresses a fundamental and unresolved challenge in applying conformal prediction to non-stationary time series data.

### Approved Open Questions
- Robustness to Regime Shifts in Conformal Forecasting: Ensuring reliability during periods of distribution shift is critical for safety-sensitive applications like energy grid management or financial forecasting.

### Rejected Candidates
- [concept] conformalForecast (`conformal-forecast-package`) - paper_local: This is a specific software package implementation rather than a generalizable machine learning concept or architectural pattern.
- [concept] Sequential Conformal Prediction (`sequential-conformal-prediction`) - duplicate_existing: This is an established sub-field of conformal prediction rather than a novel concept introduced by this specific paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.21648)
- [PDF](https://arxiv.org/pdf/2610.21648)

