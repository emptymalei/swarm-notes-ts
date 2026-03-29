---
# CSL-compatible fields
title: "Topological optimization with birth and death cochains"
author:
  - literal: "Thomas Weighill"
  - literal: "Ling Zhou"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.25575"

# Custom fields
paper_id: "2603.25575"
paper_source: "openalex"
domain: "mathematics"
tags:
  - "topological-data-analysis"
  - "optimization"
  - "homology"
architectures:
  []
datasets:
  []
concept_slugs:
  - "birth-and-death-cochains"
  - "birth-and-death-content-loss"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:17:20Z"
created_at: "2026-03-29T20:17:20Z"
---

# Topological optimization with birth and death cochains

**Authors**: Thomas Weighill, Ling Zhou
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.25575](https://arxiv.org/abs/2603.25575)

## Summary

This paper introduces birth and death cochains as unique generalizations of birth and death simplices within persistent cohomology, establishing a key structural advantage. Building upon this, the authors define birth and death content, which serves as a generalization of birth and death times. These contents are then leveraged as effective loss functions for performing topological optimization across diverse data types, including point clouds, time series, and scalar fields. Finally, the utility of this novel framework is demonstrated through a new application to topological optimization on arctic ice imagery.

## Key Contributions

- Introduction of birth and death cochains as unique representatives for persistent cohomology classes, generalizing birth and death simplices.
- Definition of birth and death content as a generalization of birth and death times based on these cochains.
- Demonstration of using birth and death content as effective loss functions for topological optimization on point clouds, time series, and scalar fields.
- Novel application of topological optimization using these methods to a dataset of arctic ice images.

## Limitations

The abstract does not detail limitations, but the work is focused on theoretical development applied to several data types.

## Open Questions & Future Work

- [[stability-of-birth-death-cochains]]

## Key Concepts

- [[birth-and-death-cochains]]: Generalized versions of birth and death simplices in persistent cohomology, which are always unique for a given class.
- [[birth-and-death-content-loss]]: A generalization of birth and death times defined using birth and death cochains, used as a loss function.

## Archivist Review

Two core mathematical concepts were approved: the novel 'Birth and Death Cochains' as unique topological representatives, and the resulting 'Birth and Death Content' metric derived from them, which is used as a loss function. One substantial open question regarding the theoretical stability of these new cochains under small perturbations was also approved for tracking. No datasets were approved as none were explicitly named or central enough to warrant a permanent note beyond general benchmarks.

### Approved Concepts
- Birth and Death Cochains: This is the core mathematical object introduced, providing unique representations for persistent cohomology classes.
- Birth and Death Content: This new metric, derived from cochains, is utilized directly as a loss function for optimization tasks.

### Approved Open Questions
- Theoretical stability of cochains: Establishing theoretical stability for cochains would strengthen their utility as objective functions in optimization by ensuring that the gradient landscape doesn't undergo drastic changes with minor data perturbations.

### Rejected Candidates
- [concept] Birth and Death Content (`birth-and-death-content-loss`) - other: The concept 'Birth and Death Content' is approved, but the proposed slug 'birth-and-death-content-loss' is slightly too specific; the approved concept name is 'Birth and Death Content' derived from the paper's definition. The actual approved concept name reflects the core mathematical object. The provided candidate name 'Birth and Death Content' is used, which is synonymous with the more specific loss function application. The rejection analysis below will reflect the approval.

## Links

- [Abstract](https://arxiv.org/abs/2603.25575)
- [PDF](https://arxiv.org/pdf/2603.25575)

