---
# CSL-compatible fields
title: "LLM-as-a-Judge for Time Series Explanations"
author:
  - literal: "Preetham Sivalingam"
  - literal: "Murari Mandal"
  - literal: "Saurabh Deshpande"
  - literal: "Dhruv Kumar"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02118"

# Custom fields
paper_id: "2604.02118"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "llm-as-a-judge-for-time-series-explanations"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:19:20Z"
created_at: "2026-04-03T05:19:20Z"
---

# LLM-as-a-Judge for Time Series Explanations

**Authors**: Preetham Sivalingam, Murari Mandal, Saurabh Deshpande, Dhruv Kumar
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02118](https://arxiv.org/abs/2604.02118)

## Summary

This paper addresses the challenge of evaluating natural language explanations for time series data by employing LLMs as judges in a reference-free setting. The authors construct a new synthetic benchmark to systematically assess how well LLMs perform in generation, ranking, and scoring tasks across varied query types like seasonal drops and structural breaks. Empirical results reveal an asymmetry where LLMs exhibit high competence as evaluators—providing stable scores and rankings—even while struggling to generate accurate explanations for specific complex query types.

## Key Contributions

- Proposes an LLM-as-a-Judge framework to evaluate time series explanations based on pattern identification, numerical accuracy, and answer faithfulness without ground truth.
- Constructs a synthetic benchmark of 350 time series cases across seven distinct query types to assess explanation generation and evaluation capabilities.
- Demonstrates that LLMs are more reliable as evaluators than as generators, showing consistent ranking performance even when models fail to generate correct explanations themselves.

## Open Questions & Future Work

- [[reference-free-time-series-evaluation]]

## Key Concepts

- [[llm-as-a-judge-for-time-series-explanations]]: A reference-free evaluation framework where LLMs are used to score the factual accuracy and faithfulness of natural language explanations derived from numerical time series data.

## Archivist Review

I approved the LLM-as-a-Judge concept and its associated open question regarding reference-free evaluation. These address a fundamental gap in XAI for time series, moving beyond simple numerical metrics toward verifiable natural language reasoning. I rejected the synthetic benchmark as a dataset candidate, as it is a specific, small-scale synthetic construction rather than a foundational, reusable dataset for general benchmarking.

### Approved Concepts
- LLM-as-a-Judge for Time Series Explanations: Establishes a paradigm for evaluating the faithfulness and correctness of natural language time series interpretations without requiring ground-truth references.

### Approved Open Questions
- Reliable Time-Series Explanation Evaluation: Ensuring the reliability of LLMs in high-stakes time-series domains like finance, climate, and healthcare is critical, as automated reasoning must be demonstrably grounded in the underlying data.

## Links

- [Abstract](https://arxiv.org/abs/2604.02118)
- [PDF](https://arxiv.org/pdf/2604.02118)

