---
created_at: '2026-04-07T04:53:55Z'
source_papers:
- '[[arxiv-260404271-a-family-of-open-time-series-foundation-models-for-the-radio]]'
title: Automated Anomaly Thresholding for RAN
---

**Background:** Anomaly detection in time-series data typically requires defining thresholds to classify reconstruction errors as anomalous or normal. In the context of RAN telemetry, establishing these thresholds dynamically or automatically for different network scenarios remains an unsolved challenge.

**Question / Future Work:** The current methodology for anomaly detection relies on manual or task-specific thresholding to distinguish anomalies from normal behavior based on reconstruction error, limiting the fully autonomous deployment of foundation models for real-time network monitoring. Determining an optimal, adaptive thresholding mechanism that does not require domain-specific tuning is an important open problem.

**Why It Matters:** Without robust, automated thresholding, the practical, autonomous application of foundation models for anomaly detection in production networks remains constrained by the need for expert-in-the-loop configuration.