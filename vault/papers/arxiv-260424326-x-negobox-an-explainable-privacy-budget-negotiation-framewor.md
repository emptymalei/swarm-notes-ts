---
# CSL-compatible fields
title: "X-NegoBox: An Explainable Privacy-Budget Negotiation Framework for Secure Peer-to-Peer Energy Data Exchange"
author:
  - literal: "Poushali Sengupta"
  - literal: "Sabita Maharjan"
  - literal: "Frank Eliassen"
  - literal: "Yan Zhang"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24326"

# Custom fields
paper_id: "2604.24326"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "autonomous-privacy-budget-negotiation-protocol-apbnp"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:14:40Z"
created_at: "2026-04-28T05:14:40Z"
---

# X-NegoBox: An Explainable Privacy-Budget Negotiation Framework for Secure Peer-to-Peer Energy Data Exchange

**Authors**: Poushali Sengupta, Sabita Maharjan, Frank Eliassen, Yan Zhang
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24326](https://arxiv.org/abs/2604.24326)

## Summary

X-NegoBox is an explainable negotiation framework designed to securely facilitate peer-to-peer energy data exchange while maintaining prosumer privacy. The system utilizes an Autonomous Privacy Budget Negotiation Protocol (APBNP) to determine budgets based on contextual risk and trust factors, paired with an Explainable Agreement Layer (X-Contract) to justify negotiation outcomes. By confining data within local 'DataBoxes' and executing external code in secure sandboxes, the framework balances data utility with privacy protection, outperforming static privacy policies in reliability and acceptance rates.

## Key Contributions

- Introduces X-NegoBox, a framework for explainable and adaptive privacy-budget negotiation in decentralized energy markets.
- Develops APBNP, a protocol for dynamic privacy budget determination based on trust, sensitivity, and risk-aware pricing.
- Implements X-Contract to provide transparent, human-readable justifications for decision outcomes, enhancing trust in automated data exchange.

## Open Questions & Future Work

- [[negotiation-aware-tss-design]]

## Key Concepts

- [[autonomous-privacy-budget-negotiation-protocol-apbnp]]: A protocol for autonomously determining and negotiating privacy budgets based on multi-factor trust and risk analysis.

## Archivist Review

I approved the core negotiation protocol as a reusable concept and the open question regarding its cryptographic enforcement via TSS. The explainable layer was rejected as a sub-component, as it functions primarily as an application of standard XAI techniques within the framework. No datasets were approved as none were provided.

### Approved Concepts
- Autonomous Privacy Budget Negotiation Protocol (APBNP): Provides a reusable mechanism for context-aware, autonomous privacy budgeting in decentralized settings.

### Approved Open Questions
- Negotiation-Aware Threshold Secret Sharing: Directly addresses the integration of privacy policy negotiation with the cryptographic primitives that enforce secure data release in decentralized systems.

### Rejected Candidates
- [concept] Explainable Agreement Layer (X-Contract) (`explainable-agreement-layer-x-contract`) - subcomponent_of_broader_mechanism: This is a functional sub-module for generating explanations, which is common in XAI and lacks the broader algorithmic novelty of the negotiation protocol.

## Links

- [Abstract](https://arxiv.org/abs/2604.24326)
- [PDF](https://arxiv.org/pdf/2604.24326)

