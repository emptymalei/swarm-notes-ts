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
processed_at: "2026-05-09T05:10:55Z"
created_at: "2026-05-09T05:10:55Z"
---

# Higher-order interactions in ecology can be hidden in plain sight

**Authors**: Violeta Calleja-Solanas, Santiago Lamata-Otín, Carlos Gómez-Ambrosi, Jesús Gómez-Gardeñes, Sandro Meloni
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06301](https://arxiv.org/abs/2605.06301)

## Summary

This paper investigates the limits of inferring ecological interaction structures from abundance time-series data. The authors demonstrate that higher-order Lotka-Volterra dynamics can be functionally indistinguishable from effective pairwise models, creating a mechanistic identifiability trap. Consequently, time-series data alone is insufficient to reconstruct the true ecological connectivity, necessitating the integration of multi-modal ecological data.

## Key Contributions

- Demonstrates that higher-order Lotka-Volterra dynamics can be accurately approximated by effective pairwise models, rendering higher-order interactions unidentifiable from time-series data alone.
- Identifies a fundamental mechanistic identifiability problem where distinct underlying ecological interaction mechanisms yield nearly identical dynamical outputs.
- Argues that complementary ecological information beyond simple abundance time series is essential for reliable interaction structure inference.

## Open Questions & Future Work

- [[mechanistic-identifiability-ecological-interactions]]

## Archivist Review

I have approved the open question regarding the mechanistic identifiability of ecological interactions, as it identifies a profound, non-trivial limitation in time-series modeling where predictive accuracy does not imply mechanistic truth. No new concepts were approved because the core phenomenon (model indistinguishability) is a well-known theoretical issue in dynamical systems, and no new datasets were introduced. The rejection policy was applied to maintain the vault's focus on reusable methodology and significant research gaps.

### Approved Open Questions
- Mechanistic Identifiability of Ecological Interactions: This is a central bottleneck in ecological modeling because it addresses the core issue of mechanistic identifiability. Without resolving this, researchers risk applying models that are predictively convenient but ecologically and mechanistically incorrect, particularly when predicting outcomes of perturbations like management actions or environmental changes.

## Links

- [Abstract](https://arxiv.org/abs/2605.06301)
- [PDF](https://arxiv.org/pdf/2605.06301)

