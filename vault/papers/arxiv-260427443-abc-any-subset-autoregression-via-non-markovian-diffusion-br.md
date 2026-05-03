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
  - "conditional-generation"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "any-subset-autoregression-abc"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:15:22Z"
created_at: "2026-05-03T05:15:22Z"
---

# ABC: Any-Subset Autoregression via Non-Markovian Diffusion Bridges in Continuous Time and Space

**Authors**: Gabe Guo, Thanawat Sornwanee, Lutong Hao, Elon Litman, Stefano Ermon, Jose Blanchet
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27443](https://arxiv.org/abs/2604.27443)

## Summary

The paper introduces Any-Subset Autoregression (ABC), a novel framework for continuous-time, continuous-space stochastic processes that addresses limitations in standard diffusion models regarding physical timing and conditioning flexibility. By utilizing non-Markovian diffusion bridges and a single continual SDE, ABC anchors generation in physical time and allows for conditioning on arbitrary subsets of past and future states. The method incorporates a path- and time-dependent denoising score matching objective, outperforming existing generative baselines on video and weather forecasting tasks.

## Key Contributions

- Introduces ABC, a framework using non-Markovian diffusion bridges to model continuous-time, continuous-space stochastic processes.
- Achieves superior generation performance by modeling the SDE such that intermediate states track physical time, utilizing previous states as generation anchors instead of uninformative noise.
- Derives a path- and time-dependent extension of denoising score matching to allow conditioning on arbitrary subsets of past and future states.

## Open Questions & Future Work

- [[time-adaptive-volatility-sde]]
- [[scaling-any-subset-autoregression]]

## Key Concepts

- [[any-subset-autoregression-abc]]: A generative framework for continuous-time processes using non-Markovian diffusion bridges, allowing for conditioning on arbitrary subsets of past and future states.

## Archivist Review

I approved the ABC framework as a significant advancement in continuous-time generation that explicitly addresses non-Markovian bridge dynamics. I also approved two open questions that isolate the specific bottlenecks regarding time-adaptive volatility and the computational complexity of path-dependent history compression, which are critical for scaling such models. No datasets were approved as none were presented as novel benchmarks central to the paper's claims.

### Approved Concepts
- Any-Subset Autoregression (ABC): ABC provides a foundational shift in modeling continuous-time stochastic processes by allowing path-dependent, non-Markovian conditioning on arbitrary temporal subsets, overcoming standard diffusion limitations.

### Approved Open Questions
- Time-Adaptive Volatility in SDEs: Decoupling the generation process from fixed noise schedules is essential for achieving physically plausible dynamics in long-horizon forecasting and video synthesis.
- Efficient Conditioning for Any-Subset Autoregression: Bridging the computational gap between path-dependent conditioning and efficient inference is crucial for scaling continuous-time generative models to complex, high-resolution time-series data.

## Links

- [Abstract](https://arxiv.org/abs/2604.27443)
- [PDF](https://arxiv.org/pdf/2604.27443)

