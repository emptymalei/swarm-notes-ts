---
# CSL-compatible fields
title: "Foundation Models to Unlock Real-World Evidence from Nationwide Medical Claims"
author:
  - literal: "Fan Ma"
  - literal: "Yuntian Liu"
  - literal: "Xiang Lan"
  - literal: "Weipeng Zhou"
  - literal: "Jun Ni"
  - literal: "Mauro Giuffrè"
  - literal: "Lingfei Qian"
  - literal: "Xueqing Peng"
  - literal: "Yujia Zhou"
  - literal: "Ruey-Ling Weng"
  - literal: "Huan He"
  - literal: "Lu Li"
  - literal: "Qingyu Chen"
  - literal: "Andrew Loza"
  - literal: "Laila Rasmy"
  - literal: "Degui Zhi"
  - literal: "Yuan Lu"
  - literal: "Chenjie Zeng"
  - literal: "Joshua C Denny"
  - literal: "Lee Schwamm"
  - literal: "Daniella Meeker"
  - literal: "Lucila Ohno-Machado"
  - literal: "Yong Chen"
  - literal: "Hua Xu"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02740"

# Custom fields
paper_id: "2605.02740"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "MarketScan"
concept_slugs:
  - "reclaim"
dataset_slugs:
  - "marketscan"
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:13:56Z"
created_at: "2026-05-06T05:13:56Z"
---

# Foundation Models to Unlock Real-World Evidence from Nationwide Medical Claims

**Authors**: Fan Ma, Yuntian Liu, Xiang Lan, Weipeng Zhou, Jun Ni, Mauro Giuffrè, Lingfei Qian, Xueqing Peng, Yujia Zhou, Ruey-Ling Weng, Huan He, Lu Li, Qingyu Chen, Andrew Loza, Laila Rasmy, Degui Zhi, Yuan Lu, Chenjie Zeng, Joshua C Denny, Lee Schwamm, Daniella Meeker, Lucila Ohno-Machado, Yong Chen, Hua Xu
**Date**: 2026-05-04
**Paper ID**: [arxiv:2605.02740](https://arxiv.org/abs/2605.02740)

## Summary

The paper introduces ReClaim, a generative transformer-based foundation model specifically designed for longitudinal administrative medical claims data. Trained on 43.8 billion medical events, the model effectively learns complex representations of disease trajectories, medications, and healthcare expenditures. Empirical results across over 1,000 tasks demonstrate that ReClaim significantly outperforms existing baselines in disease-onset prediction and improves real-world evidence generation, including target trial emulation and cost forecasting.

## Key Contributions

- Introduced ReClaim, a generative transformer foundation model trained on 43.8 billion longitudinal medical events from over 200 million individuals.
- Demonstrated superior performance in over 1,000 disease-onset prediction tasks with a mean AUC of 75.6%, significantly outperforming LightGBM and Delphi models.
- Showed that ReClaim improves healthcare expenditure forecasting and reduces systematic bias in target trial emulation by 72% on average.

## Open Questions & Future Work

- [[claims-model-transportability-and-bias]]

## Key Concepts

- [[reclaim]]: A generative transformer foundation model trained on massive longitudinal medical claims data for disease prediction and financial outcome forecasting.

## Archivist Review

I approved the ReClaim foundation model as it represents a significant scaling shift in medical claims analysis. MarketScan was approved as a critical, large-scale dataset for medical informatics. The open question regarding claims transportability highlights a key bottleneck in the utility of billing-based evidence for clinical decision support.

### Approved Concepts
- ReClaim: ReClaim establishes the efficacy of large-scale generative transformers for administrative claims data, outperforming domain-specific baselines in disease prediction and healthcare expenditure forecasting.

### Approved Open Questions
- Claims Model Transportability Limits: Ensuring equitable model utility across different insurance environments is critical for using claims data as a reliable substrate for clinical and public health informatics.

## Datasets

- [[marketscan]]

## Links

- [Abstract](https://arxiv.org/abs/2605.02740)
- [PDF](https://arxiv.org/pdf/2605.02740)

