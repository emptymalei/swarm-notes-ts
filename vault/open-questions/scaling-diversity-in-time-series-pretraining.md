---
created_at: '2026-04-12T05:02:51Z'
source_papers:
- '[[arxiv-260408398-adaptive-input-training-for-many-to-one-pre-training-on-time]]'
title: Scaling Data Diversity for Time-Series Foundation Models
---

**Background:** While diverse pre-training shows performance gains, scaling data diversity in time-series foundation models can lead to performance variance and instability. It is currently unclear how dataset diversity, total volume, and model stability interact at scale.

**Question / Future Work:** Investigating the relationship between dataset diversity, the total volume of training data, and model stability is necessary to optimize pre-training for heterogeneous time-series collections. Identifying when adding more diverse datasets leads to diminishing returns or performance degradation remains an open challenge.

**Why It Matters:** Understanding the scaling laws of time-series pre-training is essential for building robust, generalist foundation models that can consistently benefit from increasingly diverse data sources.

**Evidence:** Considering that ADAPT(EEG) provided worse performance than ADAPT on the Epilepsy (in-domain) benchmark, it is not clear why it it achieves close to perfect classification accuracy on this benchmark. We believe this may be a result of vastly increasing the diversity of the training data between the two models without proportionally increasing the amount of training data, resulting in some instabilities in model performance.