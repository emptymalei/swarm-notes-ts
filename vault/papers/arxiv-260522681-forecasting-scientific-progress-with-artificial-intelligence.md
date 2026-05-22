---
# CSL-compatible fields
title: "Forecasting Scientific Progress with Artificial Intelligence"
author:
  - literal: "Sean Wu"
  - literal: "Pan Lu"
  - literal: "Yupeng Chen"
  - literal: "Jonathan Bragg"
  - literal: "Yutaro Yamada"
  - literal: "Peter Clark"
  - literal: "David Clifton"
  - literal: "Philip Torr"
  - literal: "James Zou"
  - literal: "Junchi Yu"
issued:
  date-parts:
    - [2026, 5, 21]
url: "https://arxiv.org/abs/2605.22681"

# Custom fields
paper_id: "2605.22681"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  - "cusp-benchmark-dataset"
concept_slugs:
  - "cusp-benchmark"
dataset_slugs:
  - "cusp-benchmark-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-22T05:27:45Z"
created_at: "2026-05-22T05:27:45Z"
---

# Forecasting Scientific Progress with Artificial Intelligence

**Authors**: Sean Wu, Pan Lu, Yupeng Chen, Jonathan Bragg, Yutaro Yamada, Peter Clark, David Clifton, Philip Torr, James Zou, Junchi Yu
**Date**: 2026-05-21
**Paper ID**: [arxiv:2605.22681](https://arxiv.org/abs/2605.22681)

## Summary

This paper introduces CUSP, a novel, temporally grounded benchmark designed to evaluate how well AI models forecast scientific progress under controlled knowledge constraints. Analyzing performance across 4,760 scientific events, the authors show that frontier models struggle to predict the realization and timing of research advances, often exhibiting systematic overconfidence and strong response biases. The study finds that performance is highly domain-dependent and that current models are more reliant on post-event information than on genuine forward-looking predictive capability, suggesting significant limitations for AI in automated scientific foresight.

## Key Contributions

- Introduces CUSP, a multi-disciplinary event-level benchmark comprising 4,760 scientific events to assess AI forecasting performance under controlled knowledge cutoffs.
- Demonstrates that while frontier models identify plausible research directions, they lack the ability to reliably predict the realization or timing of scientific breakthroughs.
- Reveals significant domain-dependent performance heterogeneity, where AI-related scientific progress is more predictable than advances in natural sciences like physics, chemistry, and biology.
- Identifies systematic overconfidence and reliance on post-event information, indicating that current LLMs fail as robust tools for proactive scientific forecasting.

## Key Concepts

- [[cusp-benchmark]]: A multi-disciplinary benchmark designed to evaluate AI models on their ability to forecast scientific progress through temporal and mechanistic assessments under controlled knowledge constraints.

## Archivist Review

The paper provides a well-defined evaluation framework for scientific forecasting. I approved CUSP as a concept because it represents a distinct, reusable methodology for testing temporal foresight in AI models under controlled information constraints. I also approved the dataset as it is a core, named resource for this benchmark. I rejected potential future work directions as they were framed too broadly to serve as specific, actionable research questions.

### Approved Concepts
- CUSP (Cutoff-conditioned Unseen Scientific Progress): It establishes a rigorous methodology for evaluating predictive capabilities in AI using temporal knowledge cutoffs and event-level scientific progress tracking, which is distinct from standard static benchmarks.

## Datasets

- [[cusp-benchmark-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.22681)
- [PDF](https://arxiv.org/pdf/2605.22681)

