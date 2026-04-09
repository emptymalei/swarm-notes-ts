---
created_at: '2026-04-09T04:55:25Z'
source_papers:
- '[[arxiv-260406727-bi-level-heterogeneous-learning-for-time-series-foundation-m]]'
title: Bi-level Heterogeneity in TSFMs
---

**Background:** Time series foundation models are typically trained via centralized aggregation of heterogeneous datasets, which often leads to gradient conflicts and poor representation quality due to domain-specific discrepancies. Although federated learning offers a decentralized alternative to mitigate these issues, existing methods for time series primarily focus on inter-domain heterogeneity and often fail to account for complex intra-domain conflicts, such as temporal concept drift or latent sub-domain variability.

**Question / Future Work:** The development of a unified federated learning paradigm that simultaneously resolves both inter-domain and intra-domain (bi-level) heterogeneity remains an open challenge. Future research is needed to refine methods for integrating knowledge across diverse, contextually divergent temporal sources without compromising the stability of the learned representations or the efficacy of cross-domain collaboration.

**Why It Matters:** Addressing bi-level heterogeneity is critical for the scalability and robustness of TSFMs, as temporal data is inherently fragmented and variable across real-world organizations, rendering simple centralized pooling methods suboptimal.