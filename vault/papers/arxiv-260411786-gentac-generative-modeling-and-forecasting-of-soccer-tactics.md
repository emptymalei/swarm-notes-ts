---
# CSL-compatible fields
title: "GenTac: Generative Modeling and Forecasting of Soccer Tactics"
author:
  - literal: "Jiayuan Rao"
  - literal: "Tianlin Gui"
  - literal: "Haoning Wu"
  - literal: "Yanfeng Wang"
  - literal: "Weidi Xie"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11786"

# Custom fields
paper_id: "2604.11786"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "tacbench"
concept_slugs:
  - "gentac"
dataset_slugs:
  - "tacbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:06:26Z"
created_at: "2026-04-15T05:06:26Z"
---

# GenTac: Generative Modeling and Forecasting of Soccer Tactics

**Authors**: Jiayuan Rao, Tianlin Gui, Haoning Wu, Yanfeng Wang, Weidi Xie
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11786](https://arxiv.org/abs/2604.11786)

## Summary

GenTac is a diffusion-based framework designed to model the stochastic, multi-agent nature of open-play soccer by treating tactics as a process involving both continuous player trajectories and discrete semantic events. By grounding spatial dynamics into a tactical event space, the model generates diverse, long-horizon future trajectories that maintain collective team structural consistency. Beyond forecasting, GenTac enables controllable counterfactual simulations and stylistic adaptation, successfully generalizing to other team sports like basketball and hockey. The framework is validated on the proposed TacBench, demonstrating robust performance in geometric accuracy, stylistic simulation, and tactical outcome prediction.

## Key Contributions

- Introduced GenTac, a diffusion-based generative framework that models soccer tactics as a stochastic process over multi-player trajectories and semantic events.
- Achieved superior geometric accuracy and structural consistency in long-horizon trajectory forecasting compared to deterministic methods.
- Demonstrated capability for controllable counterfactual simulations and stylistic adaptation across soccer leagues and diverse team sports including basketball and American football.
- Established TacBench, a new benchmark for evaluating multi-agent tactical forecasting and simulation performance.

## Key Concepts

- [[gentac]]: A diffusion-based generative framework for modeling multi-agent tactical dynamics by grounding spatial trajectories in discrete semantic event spaces.

## Archivist Review

Archivist review kept only candidates judged central to the paper and reusable across future work. Approved 1 concept(s), 0 open question(s), and 1 dataset(s), with 1 rejected candidate note(s).

### Approved Concepts
- GenTac: It introduces a novel approach for coupling continuous multi-agent spatial trajectories with discrete, high-level tactical event sequences within a diffusion-based framework.

### Rejected Candidates
- [dataset] TacBench (`tacbench`) - other: While I am approving it as a dataset, I have marked it here to clarify the review summary. Wait, the instructions require rejecting *rejected* candidates. Since I approved TacBench, I will not include it in the rejected list.

## Datasets

- [[tacbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.11786)
- [PDF](https://arxiv.org/pdf/2604.11786)

