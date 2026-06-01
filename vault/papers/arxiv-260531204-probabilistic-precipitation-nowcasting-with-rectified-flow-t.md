---
# CSL-compatible fields
title: "Probabilistic Precipitation Nowcasting with Rectified Flow Transformers"
author:
  - literal: "Johannes Schusterbauer"
  - literal: "Jannik Wiese"
  - literal: "Nick Stracke"
  - literal: "Timy Phan"
  - literal: "Björn Ommer"
issued:
  date-parts:
    - [2026, 5, 29]
url: "https://arxiv.org/abs/2605.31204"

# Custom fields
paper_id: "2605.31204"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "freud-frame-wise-encoder-united-decoder"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-01T05:44:36Z"
created_at: "2026-06-01T05:44:36Z"
---

# Probabilistic Precipitation Nowcasting with Rectified Flow Transformers

**Authors**: Johannes Schusterbauer, Jannik Wiese, Nick Stracke, Timy Phan, Björn Ommer
**Date**: 2026-05-29
**Paper ID**: [arxiv:2605.31204](https://arxiv.org/abs/2605.31204)

## Summary

FREUD is a novel architecture for high-resolution precipitation nowcasting that replaces traditional deterministic compression with an uncertainty-preserving, frame-wise encoder and unified video decoder. By leveraging rectified flow transformers within this framework, the model efficiently handles complex spatio-temporal dynamics while capturing aleatoric uncertainty. Evaluated on the SEVIR benchmark, FREUD achieves state-of-the-art accuracy and demonstrates significant improvements through both model scaling and test-time inference strategies.

## Key Contributions

- Introduces FREUD, a novel frame-wise encoder and united decoder architecture that avoids deterministic compression bottlenecks.
- Utilizes rectified flow transformers to enable efficient, uncertainty-preserving spatio-temporal weather forecasting.
- Achieves state-of-the-art performance on the SEVIR precipitation nowcasting benchmark, with additional gains via model and test-time scaling.

## Key Concepts

- [[freud-frame-wise-encoder-united-decoder]]: A frame-wise encoder and unified decoder architecture using rectified flow transformers for uncertainty-preserving spatio-temporal data compression.

## Archivist Review

I have approved the FREUD architecture as a representative concept of uncertainty-preserving spatio-temporal data compression using rectified flow transformers. The SEVIR dataset is already in the vault, so it was not re-added. No open questions were identified that met the criteria for a permanent research note.

### Approved Concepts
- FREUD (Frame-wise Encoder and United Decoder): It explicitly addresses the limitation of deterministic compression in weather forecasting by proposing an uncertainty-preserving frame-wise encoder and unified decoder.

### Rejected Candidates
- [concept] FREUD (`freud-frame-wise-encoder-united-decoder`) - subcomponent_of_broader_mechanism: The candidate is essentially a specific model architecture; I am approving the architectural pattern/concept name instead.

## Links

- [Abstract](https://arxiv.org/abs/2605.31204)
- [PDF](https://arxiv.org/pdf/2605.31204)

