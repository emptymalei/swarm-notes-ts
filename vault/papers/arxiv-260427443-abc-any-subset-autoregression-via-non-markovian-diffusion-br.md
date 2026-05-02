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
  - "time-series-forecasting"
  - "generative-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "any-subset-autoregression-abc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:08:35Z"
created_at: "2026-05-02T05:08:35Z"
---

# ABC: Any-Subset Autoregression via Non-Markovian Diffusion Bridges in Continuous Time and Space

**Authors**: Gabe Guo, Thanawat Sornwanee, Lutong Hao, Elon Litman, Stefano Ermon, Jose Blanchet
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27443](https://arxiv.org/abs/2604.27443)

## Summary

ABC is a generative framework for continuous-time, continuous-space stochastic processes that addresses limitations in standard diffusion models regarding physical plausibility and flexible conditioning. By modeling processes through a single continuous SDE with non-Markovian diffusion bridges, the model starts generation from previous states instead of uninformative noise. This approach allows for path-dependent conditioning on arbitrary subsets of time, facilitating irregular sampling and future-state constraints. ABC demonstrates improved performance over existing methods in video generation and weather forecasting by ensuring dynamics remain aligned with elapsed physical time.

## Key Contributions

- Introduces ABC, a continuous-time/space framework that uses non-Markovian diffusion bridges to perform autoregression from preceding states rather than Gaussian noise.
- Derives SDE dynamics via changes-of-measure, enabling flexible conditioning on arbitrary, irregularly sampled subsets of historical and future states.
- Achieves superior generation quality and physically plausible dynamics on video and weather forecasting tasks by scaling noise injection according to elapsed physical time.

## Open Questions & Future Work

- [[hybrid-ode-sde-sampling-continuous-time]]

## Key Concepts

- [[any-subset-autoregression-abc]]: A continuous-time, continuous-space generative modeling framework using non-Markovian diffusion bridges to enable autoregressive generation conditioned on any subset of states.

## Archivist Review

I have approved the Any-Subset Autoregression framework as a novel conditioning paradigm for continuous-time generative models and the open question regarding hybrid sampling schemes for their potential to address long-horizon, high-fidelity modeling bottlenecks. All other candidates were either too local to the specific implementation of this paper or already sufficiently represented in the vault.

### Approved Concepts
- Any-Subset Autoregression (ABC): The method overcomes traditional diffusion limitations by enabling path-dependent conditioning on arbitrary, irregular subsets of process states.

### Approved Open Questions
- Hybrid ODE-SDE sampling schemes: Efficient and structurally coherent sampling is essential for scaling continuous-time generative models to high-resolution spatiotemporal tasks.

## Links

- [Abstract](https://arxiv.org/abs/2604.27443)
- [PDF](https://arxiv.org/pdf/2604.27443)

