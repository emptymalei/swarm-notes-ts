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
domain: "time-series"
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
processed_at: "2026-05-17T05:24:39Z"
created_at: "2026-05-17T05:24:39Z"
---

# What if Tomorrow is the World Cup Final? Counterfactual Time Series Forecasting with Textual Conditions

**Authors**: Shuqi Gu, Yongxiang Zhao, Baoyu Jing, Kan Ren
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14422](https://arxiv.org/abs/2605.14422)

## Summary

This paper addresses the limitations of traditional time series forecasting by introducing the task of counterfactual time series forecasting with textual conditions. By incorporating textual information, the proposed approach allows for more flexible and condition-aware modeling of future events. The authors further introduce a text-attribution mechanism to distinguish between mutable and immutable factors, ensuring more robust predictions under stochastic scenarios. Additionally, a new evaluation framework is presented to assess performance even when ground truth data for counterfactuals is unavailable.

## Key Contributions

- Introduces the task of counterfactual time series forecasting using textual conditions to improve adaptability to stochastic future events.
- Develops an evaluation framework for both factual and counterfactual scenarios, circumventing the need for ground truth in hypothetical settings.
- Proposes a text-attribution mechanism that improves forecast accuracy by distinguishing between mutable and immutable conditioning factors.

## Open Questions & Future Work

- [[counterfactual-forecasting-evaluation-limitations]]

## Key Concepts

- [[counterfactual-time-series-forecasting]]: A time series forecasting task that predicts future states based on hypothetical, counterfactual conditions provided as textual descriptions.
- [[text-attribution-mechanism]]: A technique for isolating and partitioning input conditioning factors into mutable and immutable sets to improve predictive consistency under counterfactual shifts.

## Archivist Review

I have approved the core task and the specific attribution mechanism as they define a novel, reusable paradigm for conditional time series forecasting. I also approved the open question regarding evaluation, as it identifies a foundational, unsolved challenge inherent to the proposed task. I rejected the horizon evaluation question because it is a generic scaling issue rather than a problem unique to the counterfactual methodology proposed.

### Approved Concepts
- Counterfactual Time Series Forecasting: Defines a new paradigm for time series forecasting that moves beyond historical data extrapolation into conditional hypothetical scenarios.
- Text Attribution Mechanism: Provides a systematic approach to decomposing conditioning information into changeable and fixed components, essential for causal and counterfactual modeling.

### Approved Open Questions
- Counterfactual Forecasting Evaluation Challenges: Without evaluation protocols for counterfactual outcomes, it is impossible to validate model performance in hypothetical decision-support scenarios.

### Rejected Candidates
- [open_question] Evaluating Long-Horizon Forecasting Consistency (`forecasting-horizon-evaluation-robustness`) - generic: The candidate describes a generic challenge of temporal scaling rather than a distinct, specific bottleneck unique to the paper's counterfactual methodology.

## Links

- [Abstract](https://arxiv.org/abs/2605.14422)
- [PDF](https://arxiv.org/pdf/2605.14422)

