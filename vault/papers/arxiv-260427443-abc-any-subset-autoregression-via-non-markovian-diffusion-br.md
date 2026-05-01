---
# CSL-compatible fields
title: "ABC: Any-Subset Autoregression via Non-Markovian Diffusion Bridges in Continuous Time and Space"
author:
  - literal: "Gabe Guo"
  - literal: "Thanawat Sornwanee"
  - literal: "Lutong Hao"
  - literal: "Elon Litman"
  - literal: "Stefano Ermon"
  - literal: "Jose Blanchet"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27443"

# Custom fields
paper_id: "2604.27443"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "diffusion-models"
  - "stochastic-differential-equations"
  - "generative-modeling"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "any-subset-autoregression-abc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:23:29Z"
created_at: "2026-05-01T05:23:29Z"
---

# ABC: Any-Subset Autoregression via Non-Markovian Diffusion Bridges in Continuous Time and Space

**Authors**: Gabe Guo, Thanawat Sornwanee, Lutong Hao, Elon Litman, Stefano Ermon, Jose Blanchet
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27443](https://arxiv.org/abs/2604.27443)

## Summary

ABC is a generative framework for continuous-time, continuous-space stochastic processes that addresses the limitations of standard diffusion models in modeling temporal dynamics. By utilizing a single SDE where time and states track physical processes, ABC enables robust conditioning on arbitrary subsets of observations rather than rigid noise-to-data mapping. This approach ensures that noise injection is physically consistent with elapsed time and allows for flexible interpolation and extrapolation, outperforming existing methods in video generation and weather forecasting.

## Key Contributions

- ABC framework models continuous-time, continuous-space stochastic processes using a single SDE where the time variable and state align with real-world physical evolution.
- ABC enables flexible conditioning on arbitrary subsets of states (including historical and future observations) via path-dependent dynamics derived from change-of-measure.
- Introduces a path- and time-dependent extension of denoising score matching to ensure noise injection scales physically with elapsed time, improving dynamics over standard diffusion models.

## Open Questions & Future Work

- [[scalability-efficiency-continuous-time-generative-models]]

## Key Concepts

- [[any-subset-autoregression-abc]]: A generative framework that uses a single continuous-time SDE to allow flexible conditioning on arbitrary subsets of historical and future observations.

## Archivist Review

Approved the core ABC framework as a significant contribution to continuous-time generative modeling and identified a focused open question regarding the scalability and architectural efficiency of such models. Other candidate concepts were excluded to maintain the vault's focus on high-impact, reusable mechanistic insights.

### Approved Concepts
- Any-Subset Autoregression (ABC): Provides a principled framework for continuous-time generative modeling that moves beyond rigid noise-to-data mapping by allowing conditioning on arbitrary temporal subsets.

### Approved Open Questions
- Scalability of Continuous-Time Generative Models: Addresses critical scalability and sampling efficiency bottlenecks inherent in current diffusion-based continuous-time generative frameworks.

### Rejected Candidates
- [open_question] Future Directions for Continuous-Time Models (`future-directions-continuous-time-generative-models`) - other: The candidate is too broad and describes a list of disparate tasks rather than a singular, focused research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.27443)
- [PDF](https://arxiv.org/pdf/2604.27443)

