---
# CSL-compatible fields
title: "MIRANDA: MId-feature RANk-adversarial Domain Adaptation toward climate change-robust ecological forecasting with deep learning"
author:
  - literal: "Yuchang Jiang"
  - literal: "Jan Dirk Wegner"
  - literal: "Vivien Sainte Fare Garnot"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.00800"

# Custom fields
paper_id: "2604.00800"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "irregular-time-step-forecasting"
  - "causal-insight"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mid-feature-rank-adversarial-da"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-02T05:37:50Z"
created_at: "2026-04-02T05:37:50Z"
---

# MIRANDA: MId-feature RANk-adversarial Domain Adaptation toward climate change-robust ecological forecasting with deep learning

**Authors**: Yuchang Jiang, Jan Dirk Wegner, Vivien Sainte Fare Garnot
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.00800](https://arxiv.org/abs/2604.00800)

## Summary

MIRANDA addresses the limitations of deep learning models in predicting plant phenology under the non-stationary conditions of climate change. Unlike standard domain adaptation methods that typically focus on output representations, MIRANDA applies adversarial regularization to intermediate features and utilizes a rank-based objective to enforce year-invariance. This approach effectively handles the temporal continuum of domains and the concurrent covariate and label shifts, leading to more robust ecological forecasting. Validation on a 70-year country-scale dataset confirms that MIRANDA outperforms traditional DA techniques and approaches the performance of established mechanistic models.

## Key Contributions

- Introduces MIRANDA, a domain adaptation framework that enforces year-invariance in meteorological representations to mitigate climate-induced distribution shifts.
- Demonstrates that adversarial regularization on intermediate features effectively addresses label and covariate shifts in temporal forecasting tasks.
- Achieves improved robust phenological prediction across a 70-year dataset, significantly reducing the performance gap between deep learning and mechanistic models.

## Open Questions & Future Work

- [[climate-robust-phenology-forecasting-bottlenecks]]

## Key Concepts

- [[mid-feature-rank-adversarial-da]]: A domain adaptation framework for climate-resilient forecasting that applies adversarial regularization to intermediate features using a rank-based objective to enforce year-invariance.

## Archivist Review

I approved the core architectural contribution, Mid-feature Rank-adversarial Domain Adaptation, as a novel approach to domain adaptation in continuous temporal settings. I also approved the open question regarding the specific bottleneck of climate-induced distribution shifts in ecological forecasting. Other candidates were deemed either overly specific or covered by existing categories.

### Approved Concepts
- Mid-feature Rank-adversarial Domain Adaptation: The methodology addresses the specific challenges of domain adaptation under climate change, specifically the temporal continuum of domains and label shift, which standard DA methods fail to handle.

### Approved Open Questions
- Robustness in Climate-Phenology Forecasting: Climate change induces non-stationary, multi-faceted shifts in ecological data that conventional machine learning benchmarks rarely capture, making this a critical frontier for robust predictive modeling.

## Links

- [Abstract](https://arxiv.org/abs/2604.00800)
- [PDF](https://arxiv.org/pdf/2604.00800)

