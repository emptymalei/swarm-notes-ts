---
created_at: '2026-04-16T05:06:03Z'
source_papers:
- '[[arxiv-260413924-aster-latent-pseudo-anomaly-generation-for-unsupervised-time]]'
title: Pseudo-anomaly diversity and coverage
---

**Background:** Unsupervised time-series anomaly detection frequently uses synthetic pseudo-anomalies to guide model training in the absence of labels. The quality and representative coverage of these generated anomalies directly impact the learned decision boundaries.

**Question / Future Work:** There is an unresolved challenge in ensuring the diversity and realistic structure of latent-space pseudo-anomalies, as overly simple generators may result in classifiers that fail to generalize to novel or complex real-world anomalies. Investigating how to expand the latent space coverage via advanced sampling or structural constraints remains a critical research direction.

**Why It Matters:** High-quality, diverse anomaly synthesis is the primary bottleneck for the performance of self-supervised and unsupervised anomaly detection frameworks.