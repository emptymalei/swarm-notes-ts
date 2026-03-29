---
created_at: '2026-03-29T20:18:23Z'
source_papers:
- '[[openalex-2603.25289-revealing-the-influence-of-participant-failures-on-model-qua]]'
title: Analysis of interacting failure modifiers
---

**Background:** In cross-silo Federated Learning, the combined effect of multiple influencing factors (Failure-Impact Modifiers or FIMs) on model quality during participant failures is complex to isolate and analyze individually.

**Question / Future Work:** Future work should define scenarios where multiple, interacting failure-impact modifiers (such as data skew, model architecture, and timing of failure) are varied simultaneously to understand their combined, synergistic influence on model quality degradation in cross-silo FL, moving beyond isolating single factors.

**Why It Matters:** Understanding the combinatorial effects of FIMs is critical because real-world FL failures rarely occur in isolation; systems must be designed to handle concurrent changes in data distribution, model complexity, and timing.

**Evidence:** Third, analyzing the failure-impact modifiers in complete isolation is not feasible, as each factor (e.g., model architecture, dataset, hyperparameters, aggregation methods) is present while training a model. Hence, a certain combination of multiple factors is always involved. Therefore, it is not possible to exclude whether some connections between these factors are causing additional influence.