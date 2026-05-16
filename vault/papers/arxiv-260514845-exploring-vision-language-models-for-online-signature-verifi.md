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
domain: "computer-vision"
tags:
  - "biometrics"
  - "vision-language-models"
  - "zero-shot-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "rationalization-trap"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:11:36Z"
created_at: "2026-05-16T05:11:36Z"
---

# Exploring Vision-Language Models for Online Signature Verification: A Zero-Shot Capability Study

**Authors**: Marta Robledo-Moreno, Ruben Vera-Rodriguez, Ruben Tolosana, Javier Ortega-Garcia
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14845](https://arxiv.org/abs/2605.14845)

## Summary

This study investigates the zero-shot biometric verification capabilities of state-of-the-art vision-language models by transforming online signature kinematic data into static images. While models like GPT-5.2 achieve state-of-the-art performance in random forgery detection, they struggle significantly with skilled forgeries. A key finding is the emergence of a 'Rationalization Trap', where chain-of-thought prompting causes models to hallucinate justifications for forgery artifacts, thereby reducing overall system accuracy.

## Key Contributions

- Evaluated zero-shot VLM performance (GPT-5.2, Gemini 2.5 Pro) on the Signature Verification Challenge benchmark, demonstrating high efficacy for random forgery detection but poor performance on skilled forgeries.
- Introduced a kinematic-to-static image conversion strategy that encodes pressure as stroke opacity to facilitate VLM processing of online signatures.
- Developed a token-probability-based scoring protocol for robust biometric assessment and identified the 'Rationalization Trap', where CoT reasoning induces kinematic hallucinations that mask forgery artifacts.

## Open Questions & Future Work

- [[vlm-biometric-rationalization-hallucination]]

## Key Concepts

- [[rationalization-trap]]: A phenomenon where Chain-of-Thought reasoning leads models to generate false kinematic justifications for forgery artifacts, degrading verification performance.

## Archivist Review

The paper provides a significant contribution by defining the 'Rationalization Trap' as a systematic failure mode for VLMs in biometric reasoning. This concept and the associated open question regarding its mitigation are highly relevant for future XAI and VLM research in high-stakes domains. The signature benchmark itself is considered standard and was rejected as a dataset candidate to maintain archival selectivity.

### Approved Concepts
- Rationalization Trap: Identifies a fundamental failure mode in VLM biometric reasoning where CoT leads to false positives via hallucinated justifications.

### Approved Open Questions
- Mitigating VLM Rationalization Hallucinations: The rationalization trap significantly undermines the trustworthiness of XAI in high-stakes biometric scenarios, as it can cause models to confidently misclassify forgeries while providing misleading, human-sounding justifications.

### Rejected Candidates
- [dataset] Signature Verification Challenge (SVC) (`svc-signature-verification-challenge`) - duplicate_existing: The Signature Verification Challenge is a well-established academic benchmark and not a novel dataset deserving a unique note.

## Links

- [Abstract](https://arxiv.org/abs/2605.14845)
- [PDF](https://arxiv.org/pdf/2605.14845)

