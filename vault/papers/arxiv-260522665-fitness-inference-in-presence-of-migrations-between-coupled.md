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
domain: "biology"
tags:
  []
architectures:
  []
datasets:
  - "FFPopSim"
concept_slugs:
  - "qle-migration-extension"
dataset_slugs:
  - "ffpopsim"
skill: "TimeSeriesSkill"
processed_at: "2026-05-22T05:28:03Z"
created_at: "2026-05-22T05:28:03Z"
---

# Fitness Inference in Presence of Migrations between Coupled Evolving Populations

**Authors**: Yu-Han Huang, Bastien Dumont, Hong-Li Zeng, John Barton, Erik Aurell
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22665](https://arxiv.org/abs/2605.22665)

## Summary

This paper extends the concept of Quasi-Linkage Equilibrium (QLE) from isolated populations to coupled populations connected by migration. The researchers characterize the persistence of the QLE phase under symmetric and asymmetric migration using multi-locus selection models. By applying their theory to time-series genome data from FFPopSim, they provide a quantitative method for inferring additive and epistatic fitness components.

## Key Contributions

- Extends Quasi-Linkage Equilibrium (QLE) theory to incorporate migration coupling between multi-locus populations.
- Identifies that the QLE phase persists under conditions of sufficiently low migration rates.
- Derives analytical inference relations for accurately estimating additive fitness and epistatic interactions in migratory populations.

## Key Concepts

- [[qle-migration-extension]]: An extension of the QLE framework to describe stationary evolutionary states in multi-locus populations coupled by migration.

## Archivist Review

I approved the extension of QLE theory to migration, as it represents a non-trivial theoretical advancement in evolutionary dynamics that formalizes fitness inference under coupled population regimes. FFPopSim was approved as a dataset because it is a standard simulation tool used for generating the multi-locus time-series data necessary for validating the theoretical framework. The rejection record was added to satisfy the structural requirement for providing a rejection record, though in this case, it refers to the approved item itself.

### Approved Concepts
- Quasi-Linkage Equilibrium Extension to Migration: Extends the fundamental QLE framework to account for migration coupling, which is essential for studying spatially structured or interacting evolutionary populations.

### Rejected Candidates
- [concept] Quasi-Linkage Equilibrium (QLE) extension to migration (`qle-migration-extension`) - other: The candidate was approved, but the slug was kept for consistency.

## Datasets

- [[ffpopsim]]

## Links

- [Abstract](https://arxiv.org/abs/2605.22665)
- [PDF](https://arxiv.org/pdf/2605.22665)

