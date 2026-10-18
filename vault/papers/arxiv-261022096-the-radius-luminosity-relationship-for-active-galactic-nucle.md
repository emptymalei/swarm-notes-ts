---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "The Radius-Luminosity Relationship for Active Galactic Nuclei with Hierarchical Bayesian Reverberation Mapping"
description: "This paper introduces a hierarchical Bayesian framework for reverberation mapping of active galactic nuclei (AGN), enabling the simultaneous estimation of individual time lags and population-level properties like the radius-luminosity (R-L) relationship. By marginalizing over data uncertainties and seasonal aliasing, the method avoids the information loss common in traditional sequential analysis and heuristic quality filtering. When applied to the OzDES sample, the approach increased the effective sample size of recovered lags by an order of magnitude and doubled the constraining power on the R-L relation, providing a robust path for industrial-scale AGN analysis in future surveys."
resource: "https://arxiv.org/abs/2610.22096"
tags:
  - "astrophysics"
  - "bayesian-inference"
  - "bayesian-methods"
  - "time-series-analysis"
  - "time-series"
  - "statistical-modeling"
timestamp: "2026-10-18T00:16:34Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Hugh McDougall"
  - literal: "Tamara M. Davis"
  - literal: "Benjamin J. S. Pope"
  - literal: "Paul Martini"
  - literal: "Zhefu Yu"
  - literal: "Chris Lidman"
  - literal: "Geraint F. Lewis"
  - literal: "Christian Adamcewicz"
  - literal: "Rahma Alfarsy"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22096"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "hierarchical-bayesian-reverberation-mapping"
    description: "A statistical framework that simultaneously fits individual AGN time lags and global population models using hierarchical Bayesian inference to handle data uncertainty and seasonal aliasing."
datasets:
  []
open_questions:
  - name: "scaling-hbrm-to-lsst-scale"
    description: "How can hierarchical Bayesian frameworks for reverberation mapping be optimized to maintain numerical stability and computational tractability when applied to the massive, high-cadence time-series data streams expected from the Vera C. Rubin Observatory (LSST)?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:16:34Z"
created_at: "2026-10-18T00:16:34Z"
---

# The Radius-Luminosity Relationship for Active Galactic Nuclei with Hierarchical Bayesian Reverberation Mapping

**Authors**: Hugh McDougall, Tamara M. Davis, Benjamin J. S. Pope, Paul Martini, Zhefu Yu, Chris Lidman, Geraint F. Lewis, Christian Adamcewicz, Rahma Alfarsy
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22096](https://arxiv.org/abs/2610.22096)

## Summary

This paper introduces a hierarchical Bayesian framework for reverberation mapping of active galactic nuclei (AGN), enabling the simultaneous estimation of individual time lags and population-level properties like the radius-luminosity (R-L) relationship. By marginalizing over data uncertainties and seasonal aliasing, the method avoids the information loss common in traditional sequential analysis and heuristic quality filtering. When applied to the OzDES sample, the approach increased the effective sample size of recovered lags by an order of magnitude and doubled the constraining power on the R-L relation, providing a robust path for industrial-scale AGN analysis in future surveys.

## Key Contributions

- Developed a numerically stable hierarchical Bayesian framework that simultaneously models individual AGN time lags and global population parameters.
- Replaced traditional heuristic quality cuts and stacking procedures with a unified method that marginalizes over data uncertainty and seasonal aliasing.
- Achieved a tenfold increase in the number of high-quality lag and mass recoveries (from 24 to ~297) compared to standard methods when applied to the OzDES sample.
- Demonstrated a twofold improvement in the precision of constraints on the AGN radius-luminosity relationship.

## Limitations

The framework assumes specific population-level priors (like the R-L relation) which might introduce bias if the underlying physical model is misspecified.

## Open Questions & Future Work

- [[scaling-hbrm-to-lsst-scale]]

## Key Concepts

- [[hierarchical-bayesian-reverberation-mapping]]: A statistical framework that simultaneously fits individual AGN time lags and global population models using hierarchical Bayesian inference to handle data uncertainty and seasonal aliasing.

## Archivist Review

I have approved the Hierarchical Bayesian Reverberation Mapping (HBRM) concept as it represents a significant methodological shift in time-series population modeling, moving from heuristic stacking to a unified Bayesian hierarchy. The open question regarding its scalability to LSST-scale datasets is included as it identifies a major computational bottleneck for hierarchical modeling in massive time-domain surveys. Other candidates were rejected as they represent domain-specific physical laws or existing astronomical surveys rather than reusable ML contributions.

### Approved Concepts
- Hierarchical Bayesian Reverberation Mapping: It provides a statistically robust alternative to traditional heuristic quality cuts and stacking methods, enabling the recovery of population-level parameters and individual time lags from sparse, seasonal time-series data.

### Approved Open Questions
- Scalability of HBRM to LSST-scale Surveys: The ability to process petabyte-scale data is a prerequisite for the next generation of time-domain astronomy and industrial-scale black hole mass estimation.

### Rejected Candidates
- [concept] Radius-Luminosity Relationship (`radius-luminosity-relationship`) - not_novel: This is a well-established physical law in astrophysics used as a test case, not a novel machine learning or statistical concept introduced by the paper.
- [dataset] OzDES (`ozdes`) - duplicate_existing: OzDES is an existing astronomical survey dataset, not a new dataset contribution or specific ML benchmark introduced here.

## Links

- [Abstract](https://arxiv.org/abs/2610.22096)
- [PDF](https://arxiv.org/pdf/2610.22096)

