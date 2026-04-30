---
# CSL-compatible fields
title: "Prediction of Celestial Pole Offsets Based on Sliding Window and Bivariate Least Squares Fitting"
author:
  - literal: "Wang Wei-long"
  - literal: "Wu Yuan-wei"
  - literal: "Li Xi-shun"
  - literal: "Qiao Hai-hua"
  - literal: "Kong Qiao"
  - literal: "Yang Hai-yan"
  - literal: "Yang Xu-hai"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26293"

# Custom fields
paper_id: "2604.26293"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "bivariate-least-squares-sliding-window-forecasting"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-30T05:14:15Z"
created_at: "2026-04-30T05:14:15Z"
---

# Prediction of Celestial Pole Offsets Based on Sliding Window and Bivariate Least Squares Fitting

**Authors**: Wang Wei-long, Wu Yuan-wei, Li Xi-shun, Qiao Hai-hua, Kong Qiao, Yang Hai-yan, Yang Xu-hai
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26293](https://arxiv.org/abs/2604.26293)

## Summary

This paper presents a sliding window-based bivariate least squares fitting algorithm to improve the prediction of Celestial Pole Offsets (CPO), a critical component of Earth Orientation Parameters. By optimizing the sliding window length to 900 days, the proposed method provides robust extrapolation of CPO time series data. Experimental results demonstrate consistent performance improvements over current state-of-the-art models and IERS official predictions across both historical (EOP 14 C04) and updated (EOP 20 C04) datasets.

## Key Contributions

- Developed a sliding window bivariate least squares algorithm that achieves superior Mean Absolute Error (MAE) compared to top-performing models (ID154, ID155) from the 2nd EOP PCC.
- Demonstrated significant forecast accuracy improvements over standard IERS daily publication results, with up to 60% reduction in MAE for dX and 42% for dY over 57-day horizons.
- Validated the method's robustness across different data series (EOP 14 C04 and EOP 20 C04).

## Open Questions & Future Work

- [[pn-model-geodynamic-variability-integration]]

## Key Concepts

- [[bivariate-least-squares-sliding-window-forecasting]]: A time-series forecasting approach for geodetic parameters that uses bivariate least squares fitting optimized over a fixed-length sliding window.

## Archivist Review

The paper's contribution of using a simple bivariate least squares fitting optimized over a sliding window represents a standard yet effective geodetic forecasting pattern, deserving a generalizable concept entry. The open question was refined to highlight the specific geophysical modeling bottleneck (time-varying parameters in PN models) that limits current forecasting. Datasets were rejected as they represent generic standard IERS data files, not novel or unique research datasets.

### Approved Concepts
- Bivariate Least Squares Sliding Window Forecasting: The paper demonstrates that simple, well-tuned bivariate least squares over a data-driven optimal sliding window can outperform complex models in specialized geodetic time-series forecasting.

### Approved Open Questions
- Integrating Geodynamic Variability into PN Models: This addresses a fundamental modeling deficiency that limits current forecasting performance regardless of the statistical algorithm used.

### Rejected Candidates
- [concept] Bivariate Least Squares Fitting for EOP Prediction (`bivariate-least-squares-fitting-for-eop-prediction`) - other: The concept was renamed for broader applicability as 'Bivariate Least Squares Sliding Window Forecasting'.
- [open_question] CPO Prediction via New PN Models (`cpo-prediction-new-pn-model`) - other: Renamed to 'Integrating Geodynamic Variability into PN Models' for better clarity and focus on the geophysical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.26293)
- [PDF](https://arxiv.org/pdf/2604.26293)

