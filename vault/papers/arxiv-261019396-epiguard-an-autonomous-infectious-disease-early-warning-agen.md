---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "EpiGuard: An Autonomous Infectious-Disease Early Warning Agent Platform"
description: "EpiGuard is an autonomous, agentic platform designed to provide timely early warnings for over 50 infectious diseases by continuously monitoring official surveillance data. To solve the problem of fragmented and uneven data availability, the system utilizes a dynamic strategy that adapts its analysis across three regimes: no historical data, sparse data, and abundant data. A core innovation is its ability to self-improve by converting successful analytical workflows into reusable Standard Operating Procedures (SOPs), which enables the agent to generalize to new diseases and regions. Empirical evaluations on China and US CDC datasets show significant improvements (9.68% and 14.04% respectively) over existing forecasting baselines."
resource: "https://arxiv.org/abs/2610.19396"
tags:
  - "time-series-forecasting"
  - "ai-agents"
  - "agentic-workflow"
  - "epidemiological-modeling"
  - "public-health"
  - "early-warning-systems"
  - "healthcare"
  - "zero-shot-learning"
  - "few-shot-learning"
timestamp: "2026-10-18T00:46:43Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Tonglong Wei"
  - literal: "Zheng Yuan"
  - literal: "Lingshuai Lin"
  - literal: "Yuhui Yao"
  - literal: "Xing Xie"
  - literal: "Na Zou"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19396"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "evidence-availability-regimes"
    description: "An adaptive framework that selects analytical strategies based on whether available data is non-existent, sparse, or abundant."
  - name: "agentic-sop"
    description: "The formalization and storage of successful multi-step agent workflows into modular, reusable instructions for future task execution."
datasets:
  []
open_questions:
  - name: "cross-regional-reporting-bias-in-agents"
    description: "How can agentic standard operating procedures (SOPs) account for systemic biases and infrastructure variations when transferring knowledge from high-resource data environments to resource-constrained regions?"
  - name: "zero-shot-warning-reliability-thresholds"
    description: "What are the optimal signal-to-noise thresholds for agentic systems operating in zero-shot regimes to ensure that warnings are issued only when necessary without historical data to calibrate confidence?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:46:43Z"
created_at: "2026-10-18T00:46:43Z"
---

# EpiGuard: An Autonomous Infectious-Disease Early Warning Agent Platform

**Authors**: Tonglong Wei, Zheng Yuan, Lingshuai Lin, Yuhui Yao, Xing Xie, Na Zou
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19396](https://arxiv.org/abs/2610.19396)

## Summary

EpiGuard is an autonomous, agentic platform designed to provide timely early warnings for over 50 infectious diseases by continuously monitoring official surveillance data. To solve the problem of fragmented and uneven data availability, the system utilizes a dynamic strategy that adapts its analysis across three regimes: no historical data, sparse data, and abundant data. A core innovation is its ability to self-improve by converting successful analytical workflows into reusable Standard Operating Procedures (SOPs), which enables the agent to generalize to new diseases and regions. Empirical evaluations on China and US CDC datasets show significant improvements (9.68% and 14.04% respectively) over existing forecasting baselines.

## Key Contributions

- Developed EpiGuard, an autonomous agent platform that proactively monitors, analyzes, and issues early warnings for over 50 infectious diseases by scraping official surveillance records.
- Implemented an adaptive strategy that transitions across three evidence availability regimes, allowing for reliable risk assessment even in zero-shot or data-sparse scenarios.
- Introduced a self-improving mechanism that encodes successful data-acquisition and analysis workflows into reusable Standard Operating Procedures (SOPs) to facilitate generalization to new diseases and regions.
- Achieved a reduction in forecasting error by 9.68% on China CDC data and 14.04% on U.S. CDC data compared to current state-of-the-art epidemiological forecasting systems.

## Limitations

The abstract does not detail the latency of the 'proactive monitoring' compared to official human reporting or the potential for agents to ingest misinformation from unofficial sources.

## Open Questions & Future Work

- [[cross-regional-reporting-bias-in-agents]]
- [[zero-shot-warning-reliability-thresholds]]

## Key Concepts

- [[evidence-availability-regimes]]: An adaptive framework that selects analytical strategies based on whether available data is non-existent, sparse, or abundant.
- [[agentic-sop]]: The formalization and storage of successful multi-step agent workflows into modular, reusable instructions for future task execution.

## Archivist Review

I approved concepts focusing on the agent's unique procedural learning mechanism (Agentic SOPs) and its adaptive handling of data density (Evidence Availability Regimes). I rejected the datasets as they are routine public health records used for benchmarking. The approved open questions target the reliability and transferability of autonomous systems in high-stakes environments like infectious disease monitoring.

### Approved Concepts
- Evidence Availability Regimes: This framework addresses the real-world challenge of extreme data heterogeneity in time-series monitoring, where an agent must transition between zero-shot inference and data-intensive forecasting.
- Agentic Standard Operating Procedures (SOPs): It enables agents to move beyond transient 'reasoning-in-context' to long-term procedural knowledge acquisition, facilitating generalization to new domains.

### Approved Open Questions
- Procedural Transfer Across Reporting Biases: Successful generalization across regions is critical for global health equity, yet reporting biases often lead to model failure when transferred.
- Zero-Shot Warning Signal Thresholds: The reliability of autonomous warning systems determines their practical utility in policy-making and public health response.

### Rejected Candidates
- [dataset] China CDC Surveillance Data (`china-cdc-surveillance-data`) - generic: This is a routine governmental surveillance source rather than a novel, curated research dataset or benchmark introduced by the paper.
- [dataset] U.S. CDC Surveillance Data (`u-s-cdc-surveillance-data`) - generic: This is a standard public data source used for evaluation and is not a new contribution to the ML community.
- [concept] EpiGuard (`epiguard`) - paper_local: EpiGuard is the name of the specific platform/system described in the paper rather than a distinct, reusable machine learning concept.

## Links

- [Abstract](https://arxiv.org/abs/2610.19396)
- [PDF](https://arxiv.org/pdf/2610.19396)

