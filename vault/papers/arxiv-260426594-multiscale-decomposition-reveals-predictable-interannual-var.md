---
# CSL-compatible fields
title: "Multiscale Decomposition Reveals Predictable Interannual Variability and Climate Trends in Antarctic Sea Ice Loss"
author:
  - literal: "Peter Yatsyshin"
  - literal: "Karl Lapo"
  - literal: "Oliver Strickson"
  - literal: "Louisa van Zeeland"
  - literal: "J. Scott Hosking"
  - literal: "J. Nathan Kutz"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26594"

# Custom fields
paper_id: "2604.26594"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "climate-modeling"
  - "spatiotemporal-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "regularized-predictive-dmd"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:13:39Z"
created_at: "2026-04-30T05:13:39Z"
---

# Multiscale Decomposition Reveals Predictable Interannual Variability and Climate Trends in Antarctic Sea Ice Loss

**Authors**: Peter Yatsyshin, Karl Lapo, Oliver Strickson, Louisa van Zeeland, J. Scott Hosking, J. Nathan Kutz
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26594](https://arxiv.org/abs/2604.26594)

## Summary

This paper investigates the interannual variability and climate trends of Antarctic sea ice concentration (SIC) using a hierarchical Dynamic Mode Decomposition (DMD) framework. The authors reveal that observed historical fluctuations are driven by the interaction of multiscale modes, with a clear climate change signal emerging by 2022. They introduce IceDMD, a regularized predictive model that leverages these stationary spatiotemporal modes to forecast SIC anomalies up to two years ahead with high computational efficiency and physical transparency.

## Key Contributions

- Identified that Antarctic sea ice decline and recovery cycles result from the interaction of interannual modes, with a dominant climate change signal emerging by 2022.
- Introduced IceDMD, a regularized predictive Dynamic Mode Decomposition framework that achieves state-of-the-art two-year sea ice concentration (SIC) anomaly forecasts.
- Demonstrated that IceDMD offers superior computational efficiency and physical interpretability compared to traditional forecasting approaches for multiscale geophysical systems.

## Open Questions & Future Work

- [[uncertainty-quantification-for-dmd-models]]

## Key Concepts

- [[regularized-predictive-dmd]]: A predictive framework that regularizes Dynamic Mode Decomposition by prioritizing stationary spatiotemporal modes for improved multiscale forecasting.

## Archivist Review

I approved the regularized predictive DMD framework as it provides a reusable methodological approach for multiscale forecasting, moving beyond the specific model implementation. I also approved the open question regarding uncertainty quantification for DMD, as this is a well-recognized bottleneck for transition-aware data-driven forecasting models. Other candidates were rejected for being domain-specific or subcomponents.

### Approved Concepts
- Regularized Predictive Dynamic Mode Decomposition: The core contribution is a regularization framework for DMD that forces the model to prioritize stationary modes, improving forecasting performance and physical interpretability in multiscale systems.

### Approved Open Questions
- Robust uncertainty quantification development: Reliable uncertainty quantification is essential for operational climate forecasting where risk management and decision-making are paramount.

### Rejected Candidates
- [concept] IceDMD (`icedmd`) - subcomponent_of_broader_mechanism: The model name itself is a specific implementation, while the underlying regularization technique is the broader, reusable scientific contribution.
- [open_question] Refining secular trend quantification (`refining-secular-trend-quantification-sea-ice`) - low_impact: This question is too specific to the Antarctic sea ice domain rather than representing a general research bottleneck in multiscale time-series modeling.

## Links

- [Abstract](https://arxiv.org/abs/2604.26594)
- [PDF](https://arxiv.org/pdf/2604.26594)

