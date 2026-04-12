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
  - "quantum-reservoir-computing"
  - "time-series-forecasting"
  - "multivariate-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mixing-capacity"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-12T05:02:17Z"
created_at: "2026-04-12T05:02:17Z"
---

# Multivariate quantum reservoir computing with discrete and continuous variable systems

**Authors**: Tobias Fellner, Jonas Merklinger, Christian Holm
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08427](https://arxiv.org/abs/2604.08427)

## Summary

This paper addresses the limitation of quantum reservoir computing (QRC) in handling only univariate time series by developing a framework for multivariate data processing. It introduces three distinct multivariate encoding schemes and proposes a new 'mixing capacity' metric to evaluate how effectively reservoirs combine multiple data streams. The authors evaluate these methods on the chaotic Lorenz-63 system, finding that optimal performance requires task-specific input design and correlates with the presence of non-classical quantum resources.

## Key Contributions

- Establishes a comprehensive framework for multivariate data processing in quantum reservoir computing (QRC).
- Introduces the 'mixing capacity' metric to quantify the integration effectiveness of independent input streams within a reservoir.
- Demonstrates that optimal multivariate encoding schemes depend on the specific reservoir type (discrete vs. continuous) and task, highlighting the need for task-specific input design.

## Open Questions & Future Work

- [[theoretical-link-quantum-resources-computational-capacity]]
- [[multivariate-quantum-data-processing]]

## Key Concepts

- [[mixing-capacity]]: A metric for measuring how effectively a quantum reservoir combines multiple independent input data streams.

## Archivist Review

The concept 'mixing capacity' is a novel, reusable metric specifically designed for evaluating the integration of independent streams in quantum reservoirs and therefore merits inclusion. The two approved open questions identify substantial, long-term theoretical and architectural challenges in the development of quantum reservoir computing that extend well beyond the scope of this individual paper.

### Approved Concepts
- mixing capacity: The paper introduces this metric specifically to evaluate how well multivariate inputs are integrated in quantum reservoirs, which is a core challenge in multivariate QRC.

### Approved Open Questions
- Quantum resources-computational capacity link: Establishing this link is crucial for justifying the use of quantum reservoirs over classical ones by providing a mechanistic understanding of where quantum advantage originates.
- Multivariate quantum data processing: This is essential for the evolution of quantum reservoir computing into a natively quantum machine learning paradigm capable of processing quantum-coherent information.

## Links

- [Abstract](https://arxiv.org/abs/2604.08427)
- [PDF](https://arxiv.org/pdf/2604.08427)

