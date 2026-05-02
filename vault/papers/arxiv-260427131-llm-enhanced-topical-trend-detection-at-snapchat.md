---
# CSL-compatible fields
title: "LLM-Enhanced Topical Trend Detection at Snapchat"
author:
  - literal: "Hangqi Zhao"
  - literal: "Jay Li"
  - literal: "Abhiruchi Bhattacharya"
  - literal: "Cong Ni"
  - literal: "Jason Yeung"
  - literal: "Jinchao Ye"
  - literal: "Kai Yang"
  - literal: "Akshat Malu"
  - literal: "Manish Malik"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.27131"

# Custom fields
paper_id: "2604.27131"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:09:16Z"
created_at: "2026-05-02T05:09:16Z"
---

# LLM-Enhanced Topical Trend Detection at Snapchat

**Authors**: Hangqi Zhao, Jay Li, Abhiruchi Bhattacharya, Cong Ni, Jason Yeung, Jinchao Ye, Kai Yang, Akshat Malu, Manish Malik
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27131](https://arxiv.org/abs/2604.27131)

## Summary

This paper presents an end-to-end production system designed to detect emerging topical trends on Snapchat's short-video ecosystem. The architecture integrates multimodal topic extraction with time-series burst detection, followed by LLM-based consolidation to synthesize and enrich detected signals. Deployed at a global scale, the system significantly improves content freshness and user engagement across downstream applications like content ranking and search.

## Key Contributions

- Presents an end-to-end production-scale system for topical trend detection on a major short-video social platform.
- Integrates a multi-stage pipeline combining multimodal topic extraction, time-series burst detection, and LLM-based trend consolidation.
- Demonstrates, through six months of continuous human evaluation, high precision in identifying actionable topical trends with measurable gains in content freshness and search performance.

## Open Questions & Future Work

- [[lack-of-ground-truth-for-trend-detection-recall]]

## Archivist Review

I approved the open question regarding the lack of ground truth for trend detection as it identifies a major, recurring bottleneck in social media intelligence. I rejected the proposed concepts because they represent implementation-specific production pipelines rather than reusable architectural or algorithmic primitives suitable for the research vault.

### Approved Open Questions
- Benchmarking Trend Detection Recall: Without a standardized ground-truth, it is impossible to objectively compare the effectiveness, recall, and sensitivity of different trend-detection architectures across disparate social media platforms.

### Rejected Candidates
- [concept] LLM-based Trend Consolidation (`llm-based-trend-consolidation`) - subcomponent_of_broader_mechanism: This is a specific application of LLMs to a pipeline rather than a reusable core mechanism or architecture.
- [concept] Multimodal Topic Extraction Pipeline (`multimodal-topic-extraction-pipeline`) - not_novel: This describes a standard operational pipeline for social platforms rather than a distinct algorithmic contribution.

## Links

- [Abstract](https://arxiv.org/abs/2604.27131)
- [PDF](https://arxiv.org/pdf/2604.27131)

