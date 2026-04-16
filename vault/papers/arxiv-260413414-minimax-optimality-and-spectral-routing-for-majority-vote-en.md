---
# CSL-compatible fields
title: "Minimax Optimality and Spectral Routing for Majority-Vote Ensembles under Markov Dependence"
author:
  - literal: "Ibne Farabi Shihab"
  - literal: "Sanjeda Akter"
  - literal: "Anuj Sharma"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13414"

# Custom fields
paper_id: "2604.13414"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-spectral-routing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:07:04Z"
created_at: "2026-04-16T05:07:04Z"
---

# Minimax Optimality and Spectral Routing for Majority-Vote Ensembles under Markov Dependence

**Authors**: Ibne Farabi Shihab, Sanjeda Akter, Anuj Sharma
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13414](https://arxiv.org/abs/2604.13414)

## Summary

This paper addresses the degradation of ensemble variance reduction when training data exhibits Markov dependence, a common issue in time-series and reinforcement learning. The authors establish a minimax lower bound for classification risk that scales with the mixing time of the underlying Markov process and demonstrate that standard uniform bagging is suboptimal. They propose Adaptive Spectral Routing, a novel partitioning strategy that leverages the Fiedler eigenvector of the data dependency graph to achieve the optimal minimax rate without requiring knowledge of the mixing time. Experimental results on synthetic, UCR archive, and Atari DQN ensemble tasks confirm the theoretical optimality of the proposed routing method.

## Key Contributions

- Derived an information-theoretic lower bound of Ω(√Tmix/n) for classification risk under stationary, reversible, geometrically ergodic Markov chains.
- Identified a √Tmix algorithmic gap between standard uniform bagging and the minimax rate for AR(1) processes.
- Introduced Adaptive Spectral Routing, which uses the Fiedler eigenvector of a dependency graph to achieve the minimax-optimal rate without prior knowledge of the mixing time (Tmix).

## Open Questions & Future Work

- [[ensemble-variance-finite-width-rl]]

## Key Concepts

- [[adaptive-spectral-routing]]: An ensemble partitioning technique using the empirical Fiedler eigenvector of a dependency graph to achieve minimax-optimal variance reduction under Markov dependence.

## Archivist Review

The paper provides a theoretically rigorous treatment of ensemble learning under Markov dependence. I approved the proposed 'Adaptive Spectral Routing' concept for its novelty and reusability across domains dealing with dependent data. I also approved the open question regarding ensemble variance in finite-width RL to track the necessary leap from theoretical linear regimes to practical neural network training. The UCR archive was rejected as a standard, generic benchmark.

### Approved Concepts
- Adaptive Spectral Routing: It is the novel algorithm introduced to bridge the theoretical minimax gap in ensemble learning under Markovian dependence.

### Approved Open Questions
- Ensemble variance in finite-width RL: Critical for bridging the gap between theoretical models and practical deep RL implementations where non-linear dynamics and non-stationary targets are prevalent.

### Rejected Candidates
- [dataset] UCR Archive (`ucr-archive`) - generic: The UCR Archive is a generic benchmark collection rather than a specific, novel dataset central to the core contribution of this paper.

## Links

- [Abstract](https://arxiv.org/abs/2604.13414)
- [PDF](https://arxiv.org/pdf/2604.13414)

