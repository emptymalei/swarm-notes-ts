---
created_at: '2026-04-15T05:03:12Z'
source_papers:
- '[[arxiv-260412794-stable-fine-time-step-long-horizon-turbulence-prediction-wit]]'
title: Compositional consistency in operators
---

**Background:** Neural operators often suffer from instability during long-horizon autoregressive deployment when the underlying physics are predicted over varying, fine-grained time-sampling intervals.

**Question / Future Work:** There is an unresolved need for training objectives that formally enforce compositional consistency across different prediction strides to ensure that multi-step transitions are physically accurate and stable, rather than relying solely on stride-parameterized expert selection. Establishing these constraints could significantly mitigate the accumulation of errors in long-term turbulence and complex system predictions.

**Why It Matters:** Ensuring formal compositional consistency is a critical theoretical hurdle for reliable, long-horizon autoregressive physical simulators that must function at arbitrary temporal resolutions.

**Evidence:** Future work includes ... multi-step objectives that enforce compositional consistency across strides...