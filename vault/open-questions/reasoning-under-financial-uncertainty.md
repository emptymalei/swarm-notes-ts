---
created_at: '2026-05-06T05:12:23Z'
source_papers:
- '[[arxiv-260503460-finstar-towards-financial-reasoning-with-time-series-reasoni]]'
title: Reasoning Under Financial Uncertainty
---

**Background:** Financial time series forecasting is inherently stochastic, meaning that even optimal models are limited by the presence of unobservable external factors such as news sentiment or macroeconomic events.

**Question / Future Work:** Developing models that can distinguish between deterministic assessment of historical price data and stochastic prediction under uncertainty remains a key challenge, as standard chain-of-thought strategies often lead to overconfidence in probabilistic scenarios. Determining how to effectively combine price-based reasoning with exogenous signals to improve prediction accuracy in financial time series without introducing noise is an unresolved direction for time series reasoning models.

**Why It Matters:** This distinction is critical for building epistemically honest financial AI systems that avoid overconfident predictions in high-stakes environments.

**Evidence:** Prediction tasks (e.g., “Will this drawdown recover?”) have answers that depend on future events influenced by unobservable factors such as earnings surprises. Even with a perfect model, prediction accuracy cannot reach 100% because the necessary information is not contained in the price history alone.