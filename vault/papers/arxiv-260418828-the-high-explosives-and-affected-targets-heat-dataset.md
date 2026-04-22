---
# CSL-compatible fields
title: "The High Explosives and Affected Targets (HEAT) Dataset"
author:
  - literal: "Bryan Kaiser"
  - literal: "Kyle Hickmann"
  - literal: "Sharmistha Chakrabarti"
  - literal: "Soumi De"
  - literal: "Sourabh Pandit"
  - literal: "David Schodt"
  - literal: "Jesus Pulido"
  - literal: "Divya Banesh"
  - literal: "Christine Sweeney"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18828"

# Custom fields
paper_id: "2604.18828"
paper_source: "arxiv"
domain: "physics-informed-ml"
tags:
  - "physics-informed-ml"
  - "surrogate-modeling"
  - "scientific-machine-learning"
architectures:
  []
datasets:
  - "heat"
concept_slugs:
  []
dataset_slugs:
  - "heat"
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:04:49Z"
created_at: "2026-04-22T05:04:49Z"
---

# The High Explosives and Affected Targets (HEAT) Dataset

**Authors**: Bryan Kaiser, Kyle Hickmann, Sharmistha Chakrabarti, Soumi De, Sourabh Pandit, David Schodt, Jesus Pulido, Divya Banesh, Christine Sweeney
**Date**: 2026-04-20
**Paper ID**: [arxiv:2604.18828](https://arxiv.org/abs/2604.18828)

## Summary

The HEAT dataset addresses the lack of public data for training AI surrogate models in the domain of high-explosive-driven, multi-material shock dynamics. It comprises two partitions of physics-rich simulations—expanding shock-cylinder (CYL) and perturbed layered interface (PLI)—that include time series of thermodynamic and kinematic fields. This resource provides a critical benchmark for modeling complex shock phenomena such as plastic deformation, momentum transfer, and multi-material interactions.

## Key Contributions

- Introduces the HEAT (High-Explosives and Affected Targets) dataset, a large-scale collection of high-fidelity, two-dimensional cylindrically symmetric multi-material shock physics simulations.
- Provides a multi-physics benchmark capturing complex phenomena including shock propagation, material plasticity, and reactive detonation physics for surrogate model training.
- Enables the development of AI surrogate models as efficient alternatives to full-physics Eulerian multi-material shock-propagation codes.

## Open Questions & Future Work

- [[shock-physics-damage-model-fidelity]]

## Archivist Review

The HEAT dataset was approved as it is a well-defined, physics-focused benchmark dataset serving a distinct scientific domain. The proposed open question was accepted under a more standardized title to better reflect the technical challenge of modeling material damage in high-speed shock scenarios, rather than being framed as a localized limitation of the specific dataset.

### Approved Open Questions
- Shock Physics Damage Model Fidelity: This gap prevents the development of predictive surrogates that can handle real-world material destruction and energy dissipation in high-velocity dynamics.

### Rejected Candidates
- [open_question] Incorporation of damage models (`incorporation-of-damage-models-in-shock-simulations`) - other: Renamed to a more standardized and descriptive slug/title for better indexing.

## Datasets

- [[heat]]

## Links

- [Abstract](https://arxiv.org/abs/2604.18828)
- [PDF](https://arxiv.org/pdf/2604.18828)

