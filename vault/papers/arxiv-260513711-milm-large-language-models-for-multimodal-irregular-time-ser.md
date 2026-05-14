---
# CSL-compatible fields
title: "MILM: Large Language Models for Multimodal Irregular Time Series with Informative Sampling"
author:
  - literal: "Hsing-Huan Chung"
  - literal: "Shijun Li"
  - literal: "Yoav Wald"
  - literal: "Xing Han"
  - literal: "Suchi Saria"
  - literal: "Joydeep Ghosh"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13711"

# Custom fields
paper_id: "2605.13711"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "llm"
  - "time-series-forecasting"
  - "multimodal-learning"
  - "healthcare-ai"
  - "ehr-analysis"
  - "irregular-sampling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "multimodal-irregular-time-series-language-model-milm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:23:05Z"
created_at: "2026-05-14T05:23:05Z"
---

# MILM: Large Language Models for Multimodal Irregular Time Series with Informative Sampling

**Authors**: Hsing-Huan Chung, Shijun Li, Yoav Wald, Xing Han, Suchi Saria, Joydeep Ghosh
**Date**: 2026-05-13
**Paper ID**: [arxiv:2605.13711](https://arxiv.org/abs/2605.13711)

## Summary

MILM addresses the challenge of modeling asynchronous, irregular multimodal time series (MITS) by converting heterogeneous data into XML-formatted time-ordered triplets suitable for LLM fine-tuning. The framework employs a two-stage training strategy: a first stage focused on learning predictive signals solely from sampling patterns, followed by a second stage that incorporates numerical and textual values. Empirical results on EHR benchmarks demonstrate that this approach effectively exploits the informational value of irregular sampling, particularly in settings with partial data availability.

## Key Contributions

- Introduces MILM, a framework that represents multimodal irregular time series (MITS) as time-ordered XML-formatted triplets for LLM-based modeling.
- Proposes a two-stage fine-tuning strategy that first learns from sampling patterns (value-redacted) before incorporating full observed values to improve predictive robustness.
- Demonstrates that MILM-2S outperforms baselines in scenarios with informative missingness and value-pending predictions in EHR tasks like in-hospital mortality prediction.

## Open Questions & Future Work

- [[mit-robustness-sampling-shift]]

## Key Concepts

- [[multimodal-irregular-time-series-language-model-milm]]: A framework for multimodal irregular time series classification that represents data as time-ordered XML triplets and uses a two-stage training strategy to exploit informative sampling patterns.

## Archivist Review

I approved the MILM framework concept for its novel XML-based temporal representation and two-stage training strategy, which provide a reusable paradigm for handling irregular, heterogeneous time-stamped data. I also approved the open question regarding sampling distribution shift, as it addresses a core limitation in the reliability of models trained on event-driven healthcare data. Other candidates were rejected for being overly speculative or generic regarding future work.

### Approved Concepts
- Multimodal Irregular Time Series Language Model (MILM): The framework introduces a novel XML-based structured representation that allows LLMs to jointly model irregular timing, channel patterns, and actual observations, specifically addressing informative missingness in longitudinal data.

### Approved Open Questions
- Robustness to sampling distribution shift: Ensuring robustness against sampling shifts is essential for the reliability and generalizability of predictive models in high-stakes clinical settings.

### Rejected Candidates
- [open_question] Extending MITS to additional modalities (`extending-mit-to-additional-modalities`) - low_impact: This is a generic future work suggestion regarding model expansion rather than an identified fundamental research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.13711)
- [PDF](https://arxiv.org/pdf/2605.13711)

