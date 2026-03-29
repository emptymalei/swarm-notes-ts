---
created_at: '2026-03-29T20:16:45Z'
source_papers:
- '[[openalex-2603.25046-mp-moe-matrix-profile-guided-mixture-of-experts-for-precipit]]'
title: Extension to spatiotemporal domain
---

**Background:** Current implementations of the Matrix Profile-Guided Mixture of Experts (MP-MoE) framework focus on 1D time-series analysis at the basin level, neglecting spatial dependencies between neighboring meteorological regions.

**Question / Future Work:** Future work involves extending the current 1D time-series framework to the spatiotemporal domain by incorporating graph-based dependencies. This extension is necessary to ensure that forecasts maintain regional consistency across adjacent catchment areas, which is important for capturing large-scale weather phenomena.

**Why It Matters:** Extending from 1D time-series to a spatiotemporal model using graph dependencies is necessary to capture the inherently spatial nature of weather systems and ensure consistency across neighboring forecast regions.

**Evidence:** The current implementation focuses on 1D time-series modeling at the basin scale, a choice that prioritizes local structural fidelity over broader spatiotemporal field correlations. ... Future research will focus on extending the framework to the spatiotemporal domain by incorporating graph-based dependencies, ensuring regional consistency across neighboring catchments.