---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Safety stock calculation with heteroscedastic, autocorrelated and heavy-tailed forecast errors, an adaptive parametric method.e"
description: "This paper proposes an adaptive parametric framework for safety stock sizing in the presence of non-Gaussian forecast errors (autocorrelated, heteroscedastic, and heavy-tailed). The method utilizes a modular architecture that selects SKU-specific distributions and applies corrections for forecast optimism and volume-dependent variance. Validated through discrete-event simulation on four years of fast-moving consumer goods (FMCG) data, the approach reduces average inventory by nearly 10% while maintaining target beta fill rates, demonstrating that modeling specific error characteristics leads to superior capital efficiency in supply chains."
resource: "https://arxiv.org/abs/2610.19829"
tags:
  - "supply-chain-optimization"
  - "forecasting"
  - "statistical-modeling"
  - "time-series-analysis"
  - "uncertainty-quantification"
  - "probabilistic-forecasting"
  - "simulation"
  - "non-stationary-signals"
timestamp: "2026-10-18T00:41:50Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Luis Fernández-Palacios"
  - literal: "Manuel Ceballos"
  - literal: "Yolanda Muñoz-Ocaña"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19829"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "adaptive-parametric-safety-stock"
    description: "A modular framework for safety stock sizing that dynamically selects SKU-specific probability distributions and scales dispersion to handle non-Gaussian forecast errors."
datasets:
  []
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:41:50Z"
created_at: "2026-10-18T00:41:50Z"
---

# Safety stock calculation with heteroscedastic, autocorrelated and heavy-tailed forecast errors, an adaptive parametric method.e

**Authors**: Luis Fernández-Palacios, Manuel Ceballos, Yolanda Muñoz-Ocaña
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19829](https://arxiv.org/abs/2610.19829)

## Summary

This paper proposes an adaptive parametric framework for safety stock sizing in the presence of non-Gaussian forecast errors (autocorrelated, heteroscedastic, and heavy-tailed). The method utilizes a modular architecture that selects SKU-specific distributions and applies corrections for forecast optimism and volume-dependent variance. Validated through discrete-event simulation on four years of fast-moving consumer goods (FMCG) data, the approach reduces average inventory by nearly 10% while maintaining target beta fill rates, demonstrating that modeling specific error characteristics leads to superior capital efficiency in supply chains.

## Key Contributions

- Developed a modular, adaptive safety-stock architecture that handles forecast errors characterized by autocorrelation, heteroscedasticity, asymmetry, and heavy tails.
- Introduced a forecast-scaled module that adjusts error dispersion when variance is non-linearly dependent on forecast volume.
- Achieved a 9.9% reduction in average inventory and a 19.5% reduction in maximum inventory without degrading beta fill rates compared to traditional methods in a real-world FMCG case study.
- Implemented a Cycle-End Exposure safeguard that dynamically adjusts safety stock to account for the increased shortage risk inherent in large replenishment lot sizes.

## Limitations

The benefit of the heteroscedasticity module is selective and depends on the intensity of the variance-volume dependence in the specific SKU's forecast history.

## Key Concepts

- [[adaptive-parametric-safety-stock]]: A modular framework for safety stock sizing that dynamically selects SKU-specific probability distributions and scales dispersion to handle non-Gaussian forecast errors.

## Archivist Review

The analysis focuses on the paper's core contribution: a modular, adaptive framework for safety stock that moves beyond Gaussian assumptions. Only the primary architecture was approved as a concept, as it represents a significant methodological shift in inventory management. The Cycle-End Exposure Safeguard was rejected as a sub-component of this broader architecture. The open question regarding structural breaks was rejected for being a generic limitation of parametric modeling rather than a specific research gap identified by the paper's unique contributions.

### Approved Concepts
- Adaptive Parametric Safety Stock: Most standard inventory management systems (ERPs) rely on simple Gaussian assumptions that fail to account for the heavy tails and autocorrelation common in real-world supply chains. This adaptive framework provides a structured way to select distributions and apply corrections based on individual SKU error profiles.

### Rejected Candidates
- [concept] Cycle-End Exposure Safeguard (`cycle-end-exposure-safeguard`) - subcomponent_of_broader_mechanism: This candidate is a paper-specific implementation detail and a sub-module of the broader adaptive framework, rather than a standalone concept likely to be widely adopted under this specific name.
- [open_question] Parametric Robustness to Structural Breaks (`structural-breaks-in-safety-stock`) - generic: The problem of stationarity and structural breaks is a fundamental, generic challenge for all parametric time-series models and does not represent a specific research bottleneck introduced or uniquely exposed by this paper's methodology.

## Links

- [Abstract](https://arxiv.org/abs/2610.19829)
- [PDF](https://arxiv.org/pdf/2610.19829)

