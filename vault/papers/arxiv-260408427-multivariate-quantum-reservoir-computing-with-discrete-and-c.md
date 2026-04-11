---
# CSL-compatible fields
title: "Multivariate quantum reservoir computing with discrete and continuous variable systems"
author:
  - literal: "Tobias Fellner"
  - literal: "Jonas Merklinger"
  - literal: "Christian Holm"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08427"

# Custom fields
paper_id: "2604.08427"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "quantum-computing"
  - "reservoir-computing"
  - "multivariate-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mixing-capacity"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:43:40Z"
created_at: "2026-04-11T04:43:40Z"
---

# Multivariate quantum reservoir computing with discrete and continuous variable systems

**Authors**: Tobias Fellner, Jonas Merklinger, Christian Holm
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08427](https://arxiv.org/abs/2604.08427)

## Summary

This paper extends quantum reservoir computing (QRC) to multivariate time series by proposing and evaluating three novel data encoding schemes. To assess performance in this context, the authors introduce 'mixing capacity', a metric quantifying how effectively a reservoir integrates multiple input streams. Their analysis of discrete and continuous-variable systems on the Lorenz-63 chaotic prediction task reveals that input design must be task-specific and that optimal performance correlates with non-classical quantum effects.

## Key Contributions

- Proposes a unified framework for multivariate data processing within quantum reservoir computing (QRC).
- Introduces 'mixing capacity' as a specialized metric to quantify how effectively quantum reservoirs integrate multiple independent input streams.
- Demonstrates that optimal encoding strategies for multivariate data are highly dependent on the choice of quantum reservoir (discrete vs. continuous variable systems) and the target task.
- Empirically links peak computational performance on chaotic system prediction to the presence of non-classical quantum properties.

## Open Questions & Future Work

- [[theoretical-framework-qrc-capacity]]

## Key Concepts

- [[mixing-capacity]]: A metric designed to measure the effectiveness of a quantum reservoir in combining independent multivariate data streams.

## Archivist Review

I approved the 'mixing capacity' concept as it represents a novel, reusable evaluation metric specifically for the under-explored field of multivariate quantum reservoir computing. The open question regarding the theoretical framework for QRC capacity was also approved because it addresses a fundamental, long-standing bottleneck in the field, whereas the other proposed question was too generic. I rejected the Lorenz-63 dataset as it is a standard synthetic system, not a specialized or novel benchmark.

### Approved Concepts
- mixing capacity: It provides a quantifiable way to assess how well quantum reservoirs integrate multivariate temporal inputs, which is currently an under-explored area in QRC.

### Approved Open Questions
- Theoretical Framework for QRC Capacity: Establishing a theoretical foundation would transition QRC from an empirical paradigm to one with predictive design principles, allowing for the optimization of quantum resources to maximize computational power.

### Rejected Candidates
- [open_question] Matching Topologies and Encoding Schemes (`optimal-topology-encoding-matching`) - other: This is a broad, qualitative goal rather than a specific, trackable research question.

## Links

- [Abstract](https://arxiv.org/abs/2604.08427)
- [PDF](https://arxiv.org/pdf/2604.08427)

