---
# CSL-compatible fields
title: "Predicted number counts and clustering of Hi galaxies from future radio surveys"
author:
  - literal: "Ainulnabilah Nasirudin"
  - literal: "Philip Bull"
  - literal: "Isabelle Ye"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26886"

# Custom fields
paper_id: "2604.26886"
paper_source: "arxiv"
domain: "cosmology"
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
processed_at: "2026-04-30T05:12:44Z"
created_at: "2026-04-30T05:12:44Z"
---

# Predicted number counts and clustering of Hi galaxies from future radio surveys

**Authors**: Ainulnabilah Nasirudin, Philip Bull, Isabelle Ye
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26886](https://arxiv.org/abs/2604.26886)

## Summary

This paper provides updated forecasts for HI galaxy distribution and clustering for future radio surveys, specifically the SKA-MID array. By analyzing outputs from S^3-SAX, GAEA, and IllustrisTNG simulations, the authors generate expected number counts as a function of redshift and sensitivity thresholds. They further utilize halo occupation distribution modeling to assess clustering behavior and the impact of sample variance, offering a refined outlook on the cosmological utility of 21cm galaxy spectroscopic surveys.

## Key Contributions

- Forecasts expected HI galaxy number counts and clustering properties for upcoming SKA-MID surveys using three distinct simulation suites (S^3-SAX, GAEA, IllustrisTNG).
- Quantifies the impact of modeling uncertainty on predicted HI galaxy distributions across different sensitivity cuts and redshift ranges.
- Applies a halo occupation distribution (HOD) model to characterize clustering and estimate sample variance in future survey sub-volumes.

## Open Questions & Future Work

- [[hi-galaxy-simulation-discrepancies]]

## Archivist Review

The paper provides forecasts for SKA-MID based on existing simulations rather than introducing novel methodologies or architectures that are inherently reusable across ML subfields. The identified open question regarding modeling discrepancies is significant enough for cosmologists to track, as it directly impacts the interpretability of upcoming large-scale survey data.

### Approved Open Questions
- Modeling Discrepancies in HI Surveys: Accurate predictions for HI galaxy distributions are critical for interpreting data from next-generation radio surveys; without resolving these modeling discrepancies, the reliability of inferred cosmological constraints, such as the expansion rate and growth factor, remains compromised by unquantified theoretical systematic errors.

### Rejected Candidates
- [dataset] S3-SAX (`s3-sax-simulation`) - paper_local: This is a specific simulation suite rather than a broadly reusable dataset or methodology.
- [concept] GAEA (`gaea-model`) - paper_local: This is a specific semi-analytic model implementation, not a generic reusable pattern.
- [dataset] IllustrisTNG (`illustristng-model`) - paper_local: This is an established hydrodynamical simulation framework used as an analysis tool rather than the contribution itself.

## Links

- [Abstract](https://arxiv.org/abs/2604.26886)
- [PDF](https://arxiv.org/pdf/2604.26886)

