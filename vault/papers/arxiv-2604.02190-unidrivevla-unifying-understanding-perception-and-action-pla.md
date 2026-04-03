---
# CSL-compatible fields
title: "UniDriveVLA: Unifying Understanding, Perception, and Action Planning for Autonomous Driving"
author:
  - literal: "Yongkang Li"
  - literal: "Lijun Zhou"
  - literal: "Sixu Yan"
  - literal: "Bencheng Liao"
  - literal: "Tianyi Yan"
  - literal: "Kaixin Xiong"
  - literal: "Long Chen"
  - literal: "Hongwei Xie"
  - literal: "Bing Wang"
  - literal: "Guang Chen"
  - literal: "Hangjun Ye"
  - literal: "Wenyu Liu"
  - literal: "Haiyang Sun"
  - literal: "Xinggang Wang"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02190"

# Custom fields
paper_id: "2604.02190"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "autonomous-driving"
  - "vision-language-models"
  - "multi-task-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "expert-decoupling-driving-vlas"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:18:46Z"
created_at: "2026-04-03T05:18:46Z"
---

# UniDriveVLA: Unifying Understanding, Perception, and Action Planning for Autonomous Driving

**Authors**: Yongkang Li, Lijun Zhou, Sixu Yan, Bencheng Liao, Tianyi Yan, Kaixin Xiong, Long Chen, Hongwei Xie, Bing Wang, Guang Chen, Hangjun Ye, Wenyu Liu, Haiyang Sun, Xinggang Wang
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02190](https://arxiv.org/abs/2604.02190)

## Summary

UniDriveVLA addresses the trade-off between spatial perception and semantic reasoning in autonomous driving VLA models by employing a Mixture-of-Transformers architecture. The system uses an expert decoupling strategy to separate driving understanding, scene perception, and action planning, coordinated by a masked joint attention mechanism. Coupled with a sparse perception paradigm and a three-stage training strategy, UniDriveVLA demonstrates state-of-the-art results in both open-loop and closed-loop benchmarks while maintaining broad task versatility.

## Key Contributions

- Proposes UniDriveVLA, a unified architecture using Mixture-of-Transformers to decouple spatial perception and semantic reasoning tasks.
- Introduces a masked joint attention mechanism to effectively coordinate distinct driving experts.
- Achieves state-of-the-art performance in open-loop evaluation on nuScenes and closed-loop evaluation on Bench2Drive.

## Open Questions & Future Work

- [[reconciling-spatial-semantic-interference-vla]]

## Key Concepts

- [[expert-decoupling-driving-vlas]]: An architectural design that separates driving understanding, scene perception, and action planning experts to resolve the perception-reasoning conflict in Vision-Language-Action models.

## Archivist Review

I approved the expert decoupling concept as a reusable architectural approach for resolving multi-task interference in VLA models, and the open question regarding spatial-semantic conflict because it addresses a fundamental design trade-off in modern embodied AI. Other candidates like masked joint attention and specific benchmarks were rejected as they represent either routine implementation details or standard community resources rather than unique scientific contributions.

### Approved Concepts
- Expert Decoupling for Driving VLAs: It provides a structural architectural solution to the fundamental conflict between spatial perception and semantic reasoning in driving VLA models.

### Approved Open Questions
- Reconciling Spatial-Semantic Conflict in VLAs: This is a foundational challenge in modern end-to-end autonomous driving research, as the current trade-off between perception accuracy and semantic reasoning limits the deployment of truly unified VLA systems.

### Rejected Candidates
- [concept] Masked Joint Attention (`masked-joint-attention`) - subcomponent_of_broader_mechanism: This is a specific implementation subcomponent rather than a standalone architectural contribution.
- [concept] Sparse Perception Paradigm (`sparse-perception-paradigm`) - not_novel: Sparse perception is a broad field of study; here it is used as a local implementation detail for a specific VLA model.
- [dataset] nuScenes and Bench2Drive Benchmarks (`nuscenes-bench2drive`) - not_novel: These are standard, widely used benchmarks in the autonomous driving domain.

## Links

- [Abstract](https://arxiv.org/abs/2604.02190)
- [PDF](https://arxiv.org/pdf/2604.02190)

