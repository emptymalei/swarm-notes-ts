---
title: "Asymmetric Encoder Utilization"
slug: "asymmetric-encoder-utilization"
type: concept
generated_stub: true
source_papers:
  - "[[arxiv-260607031-cf-jepa-mask-free-forward-prediction-with-asymmetric-encoder]]"
processed_at: "2026-06-08T05:48:28Z"
created_at: "2026-06-08T05:48:28Z"
---

# Asymmetric Encoder Utilization

> *Auto-generated stub. Edit this file to add more details.*

A task-routing strategy that assigns downstream tasks to specific encoders based on their distinct latent rank properties (online for discriminative, EMA for temporal smoothness).


## Why It Matters

Provides a systematic method for leveraging distinct rank properties in twin encoder architectures for improved downstream performance.

## Evidence

> A strong asymmetry is also identified between the online encoder and the exponential moving average (EMA) target encoder... Exploiting this asymmetry, classification is routed to the online encoder and forecasting or anomaly detection to the EMA target encoder

## Related Papers

- [[arxiv-260607031-cf-jepa-mask-free-forward-prediction-with-asymmetric-encoder]]
