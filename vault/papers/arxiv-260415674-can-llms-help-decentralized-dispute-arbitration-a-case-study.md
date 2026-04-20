---
# CSL-compatible fields
title: "Can LLMs Help Decentralized Dispute Arbitration? A Case Study of UMA-Resolved Markets on Polymarket"
author:
  - literal: "Junhao Wen"
  - literal: "Juncen Zhou"
  - literal: "Junjie Huang"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.15674"

# Custom fields
paper_id: "2604.15674"
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
skill: "GeneralMLSkill"
processed_at: "2026-04-20T05:10:34Z"
created_at: "2026-04-20T05:10:34Z"
---

# Can LLMs Help Decentralized Dispute Arbitration? A Case Study of UMA-Resolved Markets on Polymarket

**Authors**: Junhao Wen, Juncen Zhou, Junjie Huang
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.15674](https://arxiv.org/abs/2604.15674)

## Summary

This paper investigates the potential of large language models (LLMs) to improve dispute resolution in decentralized prediction markets like Polymarket. The study evaluates two primary tasks: predicting future dispute likelihood based on event rules and replicating the actual arbitration results of the UMA voting protocol. Results indicate that while LLMs struggle to predict disputes in advance, they show significant promise as tools for consensus arbitration, achieving nearly 90% agreement with existing on-chain resolution mechanisms.

## Key Contributions

- Evaluates the feasibility of using web-enabled LLMs as automated arbiters for decentralized prediction market disputes.
- Demonstrates that LLMs can reproduce UMA's on-chain dispute resolution outcomes with 89.58% agreement accuracy.
- Finds that LLMs are currently ineffective at predicting which future market events are likely to face disputes based on their rules.

## Open Questions & Future Work

- [[llm-governance-integration-security]]

## Archivist Review

I have approved the open question regarding the integration of LLMs into decentralized governance, as it highlights a significant security and design bottleneck in applying LLM-based arbitration to real-world systems. No concepts were approved because the paper's primary contribution is an application-specific evaluation rather than a reusable architectural or algorithmic mechanism. No datasets were approved as they were not uniquely named or centralized in the context of the vault's standards.

### Approved Open Questions
- Integrating LLMs into Decentralized Governance: This is critical for transitioning from experimental validation to actual implementation in high-stakes financial environments where trust and security are paramount.

## Links

- [Abstract](https://arxiv.org/abs/2604.15674)
- [PDF](https://arxiv.org/pdf/2604.15674)

