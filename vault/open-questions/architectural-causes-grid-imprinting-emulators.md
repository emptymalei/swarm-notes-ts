---
created_at: '2026-04-22T05:05:15Z'
source_papers:
- '[[arxiv-260418727-skillful-global-ocean-emulation-and-the-role-of-correlation]]'
title: Architectural Causes of Grid Imprinting
---

**Background:** Graph-based neural network emulators for Earth system science often exhibit grid-locking artifacts during long-term rollouts, yet the causal factors linking architectural design to these artifacts remain largely empirical.

**Question / Future Work:** Investigate the architectural dependencies of grid imprinting artifacts in graph-based emulators to determine if they are specific to the encoder design or a general consequence of ill-conditioned input feature matrices. This research would identify whether these artifacts can be systematically prevented through architectural improvements rather than heuristic constraints on input history.

**Why It Matters:** Understanding the root cause of grid-locking is essential for building stable, long-term predictive models and avoiding the need for arbitrary constraints on model inputs that may discard valuable historical information.

**Evidence:** Whether these artifacts are architecture-dependent remains unclear and requires further investigation.