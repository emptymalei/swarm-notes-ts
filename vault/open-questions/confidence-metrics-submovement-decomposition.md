---
created_at: '2026-04-24T05:09:49Z'
source_papers:
- '[[arxiv-260420673-short-time-wavelet-inspired-mouse-submovement-detection]]'
title: Confidence Metrics for Submovement Decomposition
---

**Background:** Submovement decomposition of human motion is often limited by difficulties in handling highly overlapping components, which are typically addressed by threshold-based methods that struggle with non-discrete, superimposed movements.

**Question / Future Work:** There is a need to develop more robust confidence metrics for submovement decomposition, specifically by utilizing the residual signals at the end of the wavelet-based decomposition process. Separating net positive and negative residuals could enable a more detailed assessment of the quality of fit for individual submovements and help identify cases where parameters, such as submovement width, have been incorrectly estimated, thereby affecting the overall decomposition accuracy.

**Why It Matters:** This would address a known limitation in current decomposition algorithms where poor parameter estimation in early iterations propagates errors, allowing for more reliable interpretation of submovement patterns in human motor tasks.