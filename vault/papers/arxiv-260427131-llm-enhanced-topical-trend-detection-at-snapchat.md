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
processed_at: "2026-05-01T05:24:16Z"
created_at: "2026-05-01T05:24:16Z"
---

# LLM-Enhanced Topical Trend Detection at Snapchat

**Authors**: Hangqi Zhao, Jay Li, Abhiruchi Bhattacharya, Cong Ni, Jason Yeung, Jinchao Ye, Kai Yang, Akshat Malu, Manish Malik
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.27131](https://arxiv.org/abs/2604.27131)

## Summary

This paper presents an end-to-end system designed for identifying emerging topical trends within the high-velocity, short-video ecosystem of Snapchat. The architecture combines multimodal topic extraction and time-series burst detection with LLM-based consolidation to synthesize meaningful trend signals from noisy, large-scale data. The system has been successfully deployed at global scale, demonstrably improving downstream performance in content ranking and search.

## Key Contributions

- Introduces a production-scale end-to-end system for topical trend detection on short-video social platforms.
- Integrates multimodal topic extraction with time-series burst detection and LLM-based trend consolidation.
- Demonstrates high precision via six months of offline human evaluation and significant improvements in content freshness and search performance in production.

## Open Questions & Future Work

- [[recall-evaluation-in-trend-detection]]

## Archivist Review

The paper describes a production-scale engineering system for Snapchat, but lacks the methodological novelty in forecasting or AI architecture required for a permanent vault concept note. The open question regarding recall in trend detection is accepted as a substantial, domain-agnostic bottleneck for systems evaluating emerging, ground-truth-scarce phenomena.

### Approved Open Questions
- Recall Evaluation for Trends: Precision-only evaluation is insufficient for understanding system coverage, making the development of automated ground-truth generation or recall estimation techniques essential for improving the discovery of novel and emerging trends.

## Links

- [Abstract](https://arxiv.org/abs/2604.27131)
- [PDF](https://arxiv.org/pdf/2604.27131)

