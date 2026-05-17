---
# CSL-compatible fields
title: "Exploring Vision-Language Models for Online Signature Verification: A Zero-Shot Capability Study"
author:
  - literal: "Marta Robledo-Moreno"
  - literal: "Ruben Vera-Rodriguez"
  - literal: "Ruben Tolosana"
  - literal: "Javier Ortega-Garcia"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14845"

# Custom fields
paper_id: "2605.14845"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "rationalization-trap"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:23:16Z"
created_at: "2026-05-17T05:23:16Z"
---

# Exploring Vision-Language Models for Online Signature Verification: A Zero-Shot Capability Study

**Authors**: Marta Robledo-Moreno, Ruben Vera-Rodriguez, Ruben Tolosana, Javier Ortega-Garcia
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14845](https://arxiv.org/abs/2605.14845)

## Summary

This study evaluates the zero-shot performance of vision-language models (VLMs) on online signature verification by transforming kinematic data into static images. While models achieve superior performance in random forgery scenarios, they struggle with skilled forgeries due to the 'Rationalization Trap,' where chain-of-thought reasoning generates false kinematic justifications. The findings provide a critical assessment of the limitations of current multimodal models in high-stakes biometric verification tasks.

## Key Contributions

- Establishes a baseline for zero-shot online signature verification using state-of-the-art VLMs via kinematic-to-static image conversion.
- Proposes a novel scoring protocol leveraging latent token probabilities from VLMs for biometric verification.
- Identifies the 'Rationalization Trap' where chain-of-thought reasoning leads to kinematic hallucinations, significantly degrading performance on skilled forgeries.

## Open Questions & Future Work

- [[mitigating-vlm-rationalization-traps]]

## Key Concepts

- [[rationalization-trap]]: A phenomenon where chain-of-thought reasoning causes models to hallucinate justifications for artifacts, paradoxically degrading performance in high-precision verification tasks.

## Archivist Review

I approved the Rationalization Trap as a central concept because it describes a significant and counterintuitive failure mode in multimodal foundation models that is likely to recur in other high-stakes domains. I also approved the corresponding open question regarding mitigation of this trap, as it addresses a critical research bottleneck in AI safety and interpretability. The SVC dataset was rejected as it is a standard competition benchmark rather than a novel research-derived dataset.

### Approved Concepts
- Rationalization Trap: It identifies a failure mode in LLMs/VLMs where reasoning processes lead to incorrect, hallucinated justifications in sensitive classification tasks.

### Approved Open Questions
- Mitigating VLM Rationalization Traps: Understanding this phenomenon is critical for the safety and reliability of foundation models in high-assurance domains where interpretability is a requirement.

### Rejected Candidates
- [dataset] Signature Verification Challenge (SVC) (`SVC`) - not_novel: This is a standard, longstanding competition benchmark dataset that does not warrant a new standalone vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2605.14845)
- [PDF](https://arxiv.org/pdf/2605.14845)

