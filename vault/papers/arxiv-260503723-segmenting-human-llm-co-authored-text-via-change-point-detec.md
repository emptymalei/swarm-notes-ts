---
# CSL-compatible fields
title: "Segmenting Human-LLM Co-authored Text via Change Point Detection"
author:
  - literal: "Mengchu Li"
  - literal: "Jin Zhu"
  - literal: "Jinglai Li"
  - literal: "Chengchun Shi"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03723"

# Custom fields
paper_id: "2605.03723"
paper_source: "arxiv"
domain: "nlp"
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
processed_at: "2026-05-06T05:11:55Z"
created_at: "2026-05-06T05:11:55Z"
---

# Segmenting Human-LLM Co-authored Text via Change Point Detection

**Authors**: Mengchu Li, Jin Zhu, Jinglai Li, Chengchun Shi
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03723](https://arxiv.org/abs/2605.03723)

## Summary

The proliferation of LLM-generated content necessitates fine-grained authentication beyond simple binary classification. This paper frames the localization of human-written versus machine-generated segments as a change point detection problem. By adapting time-series change point techniques to account for heterogeneous score variability, the authors provide a robust and theoretically grounded approach for segmenting co-authored texts. Empirical results demonstrate that the proposed method outperforms existing baselines in accuracy and localization capability.

## Key Contributions

- Formulates the task of segmenting human-LLM co-authored text as a change point detection problem in time-series analysis.
- Develops weighted and generalized change point detection algorithms specifically adapted to accommodate varying detection score heterogeneity.
- Provides a theoretical framework establishing the minimax optimality of the proposed segmentation procedures.

## Open Questions & Future Work

- [[temporal-dependence-heavy-tails-cpd]]

## Archivist Review

The paper proposes a clever framing of text segmentation as a change point detection problem. I approved the open question regarding the theoretical limitations of current assumptions (independence/sub-Gaussianity) as this is a high-level research direction applicable to both time-series and sequence segmentation. The core concept was rejected as it describes an application instance rather than a novel reusable primitive.

### Approved Open Questions
- Relaxing assumptions in co-authored text segmentation: Relaxing these assumptions is essential to move beyond controlled experimental settings into practical document analysis where text naturally exhibits strong dependencies and varying score reliability.

### Rejected Candidates
- [concept] Human-LLM segmentation via change point detection (`human-llm-segmentation-via-cpd`) - not_novel: This is an application-specific framing of an existing technique (change point detection) rather than a novel, reusable mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2605.03723)
- [PDF](https://arxiv.org/pdf/2605.03723)

