---
# CSL-compatible fields
title: "PreScam: A Benchmark for Predicting Scam Progression from Early Conversations"
author:
  - literal: "Weixiang Sun"
  - literal: "Shang Ma"
  - literal: "Yiyang Li"
  - literal: "Tianyi Ma"
  - literal: "Zehong Wang"
  - literal: "Colby Nelson"
  - literal: "Xusheng Xiao"
  - literal: "Yanfang Ye"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12243"

# Custom fields
paper_id: "2605.12243"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  - "prescam"
concept_slugs:
  - "scam-kill-chain"
dataset_slugs:
  - "prescam"
skill: "GeneralMLSkill"
processed_at: "2026-05-13T05:23:15Z"
created_at: "2026-05-13T05:23:15Z"
---

# PreScam: A Benchmark for Predicting Scam Progression from Early Conversations

**Authors**: Weixiang Sun, Shang Ma, Yiyang Li, Tianyi Ma, Zehong Wang, Colby Nelson, Xusheng Xiao, Yanfang Ye
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12243](https://arxiv.org/abs/2605.12243)

## Summary

PreScam is a novel benchmark designed to evaluate how AI models track the progression of multi-turn conversational scams over time, moving beyond static fraud detection. By structuring 11,573 user-reported scam instances into a hierarchical scam kill chain, the benchmark enables systematic analysis of scammer psychological actions and escalation phases. Experimental results indicate a significant performance gap, where even advanced LLMs fail to effectively predict conversation termination or future scammer actions, highlighting a limitation in understanding long-term manipulation dynamics.

## Key Contributions

- Introduces PreScam, a large-scale benchmark containing 11,573 real-world conversational scam instances across 20 categories.
- Proposes a hierarchical 'scam kill chain' to model the multi-turn lifecycle of psychological manipulation in online fraud.
- Demonstrates that current LLMs struggle with scam progression tracking, significantly trailing supervised encoders on real-time termination prediction.

## Open Questions & Future Work

- [[scam-progression-modeling-bottleneck]]

## Key Concepts

- [[scam-kill-chain]]: A hierarchical framework for structuring the progression of conversational scams across their full lifecycle.

## Archivist Review

The approved items characterize a new paradigm in fraud research that focuses on dynamic, multi-turn conversational progression rather than static detection. The PreScam dataset and its associated Kill Chain taxonomy represent significant, reusable contributions for future research into AI-driven behavioral manipulation. The open question accurately reflects the identified research gap regarding latent structural prediction versus surface-level pattern matching.

### Approved Concepts
- Scam Kill Chain: This framework provides the essential theoretical structure for labeling and understanding the multi-turn progression of conversational scams, moving beyond static detection.

### Approved Open Questions
- Modeling Conversational Scam Progression: This is the central limitation identified in the paper; models that can accurately forecast scam progression are fundamentally more capable of proactive, timely user intervention than those that rely solely on static message classification.

## Datasets

- [[prescam]]

## Links

- [Abstract](https://arxiv.org/abs/2605.12243)
- [PDF](https://arxiv.org/pdf/2605.12243)

