---
# CSL-compatible fields
title: "Generative Adversarial Learning from Deterministic Processes"
author:
  - literal: "Joris C. Kühl"
  - literal: "Hanno Gottschalk"
issued:
  date-parts:
    - [2026, 5, 18]
url: "https://arxiv.org/abs/2605.18425"

# Custom fields
paper_id: "2605.18425"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "generative-adversarial-learning-from-deterministic-processes"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-19T05:27:58Z"
created_at: "2026-05-19T05:27:58Z"
---

# Generative Adversarial Learning from Deterministic Processes

**Authors**: Joris C. Kühl, Hanno Gottschalk
**Date**: 2026-05-18
**Paper ID**: [arxiv:2605.18425](https://arxiv.org/abs/2605.18425)

## Summary

This paper develops a theoretical framework for training generative adversarial networks (GANs) on data derived from chaotic dynamical systems, moving beyond the traditional independent and identically distributed (i.i.d.) assumption. Using an infinite-dimensional model of generative adversarial learning (GAL), the authors prove that these models can effectively learn the invariant distribution of a chaotic system from a single deterministic time series. They further provide explicit convergence rates for this process in terms of the Jensen-Shannon divergence, offering a formal explanation for the success of physical AI in non-i.i.d. contexts.

## Key Contributions

- Proves that GANs can learn the invariant distribution of chaotic dynamical systems from a single deterministic time series.
- Derives explicit convergence rates for GAL in terms of Jensen-Shannon divergence for chaotic systems.
- Provides a theoretical bridge between physical AI training on chaotic data and standard i.i.d.-based generative learning theory.

## Key Concepts

- [[generative-adversarial-learning-from-deterministic-processes]]: A theoretical framework demonstrating that generative adversarial models can recover invariant distributions of chaotic systems from deterministic trajectories.

## Archivist Review

The paper provides a significant theoretical contribution by grounding the training of GANs on chaotic dynamical systems within statistical learning theory, moving away from the standard i.i.d. assumption. This framework for learning invariant distributions from single deterministic trajectories is central to physical AI and generalizes well beyond this specific paper. No datasets or open questions were proposed, and none were extracted as they did not meet the archival threshold.

### Approved Concepts
- Generative Adversarial Learning from Deterministic Processes: Establishes a formal statistical learning foundation for training generative models on non-i.i.d. chaotic dynamical data, bridging physical AI and classical GAN theory.

### Rejected Candidates
- [concept] Generative Adversarial Learning (GAL) from Deterministic Processes (`generative-adversarial-learning-from-deterministic-processes`) - duplicate_existing: This candidate was approved as the primary concept of the paper.

## Links

- [Abstract](https://arxiv.org/abs/2605.18425)
- [PDF](https://arxiv.org/pdf/2605.18425)

