---
created_at: '2026-03-29T20:16:51Z'
source_papers:
- '[[openalex-2603.24936-tigflow-grpo-trajectory-forecasting-via-interaction-aware-fl]]'
title: Integrating Behavioral Constraints in Pretraining
---

**Background:** Generative trajectory forecasting models, particularly those based on Conditional Flow Matching (CFM), are typically trained using supervised objectives that aim to match empirical data distributions.

**Question / Future Work:** The framework's reliance on post-training using Group Relative Policy Optimization (GRPO) to enforce non-differentiable social and physical constraints suggests that supervised pretraining alone is insufficient for generating behaviorally plausible futures across all modes. Further investigation into how to integrate these constraints more deeply into the flow-matching objective, perhaps during pretraining, or refining the ODE-to-SDE transition parameters for better exploration/exploitation balance, remains an avenue for improvement beyond the current two-stage approach.

**Why It Matters:** Addressing this gap could lead to single-stage, more efficient models that inherently respect real-world constraints without the overhead of a separate reinforcement learning post-training step.

**Evidence:** Although Conditional Flow Matching (CFM) has shown strong ability in modeling trajectory distributions from spatio-temporal observations, existing approaches still focus primarily on supervised fitting, which may leave social norms and scene constraints insufficiently reflected in generated trajectories.