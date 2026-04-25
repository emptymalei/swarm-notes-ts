---
created_at: '2026-04-24T05:08:56Z'
modified_at: '2026-04-25T04:55:25Z'
source_papers:
- '[[arxiv-260421097-learning-to-emulate-chaos-adversarial-optimal-transport-regu]]'
title: Extending OT to Non-Ergodic Dynamics
---

**Background:** Chaotic dynamical systems are highly sensitive to initial conditions, which renders long-term trajectory prediction fundamentally infeasible in many real-world scenarios. Future efforts are required to adapt methods for preserving invariant measures specifically to transient dynamics or systems with non-stationary behavior.

**Question / Future Work:** The current adversarial optimal transport framework is restricted to ergodic systems with a well-defined invariant measure. Extending this approach to non-ergodic regimes, such as transient dynamics or time-dependent systems, remains an unresolved challenge in preserving global statistical properties.

**Why It Matters:** Generalizing these methods to non-stationary systems is critical for applying data-driven emulators to real-world phenomena where the dynamics evolve over time.

**Evidence:** While this approach is currently restricted to ergodic systems with a well-defined attractor, we anticipate that our method can be extended to transient dynamics or mildly time-dependent systems by adjusting the time range over which statistics are computed.