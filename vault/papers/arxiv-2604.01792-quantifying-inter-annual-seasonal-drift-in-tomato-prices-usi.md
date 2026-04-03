---
# CSL-compatible fields
title: "Quantifying Inter-Annual Seasonal Drift in Tomato Prices Using Dynamic Time Warping: Evidence from Kolar Market"
author:
  - literal: "Manojkumar Patil"
  - literal: "Lalith Achoth"
  - literal: "K. B. Vedamurthy"
  - literal: "K. B. Umesh"
  - literal: "Siddayya"
  - literal: "M. N. Thimme Gowda"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.01792"

# Custom fields
paper_id: "2604.01792"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "seasonality"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:19:48Z"
created_at: "2026-04-03T05:19:48Z"
---

# Quantifying Inter-Annual Seasonal Drift in Tomato Prices Using Dynamic Time Warping: Evidence from Kolar Market

**Authors**: Manojkumar Patil, Lalith Achoth, K. B. Vedamurthy, K. B. Umesh, Siddayya, M. N. Thimme Gowda
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.01792](https://arxiv.org/abs/2604.01792)

## Summary

This study investigates the inter-annual variability of tomato price dynamics in the Kolar market using data from 2010 to 2024. By applying descriptive statistics alongside Dynamic Time Warping (DTW), the authors quantify the inconsistency of seasonal patterns over time. The results highlight that while recurring cycles exist, significant temporal shifts occur, necessitating adaptive forecasting models that account for both magnitude volatility and structural temporal drift.

## Key Contributions

- Quantified inter-annual variability of tomato prices and market arrivals in the Kolar market from 2010 to 2024.
- Applied Dynamic Time Warping (DTW) to measure temporal alignment and structural shifts in seasonal agricultural price patterns.
- Demonstrated that inter-annual seasonal drift renders fixed seasonal models insufficient for highly volatile commodity markets.

## Open Questions & Future Work

- [[dtw-based-forecasting-integration]]

## Archivist Review

The paper provides a niche application of DTW to quantify inter-annual seasonal drift. I rejected the concept candidate as it was not present in the input. I approved one open question regarding the integration of DTW into deep learning architectures, as this addresses a broader methodological gap in time-series forecasting under volatile regimes. I renamed the question to be more standard.

### Approved Open Questions
- DTW in Forecasting Architectures: Integrating DTW into deep learning pipelines could bridge the gap between statistical pattern analysis and predictive modeling, potentially enhancing robustness during regimes of high market volatility.

### Rejected Candidates
- [open_question] Integrating DTW into Deep Learning Forecasting (`dtw-integration-deep-learning-forecasting`) - other: Renamed to a more standard and concise slug for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.01792)
- [PDF](https://arxiv.org/pdf/2604.01792)

