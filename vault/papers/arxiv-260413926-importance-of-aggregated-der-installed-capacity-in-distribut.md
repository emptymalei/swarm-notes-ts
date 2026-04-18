---
# CSL-compatible fields
title: "Importance of Aggregated DER Installed Capacity in Distribution Networks"
author:
  - literal: "Alexandre M. V. Gouveia"
  - literal: "Md. Umar Hashmi"
  - literal: "Reinhilde D'hulst"
  - literal: "Dirk Van Hertem"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13926"

# Custom fields
paper_id: "2604.13926"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "energy-management"
architectures:
  []
datasets:
  []
concept_slugs:
  - "aggregated-der-installed-capacity-estimation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:53:40Z"
created_at: "2026-04-18T04:53:40Z"
---

# Importance of Aggregated DER Installed Capacity in Distribution Networks

**Authors**: Alexandre M. V. Gouveia, Md. Umar Hashmi, Reinhilde D'hulst, Dirk Van Hertem
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13926](https://arxiv.org/abs/2604.13926)

## Summary

This paper addresses the observability gap in low-voltage distribution networks caused by the high penetration of Distributed Energy Resources (DERs) like EVs and PV systems. The authors propose an estimation framework for aggregated DER installed capacity at LV aggregation points, leveraging substation and feeder measurements to bypass the need for granular customer data. This approach provides a scalable, privacy-preserving method to support key DSO functions, such as congestion management, hosting capacity assessment, and DER-aware load forecasting.

## Key Contributions

- Formalizes the estimation of aggregated Distributed Energy Resource (DER) capacity at low-voltage substations using available feeder measurements rather than customer-level data.
- Demonstrates that aggregated capacity estimates improve critical operational tasks including DER-aware load forecasting, congestion management, and hosting capacity assessment.
- Proposes a scalable observability framework that circumvents common barriers like incomplete topology records and restricted customer data access.

## Open Questions & Future Work

- [[der-capacity-estimation-methods]]
- [[quantifying-der-metadata-impact]]

## Key Concepts

- [[aggregated-der-installed-capacity-estimation]]: A method for estimating the total installed capacity of Distributed Energy Resources at the low-voltage aggregation level using only substation and feeder measurements.

## Archivist Review

I have approved the core concept of aggregated DER capacity estimation as it addresses a fundamental observability gap in distribution networks. The open questions have been refined to focus on the technical challenges of estimation accuracy and the empirical quantification of utility for grid operators, as these are critical research directions. No datasets were approved as none were provided.

### Approved Concepts
- Aggregated DER Installed Capacity Estimation: Provides a scalable, privacy-preserving alternative to customer-level monitoring for DER observability, which is a major bottleneck in distribution grid management.

### Approved Open Questions
- Improving DER capacity estimation methods: Accurate estimation of DER metadata is the foundational step for all downstream operational and planning applications; insufficient estimation accuracy directly limits the effectiveness of forecasting, congestion management, and hosting capacity assessments.
- Quantifying DER metadata utility: Quantifying the impact of this metadata is necessary for DSOs to justify the investment in, and maintenance of, the required data processing pipelines and estimation infrastructures.

## Links

- [Abstract](https://arxiv.org/abs/2604.13926)
- [PDF](https://arxiv.org/pdf/2604.13926)

