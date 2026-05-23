---
# CSL-compatible fields
title: "Fitness Inference in Presence of Migrations between Coupled Evolving Populations"
author:
  - literal: "Yu-Han Huang"
  - literal: "Bastien Dumont"
  - literal: "Hong-Li Zeng"
  - literal: "John Barton"
  - literal: "Erik Aurell"
issued:
  date-parts:
    - [2026, 5, 21]
url: "https://arxiv.org/abs/2605.22665"

# Custom fields
paper_id: "2605.22665"
paper_source: "arxiv"
domain: "bioinformatics"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "quasi-linkage-equilibrium-qle-extension"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-23T05:20:29Z"
created_at: "2026-05-23T05:20:29Z"
---

# Fitness Inference in Presence of Migrations between Coupled Evolving Populations

**Authors**: Yu-Han Huang, Bastien Dumont, Hong-Li Zeng, John Barton, Erik Aurell
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22665](https://arxiv.org/abs/2605.22665)

## Summary

This paper extends the classical Quasi-Linkage Equilibrium (QLE) theory to describe populations coupled by migration, bridging the gap between isolated population dynamics and interacting subpopulation systems. By utilizing whole-genome time-series data, the authors demonstrate that QLE persists under low migration regimes. Within this framework, they provide new analytical relations to quantify additive fitness and epistatic interactions, offering a rigorous method for inference in complex evolutionary scenarios.

## Key Contributions

- Formalized an extension of the Quasi-Linkage Equilibrium (QLE) theory to account for migration coupling between multiple evolving populations.
- Demonstrated that the QLE phase remains stable for inference under low migration rates.
- Derived new analytical relations for accurately estimating additive fitness and epistatic interactions in migration-connected subpopulations from time-series genomic data.

## Key Concepts

- [[quasi-linkage-equilibrium-qle-extension]]: An extension of the Quasi-Linkage Equilibrium framework to account for migration between coupled, evolving populations under multi-locus selection.

## Archivist Review

I approved the QLE extension concept as it represents a significant theoretical contribution to population genetics modeling by formalizing the equilibrium behavior in coupled systems. I rejected FFPopSim as it is a widely-used simulation library for evolutionary dynamics, not a specific standalone research dataset for benchmarking.

### Approved Concepts
- Quasi-Linkage Equilibrium (QLE) extension: The paper formally extends the QLE framework to multi-population dynamics, which is a major analytical advance over the standard single-population model.

### Rejected Candidates
- [dataset] FFPopSim (`ffpopsim`) - other: FFPopSim is a well-established evolutionary simulation tool/library rather than a specific research dataset for evaluation claims.

## Links

- [Abstract](https://arxiv.org/abs/2605.22665)
- [PDF](https://arxiv.org/pdf/2605.22665)

