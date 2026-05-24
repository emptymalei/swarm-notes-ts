---
# CSL-compatible fields
title: "System Level Analysis and Management of Orbital Debris Using Empirical Dynamic Modeling"
author:
  - literal: "Asaad S. Abdul-Hamid"
  - literal: "Hao Chen"
issued:
  date-parts:
    - [2026, 5, 21]
url: "https://arxiv.org/abs/2605.21892"

# Custom fields
paper_id: "2605.21892"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "shadow-attractor-reconstruction"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-24T05:28:14Z"
created_at: "2026-05-24T05:28:14Z"
---

# System Level Analysis and Management of Orbital Debris Using Empirical Dynamic Modeling

**Authors**: Asaad S. Abdul-Hamid, Hao Chen
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.21892](https://arxiv.org/abs/2605.21892)

## Summary

This research addresses the growing challenge of orbital debris by modeling the population as a non-linear dynamic system. The authors utilize empirical dynamic modeling to reconstruct a shadow attractor from limited observational time-series data, capturing the underlying causal dependencies between launches, debris, and orbital objects. This data-driven approach allows for the simulation of future debris trajectories under various policy scenarios, providing a vital tool for space infrastructure management.

## Key Contributions

- Introduces a shadow attractor reconstruction method to model orbital debris population as a complex dynamic system.
- Enables simulation of orbital debris system evolution under varying policy-induced interventions.
- Demonstrates the ability to infer high-level system dynamics and predict long-term impacts using limited observable data.

## Key Concepts

- [[shadow-attractor-reconstruction]]: A data-driven technique that uses time-delayed embedding to reconstruct the state-space attractor of a complex system from limited observational time-series data.

## Archivist Review

I approved Shadow Attractor Reconstruction as a core concept because it provides a transferable method for non-linear state-space reconstruction from sparse time-series, which is highly relevant to the vault's time-series domain. I rejected Empirical Dynamic Modeling as a candidate because it is a broad, established field rather than a specific method or model architecture derived by this work. No datasets or open questions were proposed or suitable for archival.

### Approved Concepts
- Shadow Attractor Reconstruction: This method allows for the recovery of system dynamics from limited observational data, which is crucial for complex, non-linear time-series modeling.

### Rejected Candidates
- [concept] Empirical Dynamic Modeling (`empirical-dynamic-modeling`) - duplicate_existing: This is a well-established field of complexity science that predates this specific paper and does not require a new vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2605.21892)
- [PDF](https://arxiv.org/pdf/2605.21892)

