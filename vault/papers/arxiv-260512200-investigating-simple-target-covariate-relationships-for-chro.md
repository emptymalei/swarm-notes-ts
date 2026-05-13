---
# CSL-compatible fields
title: "Investigating simple target-covariate relationships for Chronos-2 and TabPFN-TS"
author:
  - literal: "Gaspard Berthelier"
  - literal: "Mariia Baranova"
  - literal: "Andrei-Tiberiu Pantea"
  - literal: "Etienne Le Naour"
  - literal: "Adrien Petralia"
  - literal: "Tahar Nabil"
  - literal: "Themis Palpanas"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12200"

# Custom fields
paper_id: "2605.12200"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:23:29Z"
created_at: "2026-05-13T05:23:29Z"
---

# Investigating simple target-covariate relationships for Chronos-2 and TabPFN-TS

**Authors**: Gaspard Berthelier, Mariia Baranova, Andrei-Tiberiu Pantea, Etienne Le Naour, Adrien Petralia, Tahar Nabil, Themis Palpanas
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12200](https://arxiv.org/abs/2605.12200)

## Summary

This paper investigates how well modern Time Series Foundation Models (TSFMs) like Chronos-2 and TabPFN-TS integrate and model simple target-covariate relationships. By employing a series of controlled diagnostic experiments, the authors reveal that while TSFMs exhibit impressive zero-shot performance on benchmarks, they vary significantly in their ability to learn basic dependencies. The results show that TabPFN-TS is superior to Chronos-2 in modeling these specific relationships, suggesting that benchmark success does not necessarily equate to robust foundational understanding of covariate-target interactions.

## Key Contributions

- Evaluates the capability of TSFMs (Chronos-2 and TabPFN-TS) to model simple target-covariate dependencies using controlled experiments.
- Demonstrates that TabPFN-TS significantly outperforms Chronos-2 in capturing direct target-covariate relationships, particularly across short forecasting horizons.
- Identifies a limitation in Chronos-2 where its strong zero-shot performance does not guarantee optimal modeling of fundamental temporal dependencies involving covariates.

## Open Questions & Future Work

- [[hybrid-temporal-tabular-foundation-models]]

## Archivist Review

I have approved the open question regarding hybrid foundation architectures as it addresses a substantive architectural bottleneck highlighted by the paper's findings. The concepts representing the specific models compared were rejected as they are instance-specific rather than generalized methodology. No new concepts or datasets were added, maintaining the archival focus on high-level, recurring research themes.

### Approved Open Questions
- Hybrid Temporal-Tabular Foundation Architectures: The paper demonstrates that existing TSFMs specialize either in temporal modeling or tabular regression, leading to performance trade-offs based on the relative importance of these components in a specific forecasting task. Creating a model that bridges this gap is essential for building more general-purpose forecasting tools.

### Rejected Candidates
- [concept] Chronos-2 (`chronos-2`) - paper_local: This is a specific, non-reusable model instance rather than a foundational concept.
- [concept] TabPFN-TS (`tabpfn-ts`) - paper_local: This is a specific, non-reusable model instance rather than a foundational concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.12200)
- [PDF](https://arxiv.org/pdf/2605.12200)

