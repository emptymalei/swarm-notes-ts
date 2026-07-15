---
# CSL-compatible fields
title: "AutoSLO: Practical Latency SLOs on Cloud Data Warehouses -- Extended Version"
author:
  - literal: "Markos Markakis"
  - literal: "Tim Kraska"
issued:
  date-parts:
    - [2026, 7, 13]
url: "https://arxiv.org/abs/2607.11770"

# Custom fields
paper_id: "2607.11770"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  - "Redbench"
concept_slugs:
  - "autoslo"
dataset_slugs:
  - "redbench"
skill: "GeneralMLSkill"
processed_at: "2026-07-15T19:43:18Z"
created_at: "2026-07-15T19:43:18Z"
---

# AutoSLO: Practical Latency SLOs on Cloud Data Warehouses -- Extended Version

**Authors**: Markos Markakis, Tim Kraska
**Date**: 2026-07-13
**Paper ID**: [arxiv:2607.11770](https://arxiv.org/abs/2607.11770)

## Summary

AutoSLO is a multi-timescale workload management framework designed for cloud data warehouses with disaggregated compute and storage. It coordinates proactive cluster scaling via a Policy Tuner, reactive cluster adjustment through an SLO-aware Autoscaler, and granular query placement via a concurrency-aware Query Router. Empirical results on Redbench workloads demonstrate that the framework significantly reduces costs while improving latency SLO compliance compared to existing baseline strategies.

## Key Contributions

- Introduces AutoSLO, a hierarchical framework for meeting latency SLOs across three distinct operational timescales.
- Achieves a 26.4% mean cost reduction on Redbench workloads while maintaining latency SLO compliance.
- Demonstrates that reactive component-level interventions (Query Router and Autoscaler) can reduce SLO violation rates by 47.8% and 93.7%, respectively.

## Key Concepts

- [[autoslo]]: A multi-timescale workload management framework that coordinates proactive scaling, reactive cluster adjustment, and query routing to meet latency SLOs.

## Archivist Review

I approved the AutoSLO framework as it proposes a distinct multi-timescale control architecture for distributed systems, which is a reusable pattern in cloud infrastructure. Its sub-components were rejected in favor of the overarching framework to avoid cluttering the vault with specific implementation modules. The Redbench dataset was approved as the central evaluation artifact for this study.

### Approved Concepts
- AutoSLO: Provides a reusable multi-timescale architecture for managing latency objectives in resource-disaggregated distributed systems.

### Rejected Candidates
- [concept] Query Router (`query-router`) - subcomponent_of_broader_mechanism: This is a specific sub-component of the broader AutoSLO framework.
- [concept] Policy Tuner (`policy-tuner`) - subcomponent_of_broader_mechanism: This is a specific sub-component of the broader AutoSLO framework.
- [concept] SLO-aware Autoscaler (`slo-aware-autoscaler`) - subcomponent_of_broader_mechanism: This is a specific sub-component of the broader AutoSLO framework.

## Datasets

- [[redbench]]

## Links

- [Abstract](https://arxiv.org/abs/2607.11770)
- [PDF](https://arxiv.org/pdf/2607.11770)

