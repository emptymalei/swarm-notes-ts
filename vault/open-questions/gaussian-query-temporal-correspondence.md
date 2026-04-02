---
created_at: '2026-04-02T05:37:30Z'
source_papers:
- '[[arxiv-2604.00969-dlwm-dual-latent-world-models-enable-holistic-gaussian-centr]]'
title: Temporal Correspondence of Gaussians
---

**Background:** In Gaussian-centric autonomous driving, the lack of inherent one-to-one correspondence between Gaussian queries across different temporal frames complicates direct feature-level supervision for temporal modeling.

**Question / Future Work:** Establishing direct, stable correspondence between sparse Gaussian primitives across time is necessary to facilitate robust temporal feature learning without relying on intermediate representations like BEV grids. Developing a mechanism for direct, permutation-invariant temporal supervision of Gaussian queries remains an open research challenge.

**Why It Matters:** Direct temporal modeling on Gaussian primitives could bypass the inefficiencies of intermediate BEV-based representations, improving both compute performance and feature fidelity in long-horizon forecasting.