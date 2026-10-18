---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TimeCap: A Scalable Open-Source Pipeline for Captioning Wearable Health Time-Series Data"
description: "This paper introduces TimeCap, a scalable and deterministic open-source pipeline for captioning wearable health time-series data without using a language model in the loop for generation. By using tiered extractors and a synthesis layer, TimeCap ensures that captions are reproducible and signal-grounded, addressing the auditability and scaling issues of LLM-based annotation. The authors use this pipeline to create MHCap, a dataset of over 7 million captions for 19 Apple HealthKit channels, and demonstrate that a Time-Series Language Model (OpenTSLM) trained on this data outperforms traditional label-based baselines in 29 of 32 health-outcome prediction benchmarks."
resource: "https://arxiv.org/abs/2610.21274"
tags:
  - "time-series"
  - "healthcare"
  - "wearable-sensing"
  - "digital-biomarker"
  - "large-language-models"
  - "evaluation-benchmark"
  - "data-augmentation"
  - "reproducibility"
timestamp: "2026-10-18T00:23:24Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Max Rosenblattl"
  - literal: "Milana Gurbanova"
  - literal: "Karl Aurel Deck"
  - literal: "Narayan Schuetz"
  - literal: "Thomas Kaar"
  - literal: "Manuel Milling"
  - literal: "Nicolas Zumarraga"
  - literal: "Ning Wang"
  - literal: "Kelly W. Zhang"
  - literal: "Anders Johnson"
  - literal: "Robert Jakob"
  - literal: "Björn W. Schuller"
  - literal: "Elgar Fleisch"
  - literal: "Daniel Seung Kim"
  - literal: "Allan Lawrie"
  - literal: "Patrick Langer"
  - literal: "Maxwell A. Xu"
  - literal: "Euan Ashley"
  - literal: "Paul Schmiedmayer"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21274"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "timecap"
    description: "A deterministic, open-source pipeline for generating signal-grounded captions from multimodal time-series data using tiered extractors and synthesis layers."
datasets:
  - name: "MHCap"
    description: "The largest open caption layer for multimodal wearable health data, containing over 7 million signal-grounded captions derived from the MyHeart Counts dataset."
  - name: "OpenMHC"
    description: "The source wearable dataset (MyHeart Counts) used to generate the MHCap caption layer; a landmark multimodal dataset for wearable health signals."
open_questions:
  - name: "deterministic-vs-llm-captions-for-tslm"
    description: "How does the performance and robustness of models trained on deterministic, rule-based captions compare to those trained on linguistically diverse but potentially hallucinated LLM-generated captions as the scale of the pre-training data increases?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:23:24Z"
created_at: "2026-10-18T00:23:24Z"
---

# TimeCap: A Scalable Open-Source Pipeline for Captioning Wearable Health Time-Series Data

**Authors**: Max Rosenblattl, Milana Gurbanova, Karl Aurel Deck, Narayan Schuetz, Thomas Kaar, Manuel Milling, Nicolas Zumarraga, Ning Wang, Kelly W. Zhang, Anders Johnson, Robert Jakob, Björn W. Schuller, Elgar Fleisch, Daniel Seung Kim, Allan Lawrie, Patrick Langer, Maxwell A. Xu, Euan Ashley, Paul Schmiedmayer
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21274](https://arxiv.org/abs/2610.21274)

## Summary

This paper introduces TimeCap, a scalable and deterministic open-source pipeline for captioning wearable health time-series data without using a language model in the loop for generation. By using tiered extractors and a synthesis layer, TimeCap ensures that captions are reproducible and signal-grounded, addressing the auditability and scaling issues of LLM-based annotation. The authors use this pipeline to create MHCap, a dataset of over 7 million captions for 19 Apple HealthKit channels, and demonstrate that a Time-Series Language Model (OpenTSLM) trained on this data outperforms traditional label-based baselines in 29 of 32 health-outcome prediction benchmarks.

## Key Contributions

- Developed TimeCap, a deterministic, LLM-free pipeline for generating reproducible and auditable captions from multimodal time-series signals.
- Generated MHCap, a massive dataset featuring 7M+ captions across 19 HealthKit channels and 900k person-days, providing a large-scale paired corpus for wearable health data.
- Demonstrated that caption-augmented training (OpenTSLM-Cap) significantly improves performance on health-outcome prediction tasks compared to label-only baselines.

## Limitations

The deterministic nature of the pipeline relies on the quality and comprehensiveness of manually defined channel extractors and schemas.

## Open Questions & Future Work

- [[deterministic-vs-llm-captions-for-tslm]]

## Key Concepts

- [[timecap]]: A deterministic, open-source pipeline for generating signal-grounded captions from multimodal time-series data using tiered extractors and synthesis layers.

## Archivist Review

The review identifies TimeCap as the primary methodological contribution, offering a scalable solution for reproducible time-series captioning. MHCap and its source OpenMHC are approved as high-impact datasets for the wearable health domain. The open question regarding deterministic versus generative synthesis addresses a fundamental challenge in scaling multi-modal foundation models.

### Approved Concepts
- TimeCap: It provides a reproducible and scalable way to generate text annotations for time-series data without the non-determinism and hallucination risks of LLM-based captioning.

### Approved Open Questions
- Deterministic vs. LLM-based Captioning for TSLM Training: Determining whether the consistency of signal-grounded rules outweighs the linguistic variety of generative models is critical for the design of future large-scale time-series pre-training pipelines.

### Rejected Candidates
- [concept] OpenTSLM (`opentslm`) - paper_local: OpenTSLM is an instance of a model used to benchmark the dataset rather than a novel architecture or general-purpose framework.
- [concept] Deterministic Captioning (`deterministic-captioning`) - subcomponent_of_broader_mechanism: In this context, deterministic captioning is a methodological attribute of the TimeCap pipeline rather than a standalone concept.
- [concept] MHCap (`mhcap-dataset`) - duplicate_existing: Already approved as a standalone dataset entity; redundant as a concept note.

## Datasets

- [[MHCap]]
- [[OpenMHC]]

## Links

- [Abstract](https://arxiv.org/abs/2610.21274)
- [PDF](https://arxiv.org/pdf/2610.21274)

