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
domain: "time-series"
tags:
  - "time-series"
  - "evolutionary-genetics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quasi-linkage-equilibrium-qle-extension"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-24T05:25:32Z"
created_at: "2026-05-24T05:25:32Z"
---

# Fitness Inference in Presence of Migrations between Coupled Evolving Populations

**Authors**: Yu-Han Huang, Bastien Dumont, Hong-Li Zeng, John Barton, Erik Aurell
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22665](https://arxiv.org/abs/2605.22665)

## Summary

This paper extends the concept of Quasi-Linkage Equilibrium (QLE) to populations connected by migration, treating it as a stable state analogous to statistical mechanical equilibrium. The authors demonstrate that this QLE regime is maintained under low migration rates and multi-locus selection. They develop analytical inference methods to accurately estimate additive fitness and epistatic interactions, validating their framework with genomic time-series data simulated via FFPopSim.

## Key Contributions

- Extends Quasi-Linkage Equilibrium (QLE) theory to account for migration between multiple coupled evolutionary subpopulations under multi-locus selection.
- Demonstrates that the QLE phase persists in coupled populations when migration rates are sufficiently low.
- Derives analytical inference relations enabling the accurate quantitative estimation of additive fitness and epistatic interactions from genomic time-series data.

## Key Concepts

- [[quasi-linkage-equilibrium-qle-extension]]: A theoretical framework extending Quasi-Linkage Equilibrium to account for migration between interacting evolutionary subpopulations.

## Archivist Review

I approved the extension of Quasi-Linkage Equilibrium as it represents a significant theoretical contribution to evolutionary population modeling, fulfilling the criteria for reusability in future theoretical biology research. I rejected FFPopSim as it is a simulation engine/software tool rather than a dataset, and no other candidates were presented.

### Approved Concepts
- Quasi-Linkage Equilibrium (QLE) Extension: The paper provides a theoretical extension of QLE, a core concept in evolutionary genetics, to handle coupled populations with migration.

### Rejected Candidates
- [dataset] FFPopSim (`ffpopsim`) - other: This is a simulation software package/framework, not a primary research dataset.

## Links

- [Abstract](https://arxiv.org/abs/2605.22665)
- [PDF](https://arxiv.org/pdf/2605.22665)

