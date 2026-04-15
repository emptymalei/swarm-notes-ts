---
# CSL-compatible fields
title: "A unified data format for managing diabetes time-series data: DIAbetes eXchange (DIAX)"
author:
  - literal: "Elliott C. Pryor"
  - literal: "Marc D. Breton"
  - literal: "Anas El Fathi"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11944"

# Custom fields
paper_id: "2604.11944"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "diax-diabetes-exchange"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:05:51Z"
created_at: "2026-04-15T05:05:51Z"
---

# A unified data format for managing diabetes time-series data: DIAbetes eXchange (DIAX)

**Authors**: Elliott C. Pryor, Marc D. Breton, Anas El Fathi
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11944](https://arxiv.org/abs/2604.11944)

## Summary

The authors introduce DIAX (DIAbetes eXchange), a standardized JSON-based format aimed at unifying heterogeneous time-series data from diverse diabetes management devices like CGM and insulin delivery systems. By providing a common structure, DIAX facilitates better integration, reproducibility, and cross-dataset analysis in machine learning research. The accompanying open-source toolkit supports conversion and visualization, enabling researchers to leverage over 10 million patient-hours of standardized clinical data. DIAX serves as a translational framework that promotes interoperability without mandating specific data-sharing policies.

## Key Contributions

- Introduces DIAX, a unified, interoperable JSON-based format specifically designed for diabetes time-series data management.
- Provides a comprehensive open-source toolkit for dataset conversion and cross-format compatibility to support ML research pipelines.
- Demonstrates utility by standardizing over 10 million patient-hours of data across multiple major clinical diabetes datasets.

## Open Questions & Future Work

- [[standardizing-emerging-diabetes-data-streams]]

## Key Concepts

- [[diax-diabetes-exchange]]: A standardized, JSON-based schema for unifying heterogeneous diabetes time-series data across diverse monitoring and insulin delivery devices.

## Archivist Review

The paper presents a vital infrastructure contribution for clinical time-series data. I approved the DIAX format as a core concept due to its potential for widespread impact on data interoperability. I also approved an open question regarding the standardization of future physiological data streams, as this addresses a long-term sustainability challenge for the proposed format. Routine datasets mentioned in the paper were rejected as they are standard benchmarks rather than unique research products.

### Approved Concepts
- DIAbetes eXchange (DIAX): Addresses the fragmentation of heterogeneous clinical time-series data in diabetes research, which is a significant bottleneck for reproducible machine learning applications.

### Approved Open Questions
- Standardizing emerging diabetes data streams: Proactive standardization of emerging modalities is essential to maintain the long-term utility and interoperability of clinical datasets for holistic physiological modeling.

### Rejected Candidates
- [dataset] DCLP3 (`dclp3`) - not_novel: Routine dataset used for evaluation, not a novel contribution to the field.
- [dataset] DCLP5 (`dclp5`) - not_novel: Routine dataset used for evaluation, not a novel contribution to the field.

## Links

- [Abstract](https://arxiv.org/abs/2604.11944)
- [PDF](https://arxiv.org/pdf/2604.11944)

