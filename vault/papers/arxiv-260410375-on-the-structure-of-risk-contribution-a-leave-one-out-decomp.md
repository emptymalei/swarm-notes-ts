---
# CSL-compatible fields
title: "On the Structure of Risk Contribution: A Leave-One-Out Decomposition into Inherent and Correlation Risk"
author:
  - literal: "Nolan Alexander"
  - literal: "Frank Fabozzi"
issued:
  date-parts:
    - [2026, 4, 11]
url: "https://arxiv.org/abs/2604.10375"

# Custom fields
paper_id: "2604.10375"
paper_source: "arxiv"
domain: "finance"
tags:
  - "time-series-analysis"
  - "risk-management"
  - "portfolio-optimization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "inherent-correlation-decomposition-icd"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:06:25Z"
created_at: "2026-04-14T05:06:25Z"
---

# On the Structure of Risk Contribution: A Leave-One-Out Decomposition into Inherent and Correlation Risk

**Authors**: Nolan Alexander, Frank Fabozzi
**Date**: 2026-04-11
**Paper ID**: [arxiv:2604.10375](https://arxiv.org/abs/2604.10375)

## Summary

This paper introduces a novel decomposition of standard Risk Contribution (RC) into two distinct, economically interpretable terms: inherent risk and correlation risk. By utilizing a leave-one-out representation, the method separates an asset's risk contribution into its independent volatility contribution and its covariance-driven influence relative to the portfolio. This decomposition preserves the strict additivity of traditional RC while providing deeper diagnostic insight into how specific holdings affect total portfolio risk. The approach is further extended to time-series analysis, offering a robust tool for monitoring risk dynamics during varying market regimes.

## Key Contributions

- Introduces a leave-one-out decomposition of Risk Contribution (RC) into additive inherent (volatility-driven) and correlation-driven components.
- Provides an analytical framework that preserves strict additivity of standard risk contribution while increasing diagnostic interpretability.
- Demonstrates a methodology for tracking inherent and correlation risk evolution across market regimes to differentiate between volatility shocks and correlation shifts.

## Open Questions & Future Work

- [[dynamic-icd-extension-scalability]]

## Key Concepts

- [[inherent-correlation-decomposition-icd]]: A leave-one-out decomposition of portfolio Risk Contribution into additive volatility-based inherent risk and covariance-based correlation risk.

## Archivist Review

I approved the 'Inherent and Correlation Decomposition' as a core methodological contribution to financial risk attribution. I also approved a refined open question regarding its extension to dynamic and high-dimensional settings, which represents a clear technical hurdle for real-world adoption. I rejected nothing as no other candidates were proposed.

### Approved Concepts
- Inherent and Correlation Decomposition (ICD): It provides a novel, strictly additive way to disentangle portfolio volatility into isolated volatility and interaction-driven effects, which is a fundamental requirement for interpretable risk attribution.

### Approved Open Questions
- Dynamic ICD Extension Scaling: Ensuring that decomposed risk metrics remain valid and interpretable under adaptive strategies is a significant bottleneck for real-world deployment of automated portfolio management systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.10375)
- [PDF](https://arxiv.org/pdf/2604.10375)

