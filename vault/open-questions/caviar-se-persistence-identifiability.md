---
created_at: '2026-03-29T20:16:17Z'
source_papers:
- '[[openalex-2603.25217-modeling-and-forecasting-tail-risk-spillovers-a-component-ba]]'
title: CAViaR-SE persistence identifiability
---

**Background:** Conditional Autoregressive Value at Risk (CAViaR) models capture the time-varying dynamics of the Value at Risk (VaR) quantile for a single asset.

**Question / Future Work:** Determine the optimal persistence conditions for the proper-risk component ($\\beta_1$) and the spillover component ($\\varphi_1$) in the component-based CAViaR framework to ensure that the long-run dynamics persist more than the short-run/spillover dynamics ($\\beta_1 > \\varphi_1$) across various asset classes and market conditions, which is a key identifiability requirement for the model structure.

**Why It Matters:** The specified parameter relationship ($\\beta_1 > \\varphi_1$) is necessary for the formal identifiability and economic interpretation of the component-based model, separating persistent proper risk from temporary spillover risk.

**Evidence:** In this framework, the model is identified if the long-run component persists more than the short-run component: given the temporary nature of risk spillover, this translates into $\\beta_{1} > \\varphi_{1}$.