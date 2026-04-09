---
# CSL-compatible fields
title: "Conformal Prediction with Time-Series Data via Sequential Conformalized Density Regions"
author:
  - literal: "M. Sampson"
  - literal: "K. S. Chan"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07325"

# Custom fields
paper_id: "2604.07325"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "conformal-prediction"
  - "time-series-forecasting"
  - "uncertainty-quantification"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sequential-conformalized-density-regions-scdr"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:52:35Z"
created_at: "2026-04-09T04:52:35Z"
---

# Conformal Prediction with Time-Series Data via Sequential Conformalized Density Regions

**Authors**: M. Sampson, K. S. Chan
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07325](https://arxiv.org/abs/2604.07325)

## Summary

This paper introduces Sequential Conformalized Density Regions (SCDR), a novel framework for conformal prediction in time-series data that guarantees asymptotic conditional coverage. Unlike standard interval-based approaches, SCDR utilizes quantile random forests to adaptively adjust predictive regions, allowing for disconnected sets that effectively capture complex, multi-modal dynamics such as bifurcations. The method demonstrates double robustness, providing valid coverage even when the base density model or the autoregressive score structure is partially mis-specified. Experimental evaluations confirm that SCDR provides tighter, more informative prediction sets on real-world datasets compared to existing benchmarks.

## Key Contributions

- Introduces Sequential Conformalized Density Regions (SCDR), a method capable of producing disconnected prediction sets to capture bifurcations in time-series data.
- Provides theoretical proof that SCDR achieves asymptotic conditional coverage under regularity conditions.
- Demonstrates double robustness properties, ensuring coverage even if either the predictive density model is mis-specified or the score model structure is mis-specified.
- Empirical results show improved coverage and set size efficiency compared to standard time-series conformal prediction methods.

## Open Questions & Future Work

- [[joint-multi-step-conformal-prediction]]

## Key Concepts

- [[sequential-conformalized-density-regions-scdr]]: A conformal prediction method for time-series that produces flexible, potentially disconnected prediction sets with asymptotic conditional coverage guarantees.

## Archivist Review

The concept of Sequential Conformalized Density Regions (SCDR) is approved as it offers a novel approach to conformal prediction for time-series by allowing for disconnected sets, which is a reusable mechanism for handling multimodal dynamics. The open question regarding joint multi-step conformal prediction is approved as it addresses a significant technical bottleneck in extending conformal methods beyond one-step-ahead uncertainty. The datasets were rejected as they are standard, general-purpose data, not specialized or unique research assets.

### Approved Concepts
- Sequential Conformalized Density Regions: The paper introduces SCDR as a novel method for producing conformal prediction intervals/sets for non-exchangeable time-series data while guaranteeing asymptotic conditional coverage.

### Approved Open Questions
- Joint Multi-Step Conformal Prediction: Moving from one-step to multi-step joint prediction is essential for tasks requiring path-wise uncertainty quantification, which is necessary for many sequential decision-making processes.

### Rejected Candidates
- [dataset] Old Faithful geyser dataset (`old-faithful-geyser-dataset`) - not_novel: This is a standard statistical reference dataset rather than a novel or highly specialized benchmark in the context of modern time-series forecasting.
- [dataset] Australian electricity usage dataset (`australian-electricity-usage-dataset`) - not_novel: This is a widely used, general-purpose dataset for electricity forecasting and does not constitute a specialized or critical research benchmark requiring a dedicated entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.07325)
- [PDF](https://arxiv.org/pdf/2604.07325)

