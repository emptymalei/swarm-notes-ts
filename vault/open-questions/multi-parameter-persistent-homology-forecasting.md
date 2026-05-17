---
created_at: '2026-05-17T05:22:46Z'
source_papers:
- '[[arxiv-260515035-topoprimer-the-missing-topological-context-in-forecasting-mo]]'
title: Multi-Parameter Topological Forecasting Extensions
---

**Background:** Time series forecasting models often neglect the explicit global topological structure of the series population, which can lead to performance gaps in cold-start scenarios or during distribution shifts.

**Question / Future Work:** Investigating the integration of multi-parameter persistent homology, which filters along multiple axes like scale and volatility simultaneously, could capture complex geometric relational dynamics that are missed by current single-parameter summary metrics.

**Why It Matters:** Identifying better ways to capture higher-order topological relational dynamics is crucial for improving forecasting robustness in complex, non-stationary data regimes.

**Evidence:** The topological features themselves admit two natural extensions: (i) a learned filtration metric that recovers topological structure obscured by Pearson distance; and (ii) multi-parameter persistent homology filtrating along scale and demand volatility jointly, to capture geometry that single-parameter summaries miss.