---
# CSL-compatible fields
title: "Higher-order interactions in ecology can be hidden in plain sight"
author:
  - literal: "Violeta Calleja-Solanas"
  - literal: "Santiago Lamata-Otín"
  - literal: "Carlos Gómez-Ambrosi"
  - literal: "Jesús Gómez-Gardeñes"
  - literal: "Sandro Meloni"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06301"

# Custom fields
paper_id: "2605.06301"
paper_source: "arxiv"
domain: "time-series"
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
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:19:02Z"
created_at: "2026-05-10T05:19:02Z"
---

# Higher-order interactions in ecology can be hidden in plain sight

**Authors**: Violeta Calleja-Solanas, Santiago Lamata-Otín, Carlos Gómez-Ambrosi, Jesús Gómez-Gardeñes, Sandro Meloni
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06301](https://arxiv.org/abs/2605.06301)

## Summary

This paper investigates the fundamental limitations of inferring ecological interaction structures from abundance time-series data. The authors show that higher-order Lotka-Volterra dynamics can be accurately captured by effective pairwise models, leading to a mechanistic identifiability problem where different underlying processes generate indistinguishable temporal patterns. Consequently, relying solely on observational time-series data may result in misleading ecological interpretations, necessitating the integration of supplementary domain-specific ecological information.

## Key Contributions

- Demonstrates that higher-order Lotka-Volterra dynamics can be statistically mimicked by effective pairwise interaction models.
- Formally establishes a mechanistic identifiability problem where distinct underlying ecological interactions produce nearly identical time-series outputs.
- Proves that the topology of interaction networks cannot be reliably inferred from abundance time series alone without external mechanistic constraints.

## Open Questions & Future Work

- [[mechanistic-identifiability-of-ecological-hoi]]

## Archivist Review

The paper highlights a fundamental issue in time-series modeling where different causal mechanisms (pairwise vs. higher-order) produce indistinguishable data outputs. I have approved the open question regarding mechanistic identifiability, as it addresses a core limitation in causal discovery from observational time-series data. No new concepts were approved as the core contribution focuses on a negative result (the limit of inference) rather than a novel, reusable modeling architecture or representation.

### Approved Open Questions
- Mechanistic Identifiability of Ecological HOIs: This is a foundational problem because currently, model selection based solely on goodness-of-fit to time-series data is insufficient to claim the existence of higher-order interactions, which may be critical for predicting system responses to environmental stressors or interventions.

## Links

- [Abstract](https://arxiv.org/abs/2605.06301)
- [PDF](https://arxiv.org/pdf/2605.06301)

