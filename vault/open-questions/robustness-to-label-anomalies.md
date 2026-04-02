---
created_at: '2026-04-02T05:41:03Z'
source_papers:
- '[[arxiv-2603.29362-uncertainty-aware-trajectory-prediction-a-unified-framework]]'
title: Robustness to Ground-Truth Anomalies
---

**Background:** Autonomous driving systems rely on high-definition (HD) map estimation for accurate trajectory prediction, but these maps are often contaminated by sensor noise and perceptual errors. While uncertainty-aware frameworks have been proposed to mitigate these impacts, ground-truth trajectory data may occasionally contain unexpected deviations that standard uncertainty models fail to characterize correctly.

**Question / Future Work:** Future work is needed to investigate how uncertainty-aware frameworks can remain robust when ground-truth trajectory labels contain unexpected deviations or anomalies. The existing method exhibits a failure case where a slight leftward drift in a labeled \"straight\" trajectory caused a prediction discrepancy, suggesting that uncertainty estimation mechanisms may be sensitive to inconsistencies or noise within the ground-truth data itself.

**Why It Matters:** As benchmarks for autonomous driving rely on human-labeled data, the inherent noise or inconsistencies in these labels can undermine evaluation metrics and model robustness. Identifying how to distinguish between model-induced uncertainty and label-induced anomalies is critical for deploying reliable autonomous systems.