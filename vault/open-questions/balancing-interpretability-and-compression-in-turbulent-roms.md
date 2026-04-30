---
created_at: '2026-04-30T05:14:21Z'
source_papers:
- '[[arxiv-260426240-reduced-order-modeling-of-a-viscoelastic-turbulent-jet-with]]'
title: Interpretability vs. compression in ROMs
---

**Background:** Proper orthogonal decomposition (POD) provides a linear, physically interpretable basis for representing turbulent fluid flows, but often struggles to capture small-scale dynamics without a large number of modes. Conversely, data-driven autoencoders offer superior nonlinear compression but lack the orthogonality and physical interpretability of POD.

**Question / Future Work:** Further research is required to develop hybrid reduced-order modeling (ROM) frameworks that reconcile the physical interpretability and orthogonality of POD with the superior nonlinear representational power of deep networks to accurately capture small-scale dynamics in turbulence without requiring excessive mode counts.

**Why It Matters:** This tension is a fundamental bottleneck in the design of efficient, robust, and physically grounded surrogates for high-dimensional chaotic systems.