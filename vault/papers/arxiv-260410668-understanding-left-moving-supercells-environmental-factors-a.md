---
# CSL-compatible fields
title: "Understanding Left-Moving Supercells: Environmental Factors and Forecasting Challenges"
author:
  - literal: "Aaron W. Zeeb"
  - literal: "John T. Allen"
  - literal: "Matthew Van Den Broeke"
issued:
  date-parts:
    - [2026, 4, 12]
url: "https://arxiv.org/abs/2604.10668"

# Custom fields
paper_id: "2604.10668"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:05:11Z"
created_at: "2026-04-14T05:05:11Z"
---

# Understanding Left-Moving Supercells: Environmental Factors and Forecasting Challenges

**Authors**: Aaron W. Zeeb, John T. Allen, Matthew Van Den Broeke
**Date**: 2026-04-12
**Paper ID**: [arxiv:2604.10668](https://arxiv.org/abs/2604.10668)

## Summary

This paper addresses the research gap regarding the environmental factors governing left-moving (LM) supercells, which are often overlooked compared to their right-moving counterparts. By analyzing a curated dataset of over 850 LM supercell cases against near-storm proximity soundings, the authors determine the specific thermodynamic and kinematic parameters that differentiate storm strength and duration. Findings highlight the critical role of boundary layer moisture, lapse rates, and hodograph configuration above the LCL in driving LM supercell development and hail severity. The study provides a new parameter space climatology to assist meteorological forecasting of these anticyclonically rotating storms.

## Key Contributions

- Introduces a comprehensive, quality-controlled dataset of over 850 North American left-moving (LM) supercell cases.
- Identifies that LM supercells primarily depend on hodograph shape realizations above the lifting condensation level (LCL).
- Establishes lapse rates, CAPE, and LCL height as primary discriminators for LM supercell intensity and hail-producing potential.

## Open Questions & Future Work

- [[lm-supercell-dynamics-tornadogenesis-mechanisms]]

## Archivist Review

The paper provides a valuable climatological analysis of left-moving supercells, which is primarily a meteorological contribution rather than a novel ML method or architecture. I have approved one open question concerning the underlying physical dynamics of these storms, as this represents a significant gap in predictive understanding that future spatio-temporal modeling might address. Other candidates were rejected as domain-specific findings rather than generalizable machine learning research artifacts.

### Approved Open Questions
- LM Supercell Dynamics Mechanisms: Understanding these dynamics is critical for improving the operational predictability of severe hazards associated with these under-studied convective storms.

### Rejected Candidates
- [dataset] North American LM Supercell Dataset (`north-american-lm-supercell-dataset`) - low_impact: A manually compiled set of storm cases, while useful for this study, does not constitute a broadly reusable benchmark dataset for the general ML community.
- [concept] Hodograph realization at LCL (`hodograph-realization-at-lcl`) - paper_local: This is a meteorological finding rather than a reusable ML concept, mechanism, or architecture.

## Links

- [Abstract](https://arxiv.org/abs/2604.10668)
- [PDF](https://arxiv.org/pdf/2604.10668)

