---
# CSL-compatible fields
title: "Uncertainty Quantification in Forecast Comparisons"
author:
  - literal: "Marc-Oliver Pohle"
  - literal: "Tanja Zahn"
  - literal: "Sebastian Lerch"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03997"

# Custom fields
paper_id: "2605.03997"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "simultaneous-confidence-bands-for-forecast-evaluation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:11:11Z"
created_at: "2026-05-06T05:11:11Z"
---

# Uncertainty Quantification in Forecast Comparisons

**Authors**: Marc-Oliver Pohle, Tanja Zahn, Sebastian Lerch
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03997](https://arxiv.org/abs/2605.03997)

## Summary

Standard forecast evaluation using skill scores often ignores the multi-dimensional complexity of modern forecasting, leading to invalid joint inference. This paper introduces simultaneous confidence bands for expected and skill scores to rigorously quantify sampling uncertainty across multivariate horizons, variables, and locations. The proposed bootstrap implementation accounts for the multiple comparison problem, effectively controlling Type I error rates. The framework is applicable to various forecast types, including point, quantile, and full distributional forecasts.

## Key Contributions

- Introduces a rigorous framework using simultaneous confidence bands to quantify uncertainty in expected and skill scores.
- Proposes a bootstrap-based implementation valid under multivariate extensions of Diebold-Mariano assumptions to control Type I error rates in multi-dimensional comparisons.
- Demonstrates efficacy through applications in macroeconomic modeling and comparative evaluation of data-driven versus physics-based weather forecasting models.

## Open Questions & Future Work

- [[high-dimensional-simultaneous-bands-asymptotics]]
- [[automatic-block-length-selection]]

## Key Concepts

- [[simultaneous-confidence-bands-for-forecast-evaluation]]: A statistical framework for quantifying sampling uncertainty in skill scores across multiple dimensions, including forecast horizons, variables, and spatial locations.

## Archivist Review

The paper provides a rigorous statistical framework for forecast evaluation that addresses common pitfalls in multi-dimensional comparative inference. The proposed concepts and open questions address fundamental methodological limitations in current time-series forecast evaluation, particularly concerning high-dimensional scaling and bootstrapping procedures. The selection is limited to the most foundational contributions and unresolved problems identified in the work.

### Approved Concepts
- Simultaneous Confidence Bands for Forecast Evaluation: Addresses the lack of rigorous joint inference in multi-dimensional forecast evaluation where standard tests suffer from inflated Type I error rates.

### Approved Open Questions
- Asymptotics for Growing Dimensions: Without such a theoretical framework, uncertainty quantification in high-dimensional forecast comparisons remains heuristic and potentially invalid, limiting the reliability of model selection in large-scale applications.
- Multivariate Block Length Selection: Inappropriate block length selection can lead to inaccurate variance estimation, causing incorrect coverage of confidence bands and invalid statistical inference in forecast comparisons.

## Links

- [Abstract](https://arxiv.org/abs/2605.03997)
- [PDF](https://arxiv.org/pdf/2605.03997)

