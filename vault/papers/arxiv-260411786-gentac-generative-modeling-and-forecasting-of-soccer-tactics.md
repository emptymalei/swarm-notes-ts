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
  - "trajectory-prediction"
  - "generative-modeling"
  - "multi-agent-systems"
  - "diffusion-models"
  - "counterfactual-reasoning"
architectures:
  []
datasets:
  - "TacBench"
concept_slugs:
  - "gentac"
dataset_slugs:
  - "tacbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:01:56Z"
created_at: "2026-04-14T05:01:56Z"
---

# GenTac: Generative Modeling and Forecasting of Soccer Tactics

**Authors**: Jiayuan Rao, Tianlin Gui, Haoning Wu, Yanfeng Wang, Weidi Xie
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11786](https://arxiv.org/abs/2604.11786)

## Summary

GenTac is a diffusion-based generative framework designed to model open-play soccer tactics as a stochastic process, overcoming the limitations of deterministic trajectory forecasting. By conditioning on diverse contexts such as team styles and strategic objectives, the model simulates plausible, long-horizon multi-agent trajectories grounded in a discrete tactical event space. The framework provides robust counterfactual simulation capabilities and reliably predicts tactical outcomes, showing strong generalization potential across multiple dynamic team sports.

## Key Contributions

- Introduces GenTac, a diffusion-based framework that models soccer tactics by jointly learning continuous multi-player trajectories and discrete 15-class tactical events.
- Achieves high geometric accuracy and structural consistency while enabling fine-grained control over stylistic team/league behavior and strategic objectives.
- Demonstrates controllable counterfactual simulation capabilities by modifying expected threat metrics through specific offensive or defensive guidance.
- Evaluated on the newly proposed TacBench benchmark and shown to generalize across various dynamic team sports including basketball, American football, and ice hockey.

## Key Concepts

- [[gentac]]: A diffusion-based generative framework for modeling multi-agent team sports as a stochastic process over continuous trajectories and discrete tactical events.

## Archivist Review

I approved the GenTac framework because it introduces a distinct, diffusion-based approach for modeling multi-agent interactions as coupled continuous-discrete processes, which is a significant advancement in sports trajectory forecasting. I rejected the TacBench dataset to adhere to the instruction of strict scarcity, preferring to focus on the methodological contribution of the framework. No open questions were identified that represented substantial, long-term research bottlenecks beyond the standard pursuit of performance and generalization.

### Approved Concepts
- GenTac: GenTac provides a novel approach to modeling complex, stochastic multi-agent interactions in sports by jointly learning continuous trajectories and discrete tactical events.

### Rejected Candidates
- [dataset] TacBench (`tacbench`) - low_impact: The instructions state to be scarce for datasets and prioritize the framework concept; as a proprietary benchmark specific to this paper, it is less critical than the modeling framework itself.

## Datasets

- [[tacbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.11786)
- [PDF](https://arxiv.org/pdf/2604.11786)

