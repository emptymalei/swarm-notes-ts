---
created_at: '2026-04-22T05:03:26Z'
source_papers:
- '[[arxiv-260419580-probabilistic-forecasting-for-day-ahead-electricity-prices-b]]'
title: Economic and Statistical Forecast Evaluation
---

**Background:** Battery optimization strategies are frequently employed to evaluate the economic value of probabilistic electricity price forecasts. However, these strategies often compress distributional information, potentially leading to low discriminatory power and misaligned incentives compared to strictly proper scoring rules.

**Question / Future Work:** The relationship between the statistical quality of probabilistic forecasts and the quality of resulting economic decisions remains unresolved. It is unclear how to design evaluation metrics that are both aligned with decision-making processes (such as battery arbitrage) and retain the mathematical properties required for fair model selection and discrimination, especially when the decision-making context or asset portfolio changes.

**Why It Matters:** This is critical because application-based evaluation is currently used as a benchmark, yet the paper demonstrates that these benchmarks can be gamed, do not necessarily incentivize honest forecasting, and lack sufficient discriminatory power to reliably distinguish between competing models.

**Evidence:** How can we infer the quality of forecasts based on the quality of the decisions? How can we assess the quality of decisions under competing models of uncertainty? Can battery trading strategies provide meaningful discrimination between forecasts of different quality? Are battery trading strategies aligned with the concept of proper scoring rules? How are statistical scores related to the economic performance? These questions will guide us throughout this paper.