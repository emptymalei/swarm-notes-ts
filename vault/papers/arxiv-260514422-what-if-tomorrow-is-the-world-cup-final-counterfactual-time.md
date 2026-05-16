---
# CSL-compatible fields
title: "What if Tomorrow is the World Cup Final? Counterfactual Time Series Forecasting with Textual Conditions"
author:
  - literal: "Shuqi Gu"
  - literal: "Yongxiang Zhao"
  - literal: "Baoyu Jing"
  - literal: "Kan Ren"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14422"

# Custom fields
paper_id: "2605.14422"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "counterfactual-time-series-forecasting"
  - "text-attribution-mechanism"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:12:59Z"
created_at: "2026-05-16T05:12:59Z"
---

# What if Tomorrow is the World Cup Final? Counterfactual Time Series Forecasting with Textual Conditions

**Authors**: Shuqi Gu, Yongxiang Zhao, Baoyu Jing, Kan Ren
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14422](https://arxiv.org/abs/2605.14422)

## Summary

This paper introduces the task of counterfactual time series forecasting, which enables temporal models to incorporate hypothetical textual conditions into their predictions. The authors propose a specialized evaluation framework to validate performance in counterfactual scenarios where ground truth is typically unavailable. Additionally, a novel text-attribution mechanism is introduced to selectively integrate textual signals by distinguishing between mutable and immutable contextual factors, leading to improved adaptability in stochastic environments.

## Key Contributions

- Introduces the task of counterfactual time series forecasting, allowing models to predict scenarios based on hypothetical textual events.
- Develops a comprehensive evaluation framework for time series models in both factual and counterfactual settings, overcoming the lack of ground truth in hypothetical scenarios.
- Proposes a text-attribution mechanism that improves accuracy by explicitly distinguishing between mutable and immutable textual factors affecting the forecast.

## Open Questions & Future Work

- [[evaluation-frameworks-for-counterfactual-forecasting]]

## Key Concepts

- [[counterfactual-time-series-forecasting]]: A forecasting framework that adapts temporal predictions based on hypothetical, user-specified counterfactual textual conditions.
- [[text-attribution-mechanism]]: A mechanism that separates mutable from immutable factors within textual conditions to improve forecast alignment in time series models.

## Archivist Review

The paper proposes a foundational shift in time series forecasting by enabling counterfactual analysis via textual conditioning. The concepts of Counterfactual Time Series Forecasting and the Text-Attribution Mechanism are essential, reusable components for this new paradigm. The open question regarding evaluation frameworks is critical, as it highlights the primary methodological challenge when traditional error metrics cannot be computed due to the lack of counterfactual ground truth.

### Approved Concepts
- Counterfactual Time Series Forecasting: Defines a new paradigm for time series forecasting that incorporates hypothetical, non-observed future scenarios mediated by text.
- Text-Attribution Mechanism: Enables the model to selectively attend to textual information relevant to the time series while ignoring irrelevant or immutable context.

### Approved Open Questions
- Evaluation Frameworks for Counterfactual Forecasting: Without ground truth, evaluating whether a model accurately predicts the consequences of a counterfactual intervention is difficult. Tracking progress in this area is vital for moving beyond simple accuracy metrics toward validating the causal and logical consistency of time series models.

## Links

- [Abstract](https://arxiv.org/abs/2605.14422)
- [PDF](https://arxiv.org/pdf/2605.14422)

