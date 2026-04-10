---
# CSL-compatible fields
title: "Controlling the rain fall statistics using Mean-Reverting Jump Diffusion model"
author:
  - literal: "Joya GhoshDastider"
  - literal: "D. Pal"
  - literal: "Pankaj Kumar Mishra"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08338"

# Custom fields
paper_id: "2604.08338"
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
processed_at: "2026-04-10T15:27:27Z"
created_at: "2026-04-10T15:27:27Z"
---

# Controlling the rain fall statistics using Mean-Reverting Jump Diffusion model

**Authors**: Joya GhoshDastider, D. Pal, Pankaj Kumar Mishra
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08338](https://arxiv.org/abs/2604.08338)

## Summary

This paper introduces a stochastic mean-reverting jump-diffusion framework designed to simulate high-resolution, intermittent rainfall time series. The model successfully captures complex phenomena such as superdiffusive dynamics, multifractal properties, and the occurrence of extreme events. By tuning model parameters, the authors demonstrate the ability to shift between Log-Normal and Gamma probability distributions, providing a versatile tool for generating realistic synthetic rainfall data. Extensive validation against regional rainfall data confirms the model's efficacy in reproducing dominant temporal scales observed in real-world measurements.

## Key Contributions

- Proposes a mean-reverting jump-diffusion model to simulate intermittent and extreme-event rainfall dynamics.
- Demonstrates the model's ability to reproduce multifractal features and superdiffusive behavior with an exponent of ~1.8.
- Enables systematic control over rainfall statistics, including transitions between Log-Normal and Gamma distributions and modulation of dry-patch durations.

## Open Questions & Future Work

- [[spatiotemporal-stochastic-rainfall-modeling]]

## Archivist Review

The paper applies a well-known class of stochastic models to a specific time-series domain (rainfall). I approved the open question regarding the extension of such temporal models to spatiotemporal domains, as this is a central challenge in climate informatics. No new concepts were approved as the model itself is established, and no new datasets were introduced.

### Approved Open Questions
- Spatio-temporal rainfall stochastic modeling: This question addresses a fundamental limitation in current temporal stochastic models regarding their generalization to regional spatiotemporal variability and non-stationary environmental shifts.

### Rejected Candidates
- [concept] Mean-Reverting Jump Diffusion Model (`mean-reverting-jump-diffusion-model`) - not_novel: This is a standard class of stochastic processes in quantitative finance and physics, not a novel contribution of this paper.

## Links

- [Abstract](https://arxiv.org/abs/2604.08338)
- [PDF](https://arxiv.org/pdf/2604.08338)

