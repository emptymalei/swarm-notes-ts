---
created_at: '2026-04-10T15:27:10Z'
source_papers:
- '[[arxiv-260408398-adaptive-input-training-for-many-to-one-pre-training-on-time]]'
title: Fidelity of Adaptive Pooling
---

**Background:** Time-series data is characterized by diverse modalities, variable sampling rates, and inconsistent input lengths/channel dimensions, which complicates the development of unified foundation models.

**Question / Future Work:** Investigate the extent to which adaptive pooling techniques, while effective for enabling mixed-batch training, result in the loss of critical fine-grained features or temporal distortions in heterogeneous time-series datasets. Future work should determine if there are thresholds where the loss of information due to down-sampling or the artifacts introduced by up-sampling significantly degrade downstream task performance compared to architecture-aware alignment methods.

**Why It Matters:** As time-series foundation models move toward larger scale and more diverse data, understanding the trade-offs between input normalization (via pooling) and signal fidelity is essential for ensuring that pre-trained models do not suffer from latent feature degradation.

**Evidence:** We recognize that adaptively pooling the data risks losing fine-grained information in the data and may cause temporal distortions... We will show that any accuracy losses caused by the temporal distortions are mitigated by the increase in model performance using ADAPT.