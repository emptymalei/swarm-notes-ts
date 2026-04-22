---
created_at: '2026-04-22T05:02:55Z'
source_papers:
- '[[arxiv-260419705-predictive-autoscaling-for-nodejs-on-kubernetes-lower-latenc]]'
title: Mitigating Autoscaling Feedback Loops
---

**Background:** Reactive autoscalers in distributed systems often struggle with metric-feedback loops where scaling actions (e.g., adding nodes) directly redistribute load and alter the telemetry that the scaler relies on.

**Question / Future Work:** Developing robust, general-purpose methods to identify and utilize scaling-invariant metrics that remain stable under dynamic capacity changes, ensuring that control loops react only to external demand rather than their own internal state updates.

**Why It Matters:** This is a critical architectural bottleneck for scaling any distributed system effectively without over-provisioning or oscillating under reactive control loops.