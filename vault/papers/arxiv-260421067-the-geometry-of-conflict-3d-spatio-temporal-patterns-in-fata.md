---
# CSL-compatible fields
title: "The geometry of conflict : 3D Spatio-temporal patterns in fatalities prediction"
author:
  - literal: "Thomas Schincariol"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.21067"

# Custom fields
paper_id: "2604.21067"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "shapefinder"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:09:05Z"
created_at: "2026-04-24T05:09:05Z"
---

# The geometry of conflict : 3D Spatio-temporal patterns in fatalities prediction

**Authors**: Thomas Schincariol
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.21067](https://arxiv.org/abs/2604.21067)

## Summary

This paper presents a novel framework for predicting conflict fatalities by analyzing the 3D spatio-temporal diffusion patterns of past violence. By transforming fatality data at the Prio-Grid level into 3D patterns, the author adapts the ShapeFinder model to classify and match these trends using the Earth Movers Distance algorithm. This pattern-matching approach is shown to improve forecasting performance over the established Views ensemble benchmark. The findings underscore the importance of geometric pattern recognition in enhancing early warning systems for conflict dynamics.

## Key Contributions

- Introduces an innovative approach to transform conflict fatality data into 3D patterns at the Prio-Grid level for better diffusion analysis.
- Adapts the ShapeFinder model using Earth Movers Distance (EMD) to classify and match historical conflict patterns.
- Demonstrates that pattern-based conflict forecasting significantly outperforms the Views ensemble benchmark model in predictive accuracy.

## Open Questions & Future Work

- [[conflict-onset-detection-metrics]]

## Key Concepts

- [[shapefinder]]: A shape-based pattern recognition framework that classifies and matches 3D spatio-temporal structures using Earth Mover's Distance.

## Archivist Review

I approved ShapeFinder as it represents a distinct geometric pattern-matching framework for time-series forecasting, and the open question regarding onset detection metrics, as it captures a critical bottleneck in the utility of early warning systems. I rejected Earth Mover's Distance as it is a foundational technique rather than a novel research concept specific to this paper's contribution.

### Approved Concepts
- ShapeFinder: It serves as the core pattern-matching framework for identifying 3D spatio-temporal dynamics in diffusion processes.

### Approved Open Questions
- Conflict Onset Detection Metrics: This addresses a fundamental limitation in the practical utility of conflict forecasting models, shifting evaluation from generic accuracy to impact-driven early warning metrics.

### Rejected Candidates
- [concept] Earth Movers Distance (EMD) (`earth-movers-distance-emd`) - not_novel: EMD is a well-established mathematical tool and does not require a standalone vault entry in this context.

## Links

- [Abstract](https://arxiv.org/abs/2604.21067)
- [PDF](https://arxiv.org/pdf/2604.21067)

