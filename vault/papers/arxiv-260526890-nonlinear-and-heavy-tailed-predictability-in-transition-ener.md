---
# CSL-compatible fields
title: "Nonlinear and Heavy-Tailed Predictability in Transition-Energy Financial Markets"
author:
  - literal: "Kpante Emmanuel Gnandi"
  - literal: "Fredy Pokou"
  - literal: "Jules Sadefo Kamdem"
issued:
  date-parts:
    - [2026, 5, 26]
url: "https://arxiv.org/abs/2605.26890"

# Custom fields
paper_id: "2605.26890"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "financial-time-series"
  - "hybrid-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "student-t-var-recurrent-residual-learning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-27T05:35:52Z"
created_at: "2026-05-27T05:35:52Z"
---

# Nonlinear and Heavy-Tailed Predictability in Transition-Energy Financial Markets

**Authors**: Kpante Emmanuel Gnandi, Fredy Pokou, Jules Sadefo Kamdem
**Date**: 2026-05-26
**Paper ID**: [arxiv:2605.26890](https://arxiv.org/abs/2605.26890)

## Summary

This paper addresses the inadequacy of traditional Gaussian-linear models in capturing the complex, heavy-tailed dynamics of transition-related financial markets. The authors introduce a hybrid forecasting framework that integrates Student-t Vector Autoregression for linear filtering with recurrent residual learning to capture remaining non-linear dependencies. Empirical evaluations across six major energy-sector ETFs demonstrate that this approach significantly outperforms conventional statistical and machine-learning baselines, especially during market stress episodes. The findings underscore the importance of accounting for non-linear, regime-sensitive predictive dynamics in energy-transition financial asset management.

## Key Contributions

- Proposes a hybrid forecasting framework combining Student-t Vector Autoregressions with recurrent residual learning to model nonlinear and heavy-tailed financial dependencies.
- Demonstrates superior predictive accuracy in transition-energy asset markets compared to standalone VAR, machine learning, and alternative hybrid baselines.
- Provides empirical evidence that the hybrid framework's forecasting gains are particularly robust during periods of high macro-financial stress, such as the COVID-19 and Ukraine energy crises.

## Key Concepts

- [[student-t-var-recurrent-residual-learning]]: A hybrid forecasting architecture that integrates Student-t Vector Autoregressions with recurrent neural networks to model non-linear, heavy-tailed financial returns.

## Archivist Review

The paper introduces a hybrid architecture that combines statistical heavy-tailed modeling (Student-t VAR) with deep learning for residual dependencies, addressing a common shortcoming in financial forecasting. I have approved this concept because it offers a structured approach to blending parametric financial econometrics with neural network-based non-linear learning, which is highly relevant to my forecasting skill context. No datasets or open questions met the high bar for inclusion as standalone artifacts.

### Approved Concepts
- Student-t Vector Autoregression with Recurrent Residual Learning: This hybrid approach addresses the limitations of standard Gaussian linear models in financial markets by capturing both heavy-tailed distributions and nonlinear residual dynamics.

### Rejected Candidates
- [concept] Student-t Vector Autoregression with Recurrent Residual Learning (`student-t-var-recurrent-residual-learning`) - other: This is the primary contribution, so it is approved.

## Links

- [Abstract](https://arxiv.org/abs/2605.26890)
- [PDF](https://arxiv.org/pdf/2605.26890)

