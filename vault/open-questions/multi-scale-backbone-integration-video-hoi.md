---
created_at: '2026-04-14T05:06:16Z'
source_papers:
- '[[arxiv-260410397-rethinking-video-human-object-interaction-set-prediction-ove]]'
title: Multi-scale Backbone Integration
---

**Background:** Video-based human-object interaction models rely on feature extraction from visual backbones, but there is an unresolved tension between maintaining spatio-temporal coherence and leveraging hierarchical feature representations.

**Question / Future Work:** There is an open need to develop robust methods for integrating multi-scale feature hierarchies from advanced visual backbones into unified pair-centric video HOI frameworks without losing temporal sensitivity.

**Why It Matters:** Understanding how to effectively integrate backbone hierarchies is critical for scaling performance in unified detection and anticipation models.

**Evidence:** We attribute this to a limitation of the current implementation: only the final feature map of Swin-T is forwarded to the spatio-temporal encoder, forgoing the multi-scale feature hierarchy.