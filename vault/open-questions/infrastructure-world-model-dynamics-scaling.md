---
created_at: '2026-04-10T15:27:49Z'
source_papers:
- '[[arxiv-260408199-beyond-static-forecasting-unleashing-the-power-of-world-mode]]'
title: Infrastructure World Model Dynamics Scaling
---

**Background:** World models rely on learned environment dynamics to perform counterfactual simulation and planning, yet their scalability and structural fidelity in highly non-stationary infrastructure networks remain largely unexplored.

**Question / Future Work:** There is a need to formalize the inductive biases required for world models to capture the causal interplay between physical control actions and non-stationary system states in large-scale infrastructure environments. This includes understanding the limits of architectural components like multimodal fusion for spatial semantics versus purely temporal state-transition modeling.

**Why It Matters:** Establishing these architectural requirements is necessary to move beyond simple forecasting toward robust, reliable digital twins that support safe offline reinforcement learning for industrial control.

**Evidence:** Existing world models lack customized modeling of network topology and spatio-temporal traffic dynamics...