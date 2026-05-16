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
  - "medical-imaging-parsing"
  - "llm-assisted-fmu-testing"
  - "sequence-to-point-knowledge-distillation"
architectures:
  []
datasets:
  - "mimic-iii"
  - "mimic-iv"
concept_slugs:
  - "retrieval-augmented-multimodal-alignment"
dataset_slugs:
  - "mimic-iii"
  - "mimic-iv"
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:10:38Z"
created_at: "2026-05-16T05:10:38Z"
---

# Text Knows What, Tables Know When: Clinical Timeline Reconstruction via Retrieval-Augmented Multimodal Alignment

**Authors**: Sayantan Kumar, Shahriar Noroozizadeh, Juyong Kim, Jeremy C. Weiss
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15168](https://arxiv.org/abs/2605.15168)

## Summary

This paper addresses the challenge of clinical timeline reconstruction by integrating unstructured narrative text with precise structured EHR data. The authors propose a graph-based multistep approach that uses structured EHR entries as temporal evidence to calibrate timestamps extracted from clinical narratives. Empirical results on the i2m4 benchmark (MIMIC-III and MIMIC-IV) show that this multimodal alignment significantly improves temporal precision compared to text-only methods without compromising event coverage.

## Key Contributions

- Introduced a retrieval-augmented multimodal alignment framework that improves absolute timestamp accuracy (AULTC) in clinical timelines.
- Formulated clinical timeline reconstruction as a multistep graph-based process using structured EHR data as temporal anchors for narrative events.
- Demonstrated that 34.8% of clinically relevant events are absent in structured records, highlighting the necessity of multimodal alignment for patient trajectory modeling.

## Open Questions & Future Work

- [[clinical-timeline-generalization-and-adaptation]]

## Key Concepts

- [[retrieval-augmented-multimodal-alignment]]: A framework that integrates clinical text with structured EHR data using retrieval to improve the accuracy of reconstructed patient timelines.

## Archivist Review

The submission introduced a retrieval-augmented multimodal alignment concept and identified a substantial open question regarding the modularity and generalizability of clinical timeline reconstruction. The datasets MIMIC-III and MIMIC-IV are standard in this domain and are approved for their central role in the benchmark evaluation. No other concepts or open questions met the bar for long-term significance.

### Approved Concepts
- Retrieval-Augmented Multimodal Alignment: Provides a novel mechanism for integrating unstructured clinical narratives with structured EHR data to resolve temporal ambiguity.

### Approved Open Questions
- Generalizing Clinical Timeline Reconstruction: Understanding the generalizability and modularity of the proposed multistep reconstruction pipeline is critical for healthcare informatics where documentation styles vary across clinical settings.

## Datasets

- [[mimic-iii]]
- [[mimic-iv]]

## Links

- [Abstract](https://arxiv.org/abs/2605.15168)
- [PDF](https://arxiv.org/pdf/2605.15168)

