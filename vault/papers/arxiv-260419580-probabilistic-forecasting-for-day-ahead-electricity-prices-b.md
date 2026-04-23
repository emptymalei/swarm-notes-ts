---
# CSL-compatible fields
title: "Probabilistic Forecasting for Day-ahead Electricity Prices, Battery Trading Strategies and the Economic Evaluation of Predictive Accuracy"
author:
  - literal: "Simon Hirsch"
  - literal: "Florian Ziel"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19580"

# Custom fields
paper_id: "2604.19580"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "quantile-based-trading-strategies-qbts"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:09:32Z"
created_at: "2026-04-23T05:09:32Z"
---

# Probabilistic Forecasting for Day-ahead Electricity Prices, Battery Trading Strategies and the Economic Evaluation of Predictive Accuracy

**Authors**: Simon Hirsch, Florian Ziel
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19580](https://arxiv.org/abs/2604.19580)

## Summary

This paper examines the link between probabilistic electricity price forecasting and the economic performance of battery storage arbitrage. The authors identify systemic flaws in traditional quantile-based trading strategies (QBTS), specifically their failure to incentivize honest forecasting and their neglect of price dependencies. By modeling battery optimization as a stochastic program, they illustrate that improvements in statistical accuracy do not automatically translate to economic gains, highlighting the risks of relying on application-based metrics for model selection. The findings offer a critical perspective on standard evaluation practices in energy market forecasting.

## Key Contributions

- Identifies and theoretically demonstrates two critical flaws in quantile-based trading strategies (QBTS): lack of incentivized honesty in probabilistic forecasting and failure to account for intertemporal price dependencies.
- Proposes a stochastic programming framework for battery arbitrage that utilizes full probabilistic forecasts instead of simple quantiles to improve decision-making performance.
- Demonstrates through a German electricity market case study that battery trading strategies can be misleading metrics for ranking the quality of forecasting models.

## Open Questions & Future Work

- [[reconciling-statistical-and-economic-forecast-evaluation]]

## Key Concepts

- [[quantile-based-trading-strategies-qbts]]: A common operational decision-making strategy for energy storage that uses quantile forecasts, criticized for failing to incentivize honest forecasting and ignoring temporal dependencies.

## Archivist Review

I approved one concept and one open question. I focused on the paper's critique of quantile-based trading strategies and the broader, significant disconnect between statistical evaluation and economic performance. Other candidates were rejected as being either redundant or too broad/generic.

### Approved Concepts
- Quantile-based trading strategies (QBTS): The paper provides a formal critique of these strategies, explaining why common practice in energy storage evaluation is theoretically flawed and decoupled from true statistical performance.

### Approved Open Questions
- Reconciling Statistical and Economic Evaluation: This is a fundamental barrier to establishing reliable, end-to-end forecasting workflows where the objective is to maximize utility rather than purely minimizing loss.

### Rejected Candidates
- [open_question] Uncertainty Model Impact on Optimization (`uncertainty-model-impact-on-stochastic-optimization-quality`) - generic: This is a broad, generic research question regarding the well-known field of scenario-based optimization and sensitivity analysis.

## Links

- [Abstract](https://arxiv.org/abs/2604.19580)
- [PDF](https://arxiv.org/pdf/2604.19580)

