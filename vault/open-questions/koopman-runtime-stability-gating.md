---
created_at: '2026-05-07T05:15:08Z'
source_papers:
- '[[arxiv-260504793-bilinear-mamba-koopman-neural-mpc-for-varying-dynamics]]'
title: Runtime stability gating for MPC
---

**Background:** Koopman operator models often rely on spectral penalties during training to ensure the stability of the learned dynamical systems.

**Question / Future Work:** The development of reliable runtime stability gating mechanisms for Koopman-based MPC controllers, which currently lack formal guarantees that the effective operator remains stable within the unit disk for all inputs, is a significant open challenge.

**Why It Matters:** Ensuring stability is a primary requirement for deploying learned controllers in safety-critical industrial environments.

**Evidence:** We did, however, evaluate the cheap Gershgorin disk pre-check [...] as an O(dz2) stability certificate at each MPC step. Empirically the disks straddle the unit circle [...] A full eigendecomposition would therefore be required for any runtime spectral gate [...] but we leave runtime stability gating to future work.