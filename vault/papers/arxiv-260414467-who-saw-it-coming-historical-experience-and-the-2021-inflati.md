---
# CSL-compatible fields
title: "Who Saw It Coming? Historical Experience and the 2021 Inflation Forecast Failure"
author:
  - literal: "Dalibor Stevanovic"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.14467"

# Custom fields
paper_id: "2604.14467"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "experiential-priors"
  - "similarity-weighted-estimation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:06:12Z"
created_at: "2026-04-17T05:06:12Z"
---

# Who Saw It Coming? Historical Experience and the 2021 Inflation Forecast Failure

**Authors**: Dalibor Stevanovic
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.14467](https://arxiv.org/abs/2604.14467)

## Summary

This paper investigates the 2021 U.S. inflation forecast failure, identifying sample bias—specifically the over-reliance on Great Moderation-era data—as the primary cause for the inability of models and agents to anticipate supply-shock regimes. The author shows that integrating historical data from the 1970s via intercept corrections, similarity re-estimation, or kernel-weighted estimators significantly improves forecast performance across multiple price indices. Furthermore, the study links inflation expectation heterogeneity to experience-based learning, validated through both survey analysis of household age cohorts and a controlled experiment with persona-conditioned large language models. The findings suggest that the source and historical relevance of priors are more critical to forecast robustness than model architecture sophistication.

## Key Contributions

- Demonstrates that the 2021 inflation forecast failure stemmed from estimation sample bias favoring the Great Moderation rather than functional model misspecification.
- Introduces three historically informed estimators—intercept correction, 1970s similarity-weighted estimation, and kernel-weighted estimation—that mitigate inflation forecast errors across eight U.S. price indices.
- Provides empirical evidence that inflation expectations are shaped by experiential priors, where cohort age and historical exposure significantly dictate forecast accuracy and regime-shift recognition.

## Open Questions & Future Work

- [[systematic-historical-analogy-selection]]

## Key Concepts

- [[experiential-priors]]: A form of inductive bias where model or agent forecasts are conditioned on the historical temporal experiences present in their training data or lifecycle history.
- [[similarity-weighted-estimation]]: A forecasting adjustment technique that prioritizes historical data points or segments that share structural similarity with the current target period.

## Archivist Review

I approved 'Experiential Priors' and 'Similarity-Weighted Estimation' as they provide a theoretical framework and a practical mechanism, respectively, to address non-stationarity in time-series forecasting. 'Systematic Historical Analogy Selection' was approved as a critical open question because it addresses the subjective reliance on manual windowing for historical data, which is a major hurdle in robust forecasting during regime shifts. I maintained strict adherence to the review policy, rejecting generic concepts and ensuring only the most central and reusable ideas were elevated to permanent status.

### Approved Concepts
- Experiential Priors: Highlights a fundamental driver of forecast performance that transcends model architecture, providing a framework to analyze how training data history impacts regime-shift recognition.
- Similarity-Weighted Estimation: It provides a concrete, reusable mechanism to address non-stationarity by explicitly prioritizing historical samples that share topological or structural features with the current regime.

### Approved Open Questions
- Systematic Historical Analogy Selection: It addresses the fundamental subjectivity of choosing historical training samples, which is critical for the reliability of forecasting models during transition periods.

## Links

- [Abstract](https://arxiv.org/abs/2604.14467)
- [PDF](https://arxiv.org/pdf/2604.14467)

