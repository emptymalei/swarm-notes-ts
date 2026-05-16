---
# CSL-compatible fields
title: "COTCAgent: Preventive Consultation via Probabilistic Chain-of-Thought Completion"
author:
  - literal: "Zihan Deng"
  - literal: "Xiaozhen Zhong"
  - literal: "Chuanzhi Xu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15016"

# Custom fields
paper_id: "2605.15016"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  - "healthbench"
concept_slugs:
  - "probabilistic-chain-of-thought-completion"
dataset_slugs:
  - "healthbench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:11:15Z"
created_at: "2026-05-16T05:11:15Z"
---

# COTCAgent: Preventive Consultation via Probabilistic Chain-of-Thought Completion

**Authors**: Zihan Deng, Xiaozhen Zhong, Chuanzhi Xu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15016](https://arxiv.org/abs/2605.15016)

## Summary

COTCAgent is a hierarchical reasoning framework designed for longitudinal electronic health record (EHR) analysis, addressing LLM hallucinations in clinical trend and metric interpretation. By implementing a Temporal-Statistics Adapter for quantitative reasoning and a Chain-of-Thought Completion layer for risk-aware symptom-disease mapping, the model ensures rigorous clinical inference. The architecture decouples statistical computation from language generation, demonstrating superior performance over existing medical agents on both custom datasets and HealthBench.

## Key Contributions

- COTCAgent improves clinical decision support by introducing the Temporal-Statistics Adapter for standardized quantitative trend outputs.
- The framework achieves 90.47% Top-1 accuracy on a self-built longitudinal EHR dataset and 70.41% on HealthBench.
- Decouples statistical computation, feature matching, and text generation to improve clinical reasoning reliability while reducing computational overhead.

## Open Questions & Future Work

- [[clinical-risk-calibration-and-deployment]]

## Key Concepts

- [[probabilistic-chain-of-thought-completion]]: A hierarchical reasoning architecture that bridges quantitative statistical trend analysis with qualitative clinical knowledge to improve longitudinal data interpretation.

## Archivist Review

The Probabilistic Chain-of-Thought Completion framework was approved as a significant architectural approach to longitudinal time-series reasoning. HealthBench was approved as a standard benchmark dataset in this domain. The open question was refined to emphasize the gap between benchmark performance and real-world clinical safety. Other components like the Temporal-Statistics Adapter were rejected as sub-components of the primary framework.

### Approved Concepts
- Probabilistic Chain-of-Thought Completion (COTC): Provides a modular framework for decoupling statistical computation, feature matching, and natural language generation, mitigating hallucination risks in quantitative clinical temporal reasoning.

### Approved Open Questions
- Clinical Risk Calibration Reliability: Addresses the critical gap between model performance on benchmarks and the safety standards required for clinical decision support systems.

### Rejected Candidates
- [concept] Temporal-Statistics Adapter (TSA) (`temporal-statistics-adapter`) - subcomponent_of_broader_mechanism: This is a sub-module of the overarching COTC framework; it is better to track the framework as a whole.

## Datasets

- [[healthbench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.15016)
- [PDF](https://arxiv.org/pdf/2605.15016)

