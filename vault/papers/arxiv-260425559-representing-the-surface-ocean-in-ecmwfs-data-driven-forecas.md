---
# CSL-compatible fields
title: "Representing the Surface Ocean in ECMWF's data-driven forecasting system AIFS"
author:
  - literal: "Sara Hahner"
  - literal: "Lorenzo Zampieri"
  - literal: "Jean-Raymond Bidlot"
  - literal: "Philip Browne"
  - literal: "Matthew Chantry"
  - literal: "Mariana C. A. Clare"
  - literal: "Harrison Cook"
  - literal: "Peter Dueben"
  - literal: "Rachel Furner"
  - literal: "Sarah Keeley"
  - literal: "Josh Kousal"
  - literal: "Simon Lang"
  - literal: "Christian Lessig"
  - literal: "Gert Mertes"
  - literal: "Kristian Mogensen"
  - literal: "Gabriel Moldovan"
  - literal: "Charles Pelletier"
  - literal: "Florian Pinault"
  - literal: "Ana Prieto Nemesio"
  - literal: "Baudouin Raoult"
  - literal: "Irina Sandu"
  - literal: "Mario Santa Cruz"
  - literal: "Jakob Schloer"
  - literal: "Steffen Tietsche"
  - literal: "Hao Zuo"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25559"

# Custom fields
paper_id: "2604.25559"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "weather-forecasting"
  - "multimodal-learning"
  - "coupled-modeling"
  - "data-driven-science"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:11:09Z"
created_at: "2026-04-29T05:11:09Z"
---

# Representing the Surface Ocean in ECMWF's data-driven forecasting system AIFS

**Authors**: Sara Hahner, Lorenzo Zampieri, Jean-Raymond Bidlot, Philip Browne, Matthew Chantry, Mariana C. A. Clare, Harrison Cook, Peter Dueben, Rachel Furner, Sarah Keeley, Josh Kousal, Simon Lang, Christian Lessig, Gert Mertes, Kristian Mogensen, Gabriel Moldovan, Charles Pelletier, Florian Pinault, Ana Prieto Nemesio, Baudouin Raoult, Irina Sandu, Mario Santa Cruz, Jakob Schloer, Steffen Tietsche, Hao Zuo
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25559](https://arxiv.org/abs/2604.25559)

## Summary

This paper presents an extension of ECMWF's AIFS (Artificial Intelligence Forecasting System) that shifts from traditional decoupled atmosphere-ocean modeling to a unified, component-agnostic machine learning framework. By jointly learning correlations across the atmosphere-ocean interface, the system improves medium-range forecast skill for marine variables by approximately one day compared to physics-based baselines. The methodology resolves specific challenges in coupled modeling, including multi-scale temporal dynamics and data gaps over land, while ensuring physical consistency in predictions.

## Key Contributions

- Extends the AIFS (Artificial Intelligence Forecasting System) to a coupled atmosphere-ocean framework, jointly modeling marine components like waves and sea ice without explicit component separation.
- Demonstrates that the joint modeling approach yields an improvement of approximately one day in medium-range forecast skill for marine variables over traditional physics-based models.
- Addresses design challenges in coupled data-driven modeling, including heterogeneous missing values over land and the use of loss scaling to enforce physical realism and handle multi-scale temporal dynamics.

## Open Questions & Future Work

- [[dataset-inconsistency-in-joint-training]]

## Archivist Review

The paper provides a strong practical demonstration of unified atmosphere-ocean data-driven modeling but offers limited conceptual innovation beyond the integration itself. I approved the question regarding dataset inconsistencies as it addresses a fundamental, recurring bottleneck in training multi-component neural Earth system models, while rejecting the other question as it is primarily a design decision rather than a technical obstacle. No standalone concepts were approved as the AIFS architecture and its variants are highly domain-specific and proprietary to ECMWF's operational pipeline.

### Approved Open Questions
- Dataset Inconsistency in Joint Training: This is a critical bottleneck for the development of high-fidelity, data-driven Earth system models, as performance gains from coupling can be overshadowed by inconsistencies in the underlying training data infrastructure.

### Rejected Candidates
- [open_question] Necessity of Explicit Marine Representation (`necessity-of-explicit-marine-representation`) - low_impact: This is a framing of the model's design scope rather than a technical research problem with a path toward resolution in the community.

## Links

- [Abstract](https://arxiv.org/abs/2604.25559)
- [PDF](https://arxiv.org/pdf/2604.25559)

