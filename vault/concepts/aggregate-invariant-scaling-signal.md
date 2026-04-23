---
title: "Aggregate Invariant Scaling Signal"
slug: "aggregate-invariant-scaling-signal"
type: concept
generated_stub: true
source_papers:
  - "[[arxiv-260419705-predictive-autoscaling-for-nodejs-on-kubernetes-lower-latenc]]"
processed_at: "2026-04-23T05:08:55Z"
created_at: "2026-04-23T05:08:55Z"
---

# Aggregate Invariant Scaling Signal

> *Auto-generated stub. Edit this file to add more details.*

A technique for generating stable forecasting signals for autoscalers by using cluster-wide aggregates that remain invariant when the number of replicas changes.


## Why It Matters

This addresses the fundamental problem of autoscaler feedback loops where adding instances corrupts per-instance metrics, enabling proactive rather than reactive scaling.

## Evidence

> We observe that operating on a cluster-wide aggregate that is approximately invariant under scaling eliminates this feedback loop, producing a stable signal suitable for short-term extrapolation.

## Related Papers

- [[arxiv-260419705-predictive-autoscaling-for-nodejs-on-kubernetes-lower-latenc]]
