---
created_at: '2026-05-07T05:15:08Z'
source_papers:
- '[[arxiv-260504793-bilinear-mamba-koopman-neural-mpc-for-varying-dynamics]]'
title: Benchmarking control-state coupling
---

**Background:** Control-affine nonlinear systems often exhibit cross-derivatives between state and input that standard linear Koopman operators are architecturally constrained to force to zero.

**Question / Future Work:** Designing benchmarks that isolate the control-state coupling structural axis from time-varying parameters is necessary to better evaluate the effectiveness of different Koopman operator extensions in distinct dynamical regimes.

**Why It Matters:** This is critical for evaluating the specific architectural gains of models like the bilinear Koopman extension versus other potential improvements for Koopman learning.

**Evidence:** Open directions include [...] designing benchmarks that isolate the u⋅x structural axis from time-varying parameters more cleanly.