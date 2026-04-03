---
# CSL-compatible fields
title: "Possible, Yes; Ignorant, Perhaps: A Scorecard for Possibilistic Forecasts"
author:
  - literal: "John R. Lawson"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02187"

# Custom fields
paper_id: "2604.02187"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "possibilistic-forecasting"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-03T05:18:54Z"
created_at: "2026-04-03T05:18:54Z"
---

# Possible, Yes; Ignorant, Perhaps: A Scorecard for Possibilistic Forecasts

**Authors**: John R. Lawson
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02187](https://arxiv.org/abs/2604.02187)

## Summary

This paper proposes a verification framework for possibilistic forecasts, addressing the limitation of probability distributions that are constrained to sum to unity. By using subnormal distributions, the framework introduces a formal 'ignorance' signal and a five-number scorecard to decompose forecast performance across dimensions like depth-of-truth, diffuseness, and conditional necessity. The methodology includes a conversion technique to map possibility to probability, facilitating integration with traditional categorical and frequency-based evaluation metrics. Through a case study on Storm Prediction Center convective outlooks, the paper demonstrates how this multi-faceted approach exposes failure modes that single-metric evaluations miss.

## Key Contributions

- Develops a formal verification framework for possibilistic forecasts, which allows for explicit representation of 'ignorance' via subnormal distributions.
- Introduces a five-number scorecard for diagnosing forecast performance based on depth-of-truth, diffuseness, support margin, ignorance, and conditional necessity.
- Establishes a possibility-to-probability conversion method that bridges possibilistic and probabilistic paradigms, enabling the use of standard frequency-based scoring.

## Open Questions & Future Work

- [[propriety-of-possibilistic-scorecards]]

## Key Concepts

- [[possibilistic-forecasting]]: A forecasting paradigm that utilizes subnormal distributions to explicitly quantify model ignorance.

## Archivist Review

I have approved the core concept of possibilistic forecasting as a valuable alternative to standard probability distributions for uncertainty modeling, and the open question regarding the propriety of these scorecards, as this is a fundamental theoretical gap. I rejected other minor sub-components of the scorecard mechanism as they are best understood as specific facets of the overarching framework.

### Approved Concepts
- Possibilistic Forecasting: Provides a formal alternative to standard probabilistic forecasting that explicitly models 'ignorance' by relaxing the unit-sum constraint.

### Approved Open Questions
- Propriety of Possibilistic Scorecards: Propriety is a fundamental requirement in forecast verification to ensure metrics incentivize truthful reporting rather than manipulation. Extending this to the possibilistic domain is essential for it to become a robust optimization standard.

## Links

- [Abstract](https://arxiv.org/abs/2604.02187)
- [PDF](https://arxiv.org/pdf/2604.02187)

