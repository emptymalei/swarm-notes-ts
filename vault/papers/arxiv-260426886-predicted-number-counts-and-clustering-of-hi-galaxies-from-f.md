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
domain: "astrophysics"
tags:
  []
architectures:
  []
datasets:
  - "s3-sax"
  - "gaea"
concept_slugs:
  - "halo-occupation-distribution-hod-model-fitting"
dataset_slugs:
  - "s3-sax"
  - "gaea"
skill: "GeneralMLSkill"
processed_at: "2026-05-02T05:09:22Z"
created_at: "2026-05-02T05:09:22Z"
---

# Predicted number counts and clustering of Hi galaxies from future radio surveys

**Authors**: Ainulnabilah Nasirudin, Philip Bull, Isabelle Ye
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26886](https://arxiv.org/abs/2604.26886)

## Summary

This paper provides updated predictions for the number counts and clustering of HI galaxies observable by future radio surveys like SKA-MID. By leveraging three diverse simulations—S$^3$-SAX, GAEA, and IllustrisTNG—the authors characterize the expected galaxy distribution and evaluate the corresponding cosmological survey performance. Furthermore, the study applies halo occupation distribution modeling to constrain clustering properties and estimate the sample variance critical for interpreting future survey data.

## Key Contributions

- Derived HI galaxy number counts for SKA-MID across varying sensitivity cuts and redshifts.
- Forecasted cosmological performance of proposed SKA-MID surveys using multi-simulation predictions.
- Quantified the impact of model uncertainty and sample variance on HI galaxy clustering predictions using HOD modeling.

## Open Questions & Future Work

- [[hi-galaxy-simulation-discrepancies-high-redshift]]

## Key Concepts

- [[halo-occupation-distribution-hod-model-fitting]]: A statistical framework for modeling galaxy distribution by connecting galaxy counts to dark matter halo mass.

## Archivist Review

I have approved the HOD fitting concept and the high-redshift HI simulation discrepancy open question, as they are central to the field's challenges in cosmology. I also approved two of the simulation catalogues as datasets to track these specific model-based sources. I rejected IllustrisTNG as it is an extremely well-known, foundational dataset in the field.

### Approved Concepts
- Halo Occupation Distribution (HOD) model fitting: Essential for linking dark matter simulations to observed galaxy clustering statistics in cosmological surveys.

### Approved Open Questions
- HI galaxy simulation discrepancies: This uncertainty hampers the ability to reliably forecast the sensitivity and cosmological utility of future large-scale HI surveys, potentially biasing cosmological parameter inference.

### Rejected Candidates
- [dataset] IllustrisTNG (`illustristng`) - duplicate_existing: This is a large-scale, well-established public cosmological simulation that is already represented in the broader scientific literature and does not require a new vault note.

## Datasets

- [[s3-sax]]
- [[gaea]]

## Links

- [Abstract](https://arxiv.org/abs/2604.26886)
- [PDF](https://arxiv.org/pdf/2604.26886)

