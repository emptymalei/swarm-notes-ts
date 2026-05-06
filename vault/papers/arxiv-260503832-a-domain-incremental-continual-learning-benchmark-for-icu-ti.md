---
# CSL-compatible fields
title: "A Domain Incremental Continual Learning Benchmark for ICU Time Series Model Transportability"
author:
  - literal: "Ryan King"
  - literal: "Conrad Krueger"
  - literal: "Ethan Veselka"
  - literal: "Tianbao Yang"
  - literal: "Bobak J. Mortazavi"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03832"

# Custom fields
paper_id: "2605.03832"
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
processed_at: "2026-05-06T05:11:23Z"
created_at: "2026-05-06T05:11:23Z"
---

# A Domain Incremental Continual Learning Benchmark for ICU Time Series Model Transportability

**Authors**: Ryan King, Conrad Krueger, Ethan Veselka, Tianbao Yang, Bobak J. Mortazavi
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03832](https://arxiv.org/abs/2605.03832)

## Summary

This paper addresses the challenge of clinical model transportability between hospitals with differing data distributions. The authors propose a domain incremental continual learning benchmark to evaluate how effectively models can adapt to new regional ICU data while retaining knowledge from previous domains. Their evaluation compares data replay and Elastic Weight Consolidation (EWC) as mechanisms to mitigate performance degradation during domain shifts in patient outcome prediction tasks.

## Key Contributions

- Introduces a domain incremental continual learning benchmark for assessing the transportability of ICU time series models across geographically diverse hospital regions.
- Formulates clinical model transportability as a domain incremental learning challenge to address measurement distribution shifts across healthcare facilities.
- Evaluates the efficacy of data replay and Elastic Weight Consolidation (EWC) in maintaining clinical predictive performance across shifting input data distributions.

## Open Questions & Future Work

- [[memory-less-clinical-continual-learning]]

## Archivist Review

I reviewed the proposal for a domain incremental continual learning benchmark for ICU data. The benchmark framing itself is deemed paper-local, while the open question regarding memory-less continual learning in clinical settings represents a substantial, non-trivial challenge that generalizes well beyond this specific study. I have rejected the benchmark as a concept because it focuses on a specific application domain without introducing a novel, reusable algorithmic core.

### Approved Open Questions
- Memory-less Clinical Continual Learning: This addresses a fundamental architectural conflict between standard continual learning benchmarks (which often rely on replay) and the reality of health data privacy.

### Rejected Candidates
- [concept] Domain Incremental Clinical Benchmark (`domain-incremental-clinical-benchmark`) - not_reusable: This is a benchmark-specific framing rather than a reusable core mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2605.03832)
- [PDF](https://arxiv.org/pdf/2605.03832)

