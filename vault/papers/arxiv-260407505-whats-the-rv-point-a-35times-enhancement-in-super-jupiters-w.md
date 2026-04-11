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
  - "time-series-forecasting"
  - "anomaly-detection"
  - "simulation-study"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:46:58Z"
created_at: "2026-04-11T04:46:58Z"
---

# What's the (RV) Point? A $3.5\times$ Enhancement in Super-Jupiters with Saturn-like Periods from a Critical Observation

**Authors**: Marie C. Tagliavia, Lauren M. Weiss
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07505](https://arxiv.org/abs/2604.07505)

## Summary

This paper examines the impact of sparse, critical radial velocity (RV) measurements on the recovery of long-period giant exoplanets when transitioning between observational instruments. Using injection-recovery experiments with the Octofitter code on 2000 simulated 1-planet systems, the authors show that a single bridging RV measurement can significantly improve recovery rates, particularly for super-Jupiters with Saturn-like periods (8-55 years). The findings highlight how targeted sampling strategies can preserve the scientific value of long-term stable RV baselines despite instrument retirement and potential zeropoint offsets.

## Key Contributions

- Quantified the impact of a single 'critical RV' measurement on bridging observational gaps in radial velocity (RV) baselines for long-period planet detection.
- Demonstrated a 3.5x improvement in recovery rates specifically for super-Jupiters with Saturn-like orbital periods (8-55 years).
- Validated the effectiveness of sparse, targeted observations to maintain the scientific utility of legacy instrument baselines during transitions to new hardware (e.g., Keck-HIRES to KPF).

## Open Questions & Future Work

- [[bridge-observation-efficiency-limits-for-complex-systems]]

## Archivist Review

The paper offers a well-defined simulation-based study on the utility of sparse 'critical' observations for maintaining temporal baseline integrity, which is a specific, actionable insight for long-term time-series collection. I approved a refined version of the open question regarding the extension of this methodology to more complex dynamical systems, as this addresses a tangible limitation in applying the results to real-world astronomical data. No concepts were approved as the 'critical observation' strategy is a domain-specific application of known sampling principles rather than a general-purpose ML concept.

### Approved Open Questions
- Bridge observation efficiency limits for complex systems: This research is essential for generalizing the efficacy of sparse observational strategies from idealized single-planet scenarios to the more complex, realistic populations encountered in long-term astronomical surveys.

### Rejected Candidates
- [open_question] Complexity in long-term RV recovery (`complexity-in-long-term-rv-recovery`) - other: The title and phrasing were slightly generic; a more specific slug and background were generated to better capture the research question in the context of temporal bridge observations.

## Links

- [Abstract](https://arxiv.org/abs/2604.07505)
- [PDF](https://arxiv.org/pdf/2604.07505)

