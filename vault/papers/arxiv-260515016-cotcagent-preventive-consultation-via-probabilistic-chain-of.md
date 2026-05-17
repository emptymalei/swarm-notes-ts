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
  []
architectures:
  []
datasets:
  - "healthbench"
concept_slugs:
  - "probabilistic-chain-of-thought-completion"
dataset_slugs:
  - "healthbench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:22:55Z"
created_at: "2026-05-17T05:22:55Z"
---

# COTCAgent: Preventive Consultation via Probabilistic Chain-of-Thought Completion

**Authors**: Zihan Deng, Xiaozhen Zhong, Chuanzhi Xu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15016](https://arxiv.org/abs/2605.15016)

## Summary

COTCAgent is a hierarchical reasoning framework designed for longitudinal electronic health record (EHR) analysis, addressing current LLM limitations in statistical reasoning and long-range temporal dependency modeling. The framework utilizes a Temporal-Statistics Adapter for standardized trend output and a Chain-of-Thought Completion layer that incorporates a symptom-trend-disease knowledge base for evidence-based disease risk evaluation. By decoupling computation from generation, it effectively mitigates diagnostic hallucinations and improves clinical reasoning reliability on temporal health data.

## Key Contributions

- Introduces COTCAgent, a hierarchical reasoning framework that decouples statistical computation, feature matching, and language generation for EHR analysis.
- Implements a Temporal-Statistics Adapter (TSA) to translate analytical plans into executable code, reducing hallucinations in quantitative clinical trend analysis.
- Achieves 90.47% Top-1 accuracy on a private dataset and 70.41% on HealthBench, demonstrating superior performance over existing medical LLM agents.

## Open Questions & Future Work

- [[calibrated-longitudinal-clinical-risk-prediction]]

## Key Concepts

- [[probabilistic-chain-of-thought-completion]]: A hierarchical reasoning framework that uses weighted scoring and structured knowledge bases to generate rigorous, evidence-backed clinical inferences for longitudinal EHR data.

## Archivist Review

The paper proposes a structured reasoning framework (Probabilistic Chain-of-Thought Completion) which I have approved for its contribution to reducing LLM hallucinations in temporal medical tasks. I have rejected the 'Temporal-Statistics Adapter' as it functions as a subcomponent of the primary framework. The open question is approved for highlighting the critical path between research-grade reasoning and clinically-verified trust. HealthBench is approved as a central evaluation dataset for clinical LLMs.

### Approved Concepts
- Probabilistic Chain-of-Thought Completion: It provides a structured, knowledge-grounded mechanism to constrain language model reasoning in longitudinal EHR analysis, specifically mitigating hallucinations of clinical trends.

### Approved Open Questions
- Calibrated Longitudinal Clinical Risk Prediction: This is crucial for transitioning research-grade clinical decision support agents into verified, trustworthy bedside tools that can safely handle the complexities of patient-specific longitudinal data.

### Rejected Candidates
- [concept] Temporal-Statistics Adapter (`temporal-statistics-adapter`) - subcomponent_of_broader_mechanism: This is an internal modular implementation detail for code generation that is secondary to the overarching Probabilistic Chain-of-Thought Completion framework.

## Datasets

- [[healthbench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.15016)
- [PDF](https://arxiv.org/pdf/2605.15016)

