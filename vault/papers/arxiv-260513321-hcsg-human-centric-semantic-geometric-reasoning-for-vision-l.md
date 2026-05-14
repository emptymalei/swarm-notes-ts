---
# CSL-compatible fields
title: "HCSG: Human-Centric Semantic-Geometric Reasoning for Vision-Language Navigation"
author:
  - literal: "Haoxuan Xu"
  - literal: "Tianfu Li"
  - literal: "Wenbo Chen"
  - literal: "Yi Liu"
  - literal: "Jin Wu"
  - literal: "Huashuo Lei"
  - literal: "Yunfan Lou"
  - literal: "Lujia Wang"
  - literal: "Hesheng Wang"
  - literal: "Haoang Li"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13321"

# Custom fields
paper_id: "2605.13321"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "navigation"
  - "vision-language-models"
  - "human-robot-interaction"
architectures:
  []
datasets:
  - "HA-VLNCE"
concept_slugs:
  - "human-centric-semantic-geometric-reasoning"
dataset_slugs:
  - "ha-vlnce"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:24:17Z"
created_at: "2026-05-14T05:24:17Z"
---

# HCSG: Human-Centric Semantic-Geometric Reasoning for Vision-Language Navigation

**Authors**: Haoxuan Xu, Tianfu Li, Wenbo Chen, Yi Liu, Jin Wu, Huashuo Lei, Yunfan Lou, Lujia Wang, Hesheng Wang, Haoang Li
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13321](https://arxiv.org/abs/2605.13321)

## Summary

Vision-Language Navigation (VLN) models often struggle in dynamic environments populated by humans, typically treating them only as obstacles. This paper introduces HCSG, a human-centric framework that explicitly reasons about human behavior by combining geometric trajectory forecasting and semantic intention interpretation from Vision-Language Models. By fusing these insights into the robot's topological map and enforcing a social distance constraint, HCSG improves navigation safety and effectiveness. The approach demonstrates significant performance gains on the HA-VLNCE benchmark, validating its efficacy in complex, human-robot indoor settings.

## Key Contributions

- Proposes HCSG, a human-centric VLN framework that integrates geometric human forecasting and semantic action interpretation for socially intelligent navigation.
- Introduces a social distance loss to enforce compliant interaction distances in dynamic indoor environments.
- Achieves a 14% improvement in Success Rate and 34% reduction in Collision Rate on the HA-VLNCE benchmark compared to state-of-the-art methods.

## Open Questions & Future Work

- [[continuous-streaming-vln-bottleneck]]
- [[adaptive-social-distance-priors]]

## Key Concepts

- [[human-centric-semantic-geometric-reasoning]]: A framework for embodied navigation that integrates human trajectory forecasting and VLM-based action interpretation into a topological map for socially compliant planning.

## Archivist Review

The framework HCSG is approved for its distinct paradigm of semantic-geometric fusion in navigation, a key advancement over traditional obstacle-avoidance approaches. The HA-VLNCE dataset is approved as a central benchmark for this subfield. The two open questions are approved as they address fundamental bottlenecks in navigation efficiency (streaming) and social behavior modeling (adaptivity).

### Approved Concepts
- Human-Centric Semantic-Geometric Reasoning: Shifts the navigation paradigm from passive obstacle avoidance to active human behavior interpretation by explicitly fusing semantic and geometric cues into topological maps.

### Approved Open Questions
- Continuous Streaming VLN Bottleneck: The stop-and-wait bottleneck limits navigation efficiency, introduces artificial latency, and hinders the scaling of VLN to truly dynamic, fluid indoor settings.
- Adaptive Social Distance Priors: Static distance constraints fail to generalize across diverse social contexts, necessitating development of dynamic priors conditioned on high-dimensional semantic human behavior.

## Datasets

- [[ha-vlnce]]

## Links

- [Abstract](https://arxiv.org/abs/2605.13321)
- [PDF](https://arxiv.org/pdf/2605.13321)

