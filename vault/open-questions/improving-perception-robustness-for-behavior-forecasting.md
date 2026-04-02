---
created_at: '2026-04-02T05:37:22Z'
source_papers:
- '[[arxiv-2604.01015-forecasting-motion-in-the-wild]]'
title: Improving Perception for Motion Forecasting
---

**Background:** Behavioral forecasting in computer vision has historically relied on category-specific models or direct pixel prediction, both of which suffer from data inefficiency and limited generalization. The adoption of dense point trajectories as visual tokens for behavior has emerged as a promising, category-agnostic alternative, yet it remains challenging to scale these methods to handle complex, long-tailed, and non-rigid motion in unconstrained environments.

**Question / Future Work:** While the proposed method for forecasting point trajectories on non-rigid agents demonstrates strong performance on animal datasets, the authors acknowledge that further research is needed to improve the robustness and generalizability of the pipeline, particularly for cases where perception models (e.g., segmenters or trackers) may fail. Future work could focus on developing more resilient perception modules that are less sensitive to the noise and partial observability characteristic of in-the-wild video.

**Why It Matters:** This is critical because the quality of the learned motion representation depends heavily on the accuracy of the underlying perception pipeline; if the data processing is noisy or incomplete, the trajectory forecasting model's performance on rare species or complex scenarios will be severely hindered.