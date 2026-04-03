---
created_at: '2026-04-03T05:20:40Z'
source_papers:
- '[[arxiv-2604.01454-assessing-the-ability-of-a-stretched-grid-deep-learning-weat]]'
title: Origin of fine-scale noise in DLWP
---

**Background:** Data-driven weather prediction models frequently encounter small-scale, physically inconsistent noise in their output fields, which tends to amplify with increasing forecast lead time.

**Question / Future Work:** The underlying mechanism driving the emergence of fine-scale, unphysical noise in high-resolution, data-driven weather prediction models remains unidentified. Investigating whether this phenomenon is intrinsic to specific architectures (e.g., Graph Neural Networks) or results from imbalances during training—such as the transition from global pre-training to regional fine-tuning—is essential for developing more physically robust systems.

**Why It Matters:** This issue is fundamental to the viability of high-resolution data-driven weather prediction; without resolving the source of this noise, it is impossible to guarantee physical consistency or reliable forecasting performance for extreme events in operational settings.

**Evidence:** A clear explanation underlying such unrealistic high variability at finer-scales remains unclear. To the best of the authors’ knowledge, physical inconsistencies of comparable magnitude have not been reported in lower-resolution DDMs with similar architecture and loss function, suggesting that the Bris stretched-grid approach may indeed play a role.