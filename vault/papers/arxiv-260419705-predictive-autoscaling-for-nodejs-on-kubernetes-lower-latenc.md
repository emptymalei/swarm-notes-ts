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
domain: "nlp"
tags:
  - "adaptive-input-training"
architectures:
  []
datasets:
  []
concept_slugs:
  - "aggregate-invariant-scaling-signal"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-23T05:08:55Z"
created_at: "2026-04-23T05:08:55Z"
---

# Predictive Autoscaling for Node.js on Kubernetes: Lower Latency, Right-Sized Capacity

**Authors**: Ivan Tymoshenko, Luca Maraschi, Matteo Collina
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19705](https://arxiv.org/abs/2604.19705)

## Summary

This paper addresses the structural limitations of reactive Kubernetes autoscalers for Node.js workloads, which fail to account for event loop saturation and startup latency. The authors propose a predictive scaling algorithm that utilizes a cluster-wide aggregate metric to eliminate the feedback loop caused by instance churn. Through a five-stage processing pipeline, the system transforms noisy, partial metrics into a stable signal for proactive capacity provisioning, significantly outperforming HPA and KEDA in latency-critical scenarios.

## Key Contributions

- Proposes a predictive autoscaling algorithm that forecasts system load to account for pod startup latency, preventing SLO degradation.
- Introduces the use of cluster-wide aggregate metrics to eliminate feedback loops where scaling actions corrupt input data for the scaling controller.
- Demonstrates significant performance gains over standard HPA and KEDA, reducing median latency from 522ms/154ms to 26ms under steady traffic ramp conditions.

## Key Concepts

- [[aggregate-invariant-scaling-signal]]: A technique for generating stable forecasting signals for autoscalers by using cluster-wide aggregates that remain invariant when the number of replicas changes.

## Archivist Review

I approved 'Aggregate Invariant Scaling Signal' as it provides a clear, reusable methodological solution to the feedback loop problem inherent in reactive autoscaling. I rejected 'Predictive Autoscaling Algorithm' as it is a generic task description, and 'Metric Model' as it is a localized, under-defined architectural component. No datasets or open questions met the stringent threshold for archival.

### Approved Concepts
- Aggregate Invariant Scaling Signal: This addresses the fundamental problem of autoscaler feedback loops where adding instances corrupts per-instance metrics, enabling proactive rather than reactive scaling.

### Rejected Candidates
- [concept] Predictive Autoscaling Algorithm (`predictive-autoscaling-algorithm`) - generic: This is a generic description of the system task rather than a specific, reusable methodological contribution.
- [concept] Metric Model (`metric-model`) - paper_local: This is an overly generic name for a set of functions and lacks sufficient detail to serve as a distinct, reusable concept in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.19705)
- [PDF](https://arxiv.org/pdf/2604.19705)

