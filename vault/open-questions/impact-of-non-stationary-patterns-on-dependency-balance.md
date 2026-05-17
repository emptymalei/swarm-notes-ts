---
created_at: '2026-05-17T05:24:23Z'
source_papers:
- '[[arxiv-260514551-seesawnet-towards-non-stationary-time-series-forecasting-wit]]'
title: Non-stationary patterns and dependency balance
---

**Background:** Non-stationary time series often exhibit varying levels of distribution shift, where instance normalization (IN) successfully aligns global patterns but may simultaneously obscure critical, instance-specific structural information.

**Question / Future Work:** It remains to be systematically investigated how diverse non-stationary patterns—such as trend, seasonality, and irregular shifts—interact with and differentially affect the adaptive balance between common and instance-specific dependency modeling. Understanding this relationship could lead to more nuanced architectural designs that adjust their reliance on common vs. specific features based on the specific nature of the non-stationarity observed in the data.

**Why It Matters:** This is critical for developing more robust and interpretable time series forecasting models that can adaptively handle different types of distribution shifts encountered in real-world applications.

**Evidence:** Future work will study how different non-stationary patterns affect this balance.