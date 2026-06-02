---
# CSL-compatible fields
title: "TimeBlocks: Foundational and Continual Time-Series Blockbase -- Extended Version"
author:
  - literal: "David Campos"
  - literal: "Bin Yang"
  - literal: "Tung Kieu"
  - literal: "Lei Chen"
  - literal: "Chenjuan Guo"
  - literal: "Christian S. Jensen"
issued:
  date-parts:
    - [2026, 6, 1]
url: "https://arxiv.org/abs/2606.02142"

# Custom fields
paper_id: "2606.02142"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-inpainting-diffusion"
  - "regime-aware-specialist-routing"
  - "online-residual-correction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "timeblocks"
  - "streamcore"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-02T05:41:06Z"
created_at: "2026-06-02T05:41:06Z"
---

# TimeBlocks: Foundational and Continual Time-Series Blockbase -- Extended Version

**Authors**: David Campos, Bin Yang, Tung Kieu, Lei Chen, Chenjuan Guo, Christian S. Jensen
**Date**: 2026-06-01
**Paper ID**: [arxiv:2606.02142](https://arxiv.org/abs/2606.02142)

## Summary

TimeBlocks is a lightweight, foundational time-series framework designed for real-time stream processing, addressing the inefficiency of large-scale foundational models in constrained environments. The approach utilizes a pool of interchangeable model blocks combined with a routing strategy to dynamically construct models for specific tasks. To facilitate continual learning, the framework incorporates StreamCore, a method for maintaining a representative data approximation that supports efficient and ongoing model calibration.

## Key Contributions

- Introduces TimeBlocks, a modular architecture that constructs lightweight, task-specific models from an interchangeable blockbase.
- Develops StreamCore, a stream summarization method that enables efficient continual model calibration under strict computational constraints.
- Demonstrates that the proposed framework outperforms existing baselines across multiple time-series tasks and datasets while maintaining low overhead suitable for real-time applications.

## Key Concepts

- [[timeblocks]]: A foundational and continual framework that uses a pool of modular blocks and a routing strategy to construct task-specific, lightweight time-series models for streaming data.
- [[streamcore]]: A data summarization technique for streaming time-series that ensures a representative subset for continual model calibration.

## Archivist Review

The paper introduces two distinct, high-impact mechanisms for resource-constrained streaming time-series forecasting: a modular model-construction paradigm (TimeBlocks) and a stream summarization method (StreamCore) for continual calibration. These concepts are sufficiently novel and reusable to merit inclusion in the vault, while no new open questions or datasets met the strict selectivity criteria for standalone entries.

### Approved Concepts
- TimeBlocks: It is the core architectural contribution of the paper, enabling modular, lightweight, and task-adaptable time-series model construction.
- StreamCore: It solves the challenge of continual model calibration in data streams by maintaining a representative data core.

## Links

- [Abstract](https://arxiv.org/abs/2606.02142)
- [PDF](https://arxiv.org/pdf/2606.02142)

