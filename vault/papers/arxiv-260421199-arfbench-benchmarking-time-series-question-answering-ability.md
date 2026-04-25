---
# CSL-compatible fields
title: "ARFBench: Benchmarking Time Series Question Answering Ability for Software Incident Response"
author:
  - literal: "Stephan Xie"
  - literal: "Ben Cohen"
  - literal: "Mononito Goswami"
  - literal: "Junhong Shen"
  - literal: "Emaad Khwaja"
  - literal: "Chenghao Liu"
  - literal: "David Asker"
  - literal: "Othmane Abou-Amal"
  - literal: "Ameet Talwalkar"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21199"

# Custom fields
paper_id: "2604.21199"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "ARFBench"
concept_slugs:
  []
dataset_slugs:
  - "arfbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:54:55Z"
created_at: "2026-04-25T04:54:55Z"
---

# ARFBench: Benchmarking Time Series Question Answering Ability for Software Incident Response

**Authors**: Stephan Xie, Ben Cohen, Mononito Goswami, Junhong Shen, Emaad Khwaja, Chenghao Liu, David Asker, Othmane Abou-Amal, Ameet Talwalkar
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21199](https://arxiv.org/abs/2604.21199)

## Summary

This paper introduces ARFBench, a new benchmark designed to evaluate the Time Series Question-Answering (TSQA) capabilities of foundation models specifically for software incident response. The dataset includes 750 questions derived from 63 production software incidents, providing a rigorous test for LLMs, VLMs, and specialized time series models. Findings reveal that while frontier VLMs currently dominate the task, specialized hybrid TSFM-VLM architectures show significant promise. Finally, the authors demonstrate that integrating human expert input with model predictions creates a superhuman oracle, setting a new performance benchmark for operational incident analysis.

## Key Contributions

- Introduced ARFBench, a benchmark with 750 questions across 142 time series from 63 production software incidents for evaluating TSQA capabilities.
- Demonstrated that frontier VLMs significantly outperform existing baselines, with the top-performing model achieving 62.7% accuracy and 51.9% F1.
- Developed a TSFM + VLM hybrid prototype that achieves competitive results via targeted post-training, demonstrating the efficacy of specialized multimodal approaches.
- Established a model-expert oracle selector that reaches 87.2% accuracy, highlighting the complementary nature of human expertise and automated systems in incident response.

## Archivist Review

I have approved the ARFBench dataset as a valuable contribution to the time series domain. I rejected the concept candidate 'ARFBench' because it is essentially describing the dataset already approved; naming a benchmark as a reusable 'concept' is generally redundant when the asset itself is tracked in the dataset registry. I did not identify any research-grade open questions that move beyond specific performance reporting to address fundamental algorithmic or methodological bottlenecks.

### Rejected Candidates
- [concept] ARFBench (`arfbench`) - subcomponent_of_broader_mechanism: The benchmark itself is already approved as a dataset, and the methodology of using QA for time series evaluation is not yet a mature, distinct conceptual framework distinct from general TSQA.

## Datasets

- [[arfbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21199)
- [PDF](https://arxiv.org/pdf/2604.21199)

