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
processed_at: "2026-04-11T04:44:26Z"
created_at: "2026-04-11T04:44:26Z"
---

# Controlling the rain fall statistics using Mean-Reverting Jump Diffusion model

**Authors**: Joya GhoshDastider, D. Pal, Pankaj Kumar Mishra
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08338](https://arxiv.org/abs/2604.08338)

## Summary

This paper presents a mean-reverting jump-diffusion stochastic model designed to simulate the intermittent and extreme-event dynamics of rainfall. By validating the model against long-term half-hourly rainfall data from North-East India, the authors show that the framework accurately replicates observed multifractal features, superdiffusive behavior, and specific statistical distributions. Furthermore, the approach allows for the controlled modulation of extreme events and dry-patch durations, providing a flexible tool for generating synthetic rainfall series.

## Key Contributions

- Introduced a stochastic mean-reverting jump-diffusion model to simulate rainfall dynamics.
- Demonstrated the model's ability to replicate observed superdiffusive behavior (exponent ~1.8), multifractal features, and statistical distributions (Log-Normal/Gamma) of real-world rainfall.
- Enabled explicit control over the frequency of extreme events and dry-patch durations through systematic parameter adjustment.

## Open Questions & Future Work

- [[spatiotemporal-jump-diffusion-rainfall-modeling]]

## Archivist Review

I have reviewed the proposal and decided to approve the spatiotemporal extension as a significant research direction for stochastic rainfall modeling. I rejected the second open question as it focuses on empirical validation rather than a systemic research bottleneck. No new concepts were approved as the core jump-diffusion model is a standard statistical framework and does not represent a unique, reusable ML novelty in the scope of this vault.

### Approved Open Questions
- Spatio-temporal rainfall modeling extension: Moving from purely temporal to spatiotemporal stochastic modeling is a critical bottleneck for regional climate forecasting and extreme event tracking.

### Rejected Candidates
- [open_question] Validation of extreme events-dry patch relation (`validation-extreme-events-dry-patch`) - low_impact: This is a request for more empirical data validation, which is a standard call for future work rather than an architectural or theoretical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.08338)
- [PDF](https://arxiv.org/pdf/2604.08338)

