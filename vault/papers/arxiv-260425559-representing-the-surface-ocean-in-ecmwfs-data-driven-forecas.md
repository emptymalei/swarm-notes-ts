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
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "aifs"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:15:43Z"
created_at: "2026-04-30T05:15:43Z"
---

# Representing the Surface Ocean in ECMWF's data-driven forecasting system AIFS

**Authors**: Sara Hahner, Lorenzo Zampieri, Jean-Raymond Bidlot, Philip Browne, Matthew Chantry, Mariana C. A. Clare, Harrison Cook, Peter Dueben, Rachel Furner, Sarah Keeley, Josh Kousal, Simon Lang, Christian Lessig, Gert Mertes, Kristian Mogensen, Gabriel Moldovan, Charles Pelletier, Florian Pinault, Ana Prieto Nemesio, Baudouin Raoult, Irina Sandu, Mario Santa Cruz, Jakob Schloer, Steffen Tietsche, Hao Zuo
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25559](https://arxiv.org/abs/2604.25559)

## Summary

This paper introduces an extension to the ECMWF's Artificial Intelligence Forecasting System (AIFS) to perform joint forecasting of atmospheric and surface-ocean states, including waves and sea ice. By moving away from separate numerical models for each component, the system learns atmospheric-oceanic correlations directly from data in a component-agnostic fashion. The authors address specific challenges in multi-scale temporal dynamics and data sparsity, demonstrating significant gains in medium-range forecast skill for marine variables and improved physical consistency under varied conditions.

## Key Contributions

- Extends the AIFS data-driven weather forecasting framework to jointly model atmosphere, surface ocean, ocean waves, and sea ice components.
- Achieves approximately one day of improvement in forecast skill for nearly all evaluated marine variables at medium-range lead times compared to traditional physics-based models.
- Demonstrates that component-agnostic joint learning of cross-component relationships enhances forecasting robustness to out-of-distribution initial conditions.

## Open Questions & Future Work

- [[predicting-trend-dominated-ocean-variables]]
- [[balancing-multicomponent-ml-models]]

## Key Concepts

- [[aifs]]: A data-driven, component-agnostic machine learning framework for medium-range atmospheric and surface ocean forecasting.

## Archivist Review

The AIFS framework is approved as a key advancement in component-agnostic earth system modeling. The identified open questions regarding trend-dominated variables and multicomponent model balancing represent significant, research-level bottlenecks for data-driven climate forecasting that extend beyond this specific study.

### Approved Concepts
- AIFS (Artificial Intelligence Forecasting System): Central framework for the study, representing a shift toward component-agnostic joint earth system modeling in machine learning weather forecasting.

### Approved Open Questions
- Predicting Trend-Dominated Ocean Variables: Correctly representing ocean state variables is critical for climate forecasting and oceanography. Understanding how to handle long-term climate trends in data-driven models is a key bottleneck for the field.
- Balancing Multicomponent ML Models: As machine learning models evolve into full Earth system models, reconciling the disparate data requirements and dynamic behaviors of different physical components is a primary research obstacle.

## Links

- [Abstract](https://arxiv.org/abs/2604.25559)
- [PDF](https://arxiv.org/pdf/2604.25559)

