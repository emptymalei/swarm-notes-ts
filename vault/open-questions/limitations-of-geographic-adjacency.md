---
created_at: '2026-05-10T05:18:12Z'
source_papers:
- '[[arxiv-260506530-spatialepibench-benchmarking-spatial-information-and-epidemi]]'
title: Efficacy of geographic adjacency
---

**Background:** Epidemic forecasting typically utilizes geographic adjacency matrices as a primary input for spatiotemporal models under the assumption that epidemiological interactions occur primarily between neighboring regions.

**Question / Future Work:** Empirical evidence suggests that geographic adjacency is a poor proxy for cross-region epidemiological dependencies. Further research is required to determine whether alternative network structures (e.g., mobility, contact, or functional networks) or learnable dynamic spatial representations can more effectively capture the interactions that drive disease spread.

**Why It Matters:** Identifying the correct structural priors is a fundamental bottleneck in spatiotemporal epidemic forecasting, as current reliance on geographic adjacency fails to yield performance gains over univariate models.

**Evidence:** Few adjacency-informed methods match univariate baselines, and most underperform, questioning the common use of geographic proximity for epidemic forecasting. [...] Consistent with statistical epidemiology findings, we conclude that geographic adjacency may be a poor proxy for cross-region dependencies and can hinder performance.