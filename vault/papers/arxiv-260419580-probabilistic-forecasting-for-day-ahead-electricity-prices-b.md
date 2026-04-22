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
domain: "time-series"
tags:
  - "probabilistic-electricity-price-forecasting-pepf"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quantile-based-trading-strategies-qbts"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:03:26Z"
created_at: "2026-04-22T05:03:26Z"
---

# Probabilistic Forecasting for Day-ahead Electricity Prices, Battery Trading Strategies and the Economic Evaluation of Predictive Accuracy

**Authors**: Simon Hirsch, Florian Ziel
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19580](https://arxiv.org/abs/2604.19580)

## Summary

This paper examines the connection between probabilistic electricity price forecasting accuracy and the economic performance of battery storage arbitrage strategies. The authors demonstrate that traditional quantile-based trading strategies are flawed because they ignore intertemporal price dependencies and do not ensure honest uncertainty quantification. To address this, they propose a stochastic programming framework based on full predictive distributions, providing both theoretical insights and empirical evidence from the German day-ahead electricity market. The results challenge the reliance on simplified application-based benchmarks for evaluating the quality of predictive models in energy markets.

## Key Contributions

- Identifies that standard quantile-based trading strategies for battery storage fail to incentivize honest probabilistic forecasting and ignore intertemporal price dependencies.
- Formulates battery storage arbitrage as a stochastic programming problem that utilizes full predictive distributions rather than simple quantiles.
- Demonstrates that ranking forecasting models via application-based benchmarks (like battery arbitrage) is prone to pitfalls, necessitating more rigorous evaluation practices in economic decision-making contexts.

## Open Questions & Future Work

- [[economic-evaluation-vs-statistical-scoring]]

## Key Concepts

- [[quantile-based-trading-strategies-qbts]]: A common approach to battery arbitrage that uses price quantiles for decision-making, which the paper identifies as failing to incentivize honest forecasting or account for intertemporal price dependencies.

## Archivist Review

I approved the concept of Quantile-based Trading Strategies (QBTS) because the paper explicitly defines and critiques this industry-standard practice, establishing a framework for future discussion on why decision-making benchmarks can fail. I also approved the open question regarding the misalignment between economic and statistical evaluation, as this is a high-level, persistent challenge in energy market forecasting that the paper effectively characterizes as an unresolved tension. Other candidates were not proposed, and I adhered to the scarcity constraints and the rigorous standards for identifying reusable methodological critiques.

### Approved Concepts
- Quantile-based Trading Strategies (QBTS): This concept identifies a widely used but flawed approach to evaluating probabilistic forecasts in energy storage applications, serving as the primary object of critique for better decision-theoretic evaluation methods.

### Approved Open Questions
- Economic and Statistical Forecast Evaluation: This is critical because application-based evaluation is currently used as a benchmark, yet the paper demonstrates that these benchmarks can be gamed, do not necessarily incentivize honest forecasting, and lack sufficient discriminatory power to reliably distinguish between competing models.

## Links

- [Abstract](https://arxiv.org/abs/2604.19580)
- [PDF](https://arxiv.org/pdf/2604.19580)

