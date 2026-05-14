---
# CSL-compatible fields
title: "Stable Attention Response for Reliable Precipitation Nowcasting"
author:
  - literal: "Penghui Wen"
  - literal: "Zexin Hu"
  - literal: "Sen Zhang"
  - literal: "Patrick Filippi"
  - literal: "Xiaogang Zhu"
  - literal: "Allen Benter"
  - literal: "Thomas Bishop"
  - literal: "Zhiyong Wang"
  - literal: "Kun Hu"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13181"

# Custom fields
paper_id: "2605.13181"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "SEVIR"
  - "MeteoNet"
concept_slugs:
  - "harecast"
dataset_slugs:
  - "sevir"
  - "meteonet"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:24:40Z"
created_at: "2026-05-14T05:24:40Z"
---

# Stable Attention Response for Reliable Precipitation Nowcasting

**Authors**: Penghui Wen, Zexin Hu, Sen Zhang, Patrick Filippi, Xiaogang Zhu, Allen Benter, Thomas Bishop, Zhiyong Wang, Kun Hu
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13181](https://arxiv.org/abs/2605.13181)

## Summary

This paper investigates the role of attention-response stability in precipitation nowcasting, identifying cross-sample energy variance as a significant factor in forecast unreliability. To mitigate this, the authors introduce HARECast, a head-wise regularization framework that constraints attention-response energy fluctuations across samples. The method is shown to be model-agnostic and achieves state-of-the-art results on the SEVIR and MeteoNet datasets, significantly improving predictive reliability.

## Key Contributions

- Identified cross-sample instability of attention-response energy as a primary source of unreliability in precipitation nowcasting.
- Established a theoretical lower bound on prediction error linked to cross-sample attention-response variability.
- Proposed HARECast, a generic regularization framework that reduces attention-head fluctuations to achieve state-of-the-art performance on SEVIR and MeteoNet benchmarks.

## Open Questions & Future Work

- [[online-attention-stability-nowcasting]]

## Key Concepts

- [[harecast]]: A regularization framework that minimizes cross-sample variance of attention-response energy to improve precipitation nowcasting reliability.

## Archivist Review

The concept of HARECast is approved as it introduces a novel regularization mechanism for stabilizing attention across samples, which is a reusable architectural improvement. The two datasets, SEVIR and MeteoNet, are accepted as standard benchmarks in the nowcasting literature. Finally, the open question on online stability is accepted because it highlights the transition from batch-dependent training objectives to real-world, streaming deployment requirements.

### Approved Concepts
- Head-wise Attention Response Energy-regulated framework (HARECast): Addresses cross-sample attention response instability as a source of forecast unreliability, providing a mechanism to stabilize attention heads across samples.

### Approved Open Questions
- Online Attention Stability: Crucial for moving attention-based precipitation nowcasting into real-time, online deployment scenarios where large-batch estimation is impossible.

## Datasets

- [[sevir]]
- [[meteonet]]

## Links

- [Abstract](https://arxiv.org/abs/2605.13181)
- [PDF](https://arxiv.org/pdf/2605.13181)

