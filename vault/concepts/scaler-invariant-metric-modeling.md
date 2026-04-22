---
title: "Scaler-Invariant Metric Modeling"
slug: "scaler-invariant-metric-modeling"
type: concept
generated_stub: true
source_papers:
  - "[[arxiv-260419705-predictive-autoscaling-for-nodejs-on-kubernetes-lower-latenc]]"
processed_at: "2026-04-22T05:02:55Z"
created_at: "2026-04-22T05:02:55Z"
---

# Scaler-Invariant Metric Modeling

> *Auto-generated stub. Edit this file to add more details.*

A design pattern for autoscaling that operates on cluster-wide aggregate metrics which remain invariant during scaling actions, thereby preventing the metric-feedback contamination loop.


## Why It Matters

It identifies and solves the fundamental feedback loop problem where reactive autoscalers contaminate their own input telemetry by changing the system state, a critical challenge in distributed systems.

## Evidence

> We observe that operating on a cluster-wide aggregate that is approximately invariant under scaling eliminates this feedback loop, producing a stable signal suitable for short-term extrapolation.

## Related Papers

- [[arxiv-260419705-predictive-autoscaling-for-nodejs-on-kubernetes-lower-latenc]]
