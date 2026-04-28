---
# CSL-compatible fields
title: "Neyman Jackknife: Design-Based Variance Estimation for Causal Inference under Interference"
author:
  - literal: "Bryan Park"
  - literal: "Stefan Wager"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24017"

# Custom fields
paper_id: "2604.24017"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "neyman-jackknife"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:15:38Z"
created_at: "2026-04-28T05:15:38Z"
---

# Neyman Jackknife: Design-Based Variance Estimation for Causal Inference under Interference

**Authors**: Bryan Park, Stefan Wager
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24017](https://arxiv.org/abs/2604.24017)

## Summary

The paper introduces the Neyman Jackknife, a flexible, design-based framework for conservative variance estimation in causal inference contexts characterized by interference. By enabling the recomputation of target estimators under various treatment assignment subsets, the approach provides a universal blueprint for uncertainty quantification. The framework demonstrates robust performance, recovering classical estimators in standard settings while matching or exceeding specialized baselines in complex causal interference scenarios.

## Key Contributions

- Introduces the Neyman Jackknife, a flexible framework for conservative variance estimation in causal inference under interference.
- Demonstrates that the framework recovers established variance estimators like the Neyman estimator and Newey-West HAC under specific conditions.
- Provides experimental evidence that the general-purpose framework matches or outperforms application-specific variance estimation baselines.

## Open Questions & Future Work

- [[optimal-neyman-jackknife-parameter-selection]]

## Key Concepts

- [[neyman-jackknife]]: A general framework for conservative variance estimation in finite-population causal inference under interference by recomputing estimators with subsetted treatment assignments.

## Archivist Review

I have approved the Neyman Jackknife as a core methodological contribution to design-based causal inference, as it provides a reusable blueprint for variance estimation under interference. The corresponding open question regarding parameter selection is approved because it addresses the core tension between theoretical conservativeness and practical optimization in this framework. No further datasets or concepts were deemed central enough to warrant entry.

### Approved Concepts
- Neyman Jackknife: Provides a unified, design-based variance estimation framework for causal inference settings with interference.

### Approved Open Questions
- Optimal Neyman Jackknife parameters: This is crucial because the framework's effectiveness in real-world applications is highly sensitive to the chosen parameters, and the lack of a formal, guaranteed procedure for data-driven parameter selection limits the practical automation of the method.

## Links

- [Abstract](https://arxiv.org/abs/2604.24017)
- [PDF](https://arxiv.org/pdf/2604.24017)

