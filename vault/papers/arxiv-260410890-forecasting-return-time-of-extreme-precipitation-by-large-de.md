---
# CSL-compatible fields
title: "Forecasting Return Time of Extreme Precipitation by Large Deviation Theory"
author:
  - literal: "Haotian Xie"
  - literal: "Haoxian Liu"
  - literal: "Jingfang Fan"
  - literal: "Ying Tang"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.10890"

# Custom fields
paper_id: "2604.10890"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "statistical-modeling"
  - "climate-science"
architectures:
  []
datasets:
  - "cmip6"
concept_slugs:
  - "landau-distribution-for-precipitation-extremes"
dataset_slugs:
  - "cmip6"
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:04:28Z"
created_at: "2026-04-14T05:04:28Z"
---

# Forecasting Return Time of Extreme Precipitation by Large Deviation Theory

**Authors**: Haotian Xie, Haoxian Liu, Jingfang Fan, Ying Tang
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.10890](https://arxiv.org/abs/2604.10890)

## Summary

This paper presents a novel framework based on large deviation theory to forecast the return times of extreme precipitation events. By identifying that the Landau distribution—a statistical model from plasma physics—better describes global precipitation extremes than standard distributions, the authors achieve more reliable modeling of rare events. The approach allows for forecasting return times even for intensities that have not been historically observed. Furthermore, the analysis reveals a unified collapse of return time curves under different CMIP6 emission scenarios, highlighting significant increases in lifetime exposure for future birth cohorts.

## Key Contributions

- Introduced the Landau distribution as a superior alternative to conventional extreme value distributions for modeling extreme precipitation at 93% of global locations.
- Proposed a large deviation theory-based framework that enriches rare event samples, enabling return time forecasting for precipitation intensities beyond historical observations.
- Demonstrated that projected extreme precipitation return time curves collapse onto a unified relation across various future CMIP6 emission scenarios.

## Open Questions & Future Work

- [[ldt-asymptotic-regime-climate]]

## Key Concepts

- [[landau-distribution-for-precipitation-extremes]]: The application of the Landau distribution to model the tails of extreme precipitation distributions, outperforming standard extreme value theory.

## Archivist Review

I approved the Landau distribution concept as it represents a significant, reusable statistical refinement for extreme value modeling. CMIP6 was approved as a critical, widely-used dataset for this type of climate research. The LDT validation question was approved for its importance in grounding theoretical frameworks in non-ideal, real-world data, while the sub-daily forecasting question was rejected as a standard incremental task.

### Approved Concepts
- Landau Distribution for Precipitation Extremes: The use of the Landau distribution provides a more robust statistical alternative to conventional extreme value distributions for modeling rare environmental events.

### Approved Open Questions
- LDT Asymptotic Regime Validation: Understanding the breakdown of LDT assumptions in real-world climate data is crucial for preventing overconfident predictions of extreme events.

### Rejected Candidates
- [open_question] Sub-daily extreme precipitation forecasting (`ldt-sub-daily-precipitation`) - low_impact: This is a classic 'apply to more granular data' research direction, which lacks a clear methodological bottleneck or unique theoretical challenge compared to the broader LDT applicability question.

## Datasets

- [[cmip6]]

## Links

- [Abstract](https://arxiv.org/abs/2604.10890)
- [PDF](https://arxiv.org/pdf/2604.10890)

