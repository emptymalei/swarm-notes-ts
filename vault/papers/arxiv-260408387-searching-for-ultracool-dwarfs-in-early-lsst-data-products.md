---
# CSL-compatible fields
title: "Searching for Ultracool Dwarfs in Early LSST Data Products"
author:
  - literal: "Easton J. Honaker"
  - literal: "John E. Gizis"
  - literal: "Christian Aganze"
  - literal: "Siddharth Chaini"
  - literal: "Federica B. Bianco"
  - literal: "Maruša Žerjal"
  - literal: "Eduardo L. Martín"
  - literal: "Riley W. Clarke"
  - literal: "Ashton Southwick"
  - literal: "Harrison Petrie"
  - literal: "Tyler Blask"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08387"

# Custom fields
paper_id: "2604.08387"
paper_source: "arxiv"
domain: "computer-vision"
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
skill: "GeneralMLSkill"
processed_at: "2026-04-11T04:44:18Z"
created_at: "2026-04-11T04:44:18Z"
---

# Searching for Ultracool Dwarfs in Early LSST Data Products

**Authors**: Easton J. Honaker, John E. Gizis, Christian Aganze, Siddharth Chaini, Federica B. Bianco, Maruša Žerjal, Eduardo L. Martín, Riley W. Clarke, Ashton Southwick, Harrison Petrie, Tyler Blask
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08387](https://arxiv.org/abs/2604.08387)

## Summary

This paper evaluates the performance of the Rubin Observatory's early LSST data products for the identification and characterization of ultracool dwarfs (UCDs). By cross-referencing commissioning data with known catalogs and Euclid-verified objects, the authors validated detection pipelines and identified 89 candidate UCDs. Additionally, they provide scaling forecasts using synthetic population models, projecting the discovery of over 17,000 UCDs in forthcoming LSST Data Preview 2 datasets.

## Key Contributions

- Characterized the early performance of LSST Data Preview 1 for detecting faint ultracool dwarfs (UCDs) through cross-matching with established catalogs.
- Identified 89 UCD candidates, including 17 previously uncatalogued objects, using a combination of LSST photometry and auxiliary spectroscopic data.
- Developed predictive models using synthetic brown dwarf populations to forecast the discovery of over 17,000 UCDs in upcoming LSST Data Preview 2 releases.

## Open Questions & Future Work

- [[l-t-transition-mechanisms]]
- [[lsst-artifact-characterization-bottlenecks]]

## Archivist Review

I have approved two open questions that capture the fundamental bottlenecks in astronomical data processing and stellar physics described in the paper. The concepts provided were not central or reusable enough for individual vault notes, as they largely describe the application of existing survey techniques to specific populations. The open questions have been refined to align with existing naming conventions and to ensure they remain broadly relevant for future research in time-domain astronomy and survey-based machine learning.

### Approved Open Questions
- Mechanisms of L/T Transition: The L/T transition is a critical phase in brown dwarf cooling, impacting the interpretation of photometric survey data and the classification of ultracool dwarfs.
- LSST Artifact Characterization Bottlenecks: Accurate handling of saturated source artifacts is vital for the scientific validity of deep, wide-field sky surveys.

### Rejected Candidates
- [open_question] Physics of the L/T Transition (`lt-transition-physics`) - duplicate_existing: The candidate is a near-duplicate of an existing entry in the vault and has been renamed for clarity.
- [open_question] Characterizing LSST Saturated Source Artifacts (`lsst-saturation-deblending-characterization`) - duplicate_existing: The candidate is a near-duplicate of an existing category of problems in the vault and has been generalized.

## Links

- [Abstract](https://arxiv.org/abs/2604.08387)
- [PDF](https://arxiv.org/pdf/2604.08387)

