---
# CSL-compatible fields
title: "Rethinking Video Human-Object Interaction: Set Prediction over Time for Unified Detection and Anticipation"
author:
  - literal: "Yuanhao Luo"
  - literal: "Di Wen"
  - literal: "Kunyu Peng"
  - literal: "Ruiping Liu"
  - literal: "Junwei Zheng"
  - literal: "Yufan Chen"
  - literal: "Jiale Wei"
  - literal: "Rainer Stiefelhage"
issued:
  date-parts:
    - [2026, 4, 12]
url: "https://arxiv.org/abs/2604.10397"

# Custom fields
paper_id: "2604.10397"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "video-understanding"
  - "human-object-interaction"
  - "anticipation"
  - "forecasting"
architectures:
  []
datasets:
  - "detant-hoi-benchmark"
concept_slugs:
  - "hoi-da-framework"
dataset_slugs:
  - "detant-hoi-benchmark"
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:06:16Z"
created_at: "2026-04-14T05:06:16Z"
---

# Rethinking Video Human-Object Interaction: Set Prediction over Time for Unified Detection and Anticipation

**Authors**: Yuanhao Luo, Di Wen, Kunyu Peng, Ruiping Liu, Junwei Zheng, Yufan Chen, Jiale Wei, Rainer Stiefelhage
**Date**: 2026-04-12
**Paper ID**: [arxiv:2604.10397](https://arxiv.org/abs/2604.10397)

## Summary

This paper introduces a unified approach to video-based human-object interaction (HOI) by jointly learning detection and future anticipation. To address temporal misalignment issues in current benchmarks, the authors propose DETAnt-HOI, a corrected evaluation framework. The method, HOI-DA, models anticipation as residual transitions from current pair states, achieving significant improvements in long-horizon forecasting tasks. Results confirm that joint learning provides better structural constraints for pair-level video representation.

## Key Contributions

- Introduces DETAnt-HOI, a temporally corrected benchmark for robust multi-horizon HOI detection and anticipation.
- Proposes HOI-DA, a pair-centric framework that jointly models HOI detection and future anticipation via residual transitions.
- Demonstrates that joint learning of detection and anticipation acts as a structural constraint that improves long-horizon video representation learning.

## Open Questions & Future Work

- [[multi-scale-backbone-integration-video-hoi]]

## Key Concepts

- [[hoi-da-framework]]: A pair-centric HOI framework that models future interactions as residual transitions from current states to jointly perform detection and anticipation.

## Archivist Review

The review process prioritized the novel pair-centric residual transition framework and the identified benchmark. The open question regarding backbone integration was approved as it represents a significant, recurring bottleneck in vision-based forecasting architectures. Routine dataset mentions (VidHOI, Action Genome) were excluded as they are standard benchmarks, not original contributions.

### Approved Concepts
- HOI-DA Framework: It proposes a specific pair-centric modeling paradigm (residual transitions for future interaction forecasting) that improves long-horizon anticipation.

### Approved Open Questions
- Multi-scale Backbone Integration: Understanding how to effectively integrate backbone hierarchies is critical for scaling performance in unified detection and anticipation models.

### Rejected Candidates
- [concept] DETAnt-HOI Benchmark (`detant-hoi-benchmark`) - subcomponent_of_broader_mechanism: This is better classified as a dataset or benchmark rather than a standalone architectural concept.

## Datasets

- [[detant-hoi-benchmark]]

## Links

- [Abstract](https://arxiv.org/abs/2604.10397)
- [PDF](https://arxiv.org/pdf/2604.10397)

