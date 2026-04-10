---
# CSL-compatible fields
title: "What's the (RV) Point? A $3.5\times$ Enhancement in Super-Jupiters with Saturn-like Periods from a Critical Observation"
author:
  - literal: "Marie C. Tagliavia"
  - literal: "Lauren M. Weiss"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07505"

# Custom fields
paper_id: "2604.07505"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:29:58Z"
created_at: "2026-04-10T15:29:58Z"
---

# What's the (RV) Point? A $3.5\times$ Enhancement in Super-Jupiters with Saturn-like Periods from a Critical Observation

**Authors**: Marie C. Tagliavia, Lauren M. Weiss
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07505](https://arxiv.org/abs/2604.07505)

## Summary

This paper evaluates the impact of observational gaps in radial velocity (RV) datasets, specifically concerning the transition between the Keck-HIRES and Keck-KPF instruments. By performing injection-recovery experiments on 2,000 synthetic long-period planetary systems, the authors quantify how adding a single 'critical' RV measurement between disjoint baselines influences planet detection. Results demonstrate a 3.5x improvement in the recovery of super-Jupiters with Saturn-like orbital periods, highlighting the importance of strategic observation scheduling to maintain long-term RV baselines for exoplanet discovery.

## Key Contributions

- Demonstrated that a single 'critical RV' measurement bridging observational gaps between instrument baselines significantly improves long-period planet detection.
- Quantified a 3.5x recovery enhancement for super-Jupiters with Saturn-like periods using injection-recovery experiments with Octofitter.
- Provided a quantitative framework for assessing the impact of instrument retirement on long-term radial velocity (RV) baseline continuity.

## Open Questions & Future Work

- [[rv-gap-bridging-complexity]]

## Archivist Review

The paper provides a domain-specific analysis of radial velocity baseline continuity. While the findings are valuable for exoplanet research, the concepts identified are specific to astronomical observation scheduling rather than general ML or time-series methodologies. The open question regarding the complexity of bridging observational gaps was approved as it captures a broader challenge in long-term time-series signal recovery under non-stationary instrument conditions.

### Approved Open Questions
- Complexity in RV Gap Bridging: This question is technically important because it addresses the scalability of observational gap mitigation from simplified models to complex, realistic orbital architectures in long-term time-series analysis.

### Rejected Candidates
- [concept] Critical RV measurement (`critical-rv-measurement`) - not_reusable: This refers to a specific operational strategy for astronomical observations rather than a reusable machine learning or time-series methodology.
- [concept] Octofitter injection-recovery framework (`octofitter-injection-recovery-framework`) - paper_local: This is a specific domain-specific software tool/workflow rather than a generalizable ML concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.07505)
- [PDF](https://arxiv.org/pdf/2604.07505)

