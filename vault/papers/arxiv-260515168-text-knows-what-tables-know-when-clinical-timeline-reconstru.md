---
# CSL-compatible fields
title: "Text Knows What, Tables Know When: Clinical Timeline Reconstruction via Retrieval-Augmented Multimodal Alignment"
author:
  - literal: "Sayantan Kumar"
  - literal: "Shahriar Noroozizadeh"
  - literal: "Juyong Kim"
  - literal: "Jeremy C. Weiss"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15168"

# Custom fields
paper_id: "2605.15168"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "i2m4-benchmark"
concept_slugs:
  - "retrieval-augmented-multimodal-alignment"
dataset_slugs:
  - "i2m4-benchmark"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:22:18Z"
created_at: "2026-05-17T05:22:18Z"
---

# Text Knows What, Tables Know When: Clinical Timeline Reconstruction via Retrieval-Augmented Multimodal Alignment

**Authors**: Sayantan Kumar, Shahriar Noroozizadeh, Juyong Kim, Jeremy C. Weiss
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15168](https://arxiv.org/abs/2605.15168)

## Summary

This paper presents a retrieval-augmented multimodal alignment framework to address the temporal ambiguity in unstructured clinical narratives by leveraging the precise timestamps found in structured EHR data. The approach builds a temporal scaffold from clinical text, performs relative event placement, and refines the timeline through structured EHR record retrieval. Experiments on the i2m4 benchmark demonstrate that integrating these modalities significantly enhances the temporal accuracy and completeness of reconstructed patient trajectories compared to text-only methods.

## Key Contributions

- Introduces a graph-based multistep pipeline that constructs temporal scaffolds from clinical narratives and calibrates them with structured EHR evidence.
- Demonstrates that the proposed alignment method improves absolute timestamp accuracy (AULTC) and temporal concordance over unimodal baselines on the i2m4 benchmark.
- Quantifies the clinical importance of multimodal fusion by showing 34.8% of narrative events are missing from tabular EHR records.

## Open Questions & Future Work

- [[clinical-timeline-generalization-and-adaptation]]

## Key Concepts

- [[retrieval-augmented-multimodal-alignment]]: A framework for reconstructing clinical timelines by aligning semantically rich narrative text with temporally precise structured EHR data using retrieval.

## Archivist Review

Approved the central methodological contribution and a refined open question regarding timeline generalization. I consolidated the dataset into a specific benchmark name rather than the underlying generic MIMIC databases. I rejected the original open question candidate in favor of a more concise phrasing that better aligns with existing vault terminology.

### Approved Concepts
- Retrieval-Augmented Multimodal Alignment: Central novel method for combining unstructured clinical narratives with structured EHR data to improve temporal precision.

### Approved Open Questions
- Multimodal Timeline Generalization Limits: Understanding the generalizability of these methods is critical for moving from research-based phenotyping to hospital-wide temporal decision support.

### Rejected Candidates
- [open_question] Generalization of Multimodal Timeline Reconstruction (`clinical-timeline-generalization-scalability`) - duplicate_existing: Replaced with a more concise and canonical slug and title.

## Datasets

- [[i2m4-benchmark]]

## Links

- [Abstract](https://arxiv.org/abs/2605.15168)
- [PDF](https://arxiv.org/pdf/2605.15168)

