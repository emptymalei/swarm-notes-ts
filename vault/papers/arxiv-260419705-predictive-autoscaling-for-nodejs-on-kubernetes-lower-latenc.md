---
# CSL-compatible fields
title: "Predictive Autoscaling for Node.js on Kubernetes: Lower Latency, Right-Sized Capacity"
author:
  - literal: "Ivan Tymoshenko"
  - literal: "Luca Maraschi"
  - literal: "Matteo Collina"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19705"

# Custom fields
paper_id: "2604.19705"
paper_source: "arxiv"
domain: "systems-ml"
tags:
  - "kubernetes-autoscaling"
  - "predictive-forecasting"
  - "node-js-performance"
  - "system-reliability"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "scaler-invariant-metric-modeling"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-22T05:02:55Z"
created_at: "2026-04-22T05:02:55Z"
---

# Predictive Autoscaling for Node.js on Kubernetes: Lower Latency, Right-Sized Capacity

**Authors**: Ivan Tymoshenko, Luca Maraschi, Matteo Collina
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19705](https://arxiv.org/abs/2604.19705)

## Summary

This paper addresses the latency issues in Node.js applications on Kubernetes caused by reactive autoscalers that rely on CPU utilization and delayed reaction loops. The authors propose a predictive scaling algorithm that eliminates the feedback loop between scaling actions and metrics by utilizing cluster-wide invariant aggregates. The methodology includes a specialized metric model and a five-stage processing pipeline to transform raw telemetry into proactive scaling signals. Extensive benchmarking shows superior latency performance compared to default HPA and event-loop-aware KEDA solutions.

## Key Contributions

- Introduces a predictive scaling algorithm that forecasts load to proactively adjust capacity before latency SLO violations occur.
- Identifies and solves the metric corruption feedback loop in Kubernetes autoscalers by operating on cluster-wide, scaling-invariant aggregates.
- Develops a five-stage processing pipeline for converting irregular, partial metric streams into a stable, high-fidelity signal for short-term extrapolation.
- Achieves significantly lower median latency (26ms) compared to KEDA (154ms) and HPA (522ms) during steady traffic ramps.

## Open Questions & Future Work

- [[scaling-invariant-metric-feedback-loop-mitigation]]

## Key Concepts

- [[scaler-invariant-metric-modeling]]: A design pattern for autoscaling that operates on cluster-wide aggregate metrics which remain invariant during scaling actions, thereby preventing the metric-feedback contamination loop.

## Archivist Review

I have approved the concept of 'Scaler-Invariant Metric Modeling' as it captures the core innovation in solving the feedback loop in distributed systems. Correspondingly, I have added an open question focused on the general challenge of 'Mitigating Autoscaling Feedback Loops'. Other candidates were rejected for being too paper-specific or for representing standard software engineering practices rather than high-level machine learning or architectural innovations.

### Approved Concepts
- Scaler-Invariant Metric Modeling: It identifies and solves the fundamental feedback loop problem where reactive autoscalers contaminate their own input telemetry by changing the system state, a critical challenge in distributed systems.

### Approved Open Questions
- Mitigating Autoscaling Feedback Loops: This is a critical architectural bottleneck for scaling any distributed system effectively without over-provisioning or oscillating under reactive control loops.

## Links

- [Abstract](https://arxiv.org/abs/2604.19705)
- [PDF](https://arxiv.org/pdf/2604.19705)

