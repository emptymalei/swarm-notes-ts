---
created_at: '2026-04-14T05:02:20Z'
source_papers:
- '[[arxiv-260411707-representations-before-pixels-semantics-guided-hierarchical]]'
title: Hierarchical Temporal Coherence Bottlenecks
---

**Background:** Multi-stage generative video models frequently experience a distribution shift between ground-truth features used during training and predicted features used during inference, leading to error accumulation. While hierarchical models that separate semantic representation forecasting from visual synthesis address this via architectural decomposition, maintaining temporal consistency across long horizons remains an open problem.

**Question / Future Work:** Develop robust mechanisms to ensure long-term temporal coherence when bridging the gap between semantic feature prediction and visual synthesis in hierarchical world models. This involves addressing how to maintain structural and semantic stability without relying on cumulative ground-truth supervision.

**Why It Matters:** This bottleneck is central to the viability of hierarchical generative modeling for real-world robotics and autonomous navigation tasks.

**Evidence:** A key challenge arises from the train-test mismatch between ground-truth representations available during training and predicted ones used at inference.