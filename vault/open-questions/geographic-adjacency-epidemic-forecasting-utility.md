---
created_at: '2026-05-09T05:10:02Z'
source_papers:
- '[[arxiv-260506530-spatialepibench-benchmarking-spatial-information-and-epidemi]]'
title: Utility of Geographic Adjacency
---

**Background:** Epidemic forecasting models frequently utilize geographic adjacency matrices as a primary input to capture spatial dependencies between regions. However, empirical benchmarks suggest that these adjacency-informed models often fail to outperform simple univariate baselines in practical forecasting settings.

**Question / Future Work:** It remains an unresolved question whether geographic adjacency is an appropriate proxy for the complex, time-varying inter-regional interactions that drive infectious disease spread, or if alternative network representations (e.g., mobility-based or data-driven graphs) are required for effective spatiotemporal epidemic forecasting. Further research is needed to determine how to better model or learn the spatial structure relevant to epidemiology.

**Why It Matters:** Understanding the utility of spatial priors is fundamental to the design of spatiotemporal models in public health, as the current reliance on geographic adjacency may be a limiting factor in predictive accuracy.

**Evidence:** Consistent with statistical epidemiology findings, we conclude that geographic adjacency may be a poor proxy for cross-region dependencies and can hinder performance.