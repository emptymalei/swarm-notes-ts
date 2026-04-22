---
# CSL-compatible fields
title: "OmniMouse: Scaling properties of multi-modal, multi-task Brain Models on 150B Neural Tokens"
author:
  - literal: "Konstantin F. Willeke"
  - literal: "Polina Turishcheva"
  - literal: "Alex Gilbert"
  - literal: "Goirik Chakrabarty"
  - literal: "Hasan A. Bedel"
  - literal: "Paul G. Fahey"
  - literal: "Yongrong Qiu"
  - literal: "Marissa A. Weis"
  - literal: "Michaela Vystrčilová"
  - literal: "Taliah Muhammad"
  - literal: "Lydia Ntanavara"
  - literal: "Rachel E. Froebe"
  - literal: "Kayla Ponder"
  - literal: "Zheng Huan Tan"
  - literal: "Emin Orhan"
  - literal: "Erick Cobos"
  - literal: "Sophia Sanborn"
  - literal: "Katrin Franke"
  - literal: "Fabian H. Sinz"
  - literal: "Alexander S. Ecker"
  - literal: "Andreas S. Tolias"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18827"

# Custom fields
paper_id: "2604.18827"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "time-series"
  - "multi-modal-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "neural-tokenization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:04:58Z"
created_at: "2026-04-22T05:04:58Z"
---

# OmniMouse: Scaling properties of multi-modal, multi-task Brain Models on 150B Neural Tokens

**Authors**: Konstantin F. Willeke, Polina Turishcheva, Alex Gilbert, Goirik Chakrabarty, Hasan A. Bedel, Paul G. Fahey, Yongrong Qiu, Marissa A. Weis, Michaela Vystrčilová, Taliah Muhammad, Lydia Ntanavara, Rachel E. Froebe, Kayla Ponder, Zheng Huan Tan, Emin Orhan, Erick Cobos, Sophia Sanborn, Katrin Franke, Fabian H. Sinz, Alexander S. Ecker, Andreas S. Tolias
**Date**: 2026-04-20
**Paper ID**: [arxiv:2604.18827](https://arxiv.org/abs/2604.18827)

## Summary

OmniMouse is a foundation model for brain activity trained on an unprecedented 150 billion neural tokens from 3.1 million mouse visual cortex neurons. The model supports flexible, multi-task inference, including neural prediction, behavior decoding, and forecasting, and achieves state-of-the-art performance across all tasks. Crucially, the authors find that neural modeling is currently limited by data quantity rather than model architecture size, contrasting with standard scaling laws in LLMs and vision models.

## Key Contributions

- Introduces OmniMouse, a multi-modal, multi-task foundation model for mouse visual cortex activity trained on 150B neural tokens.
- Demonstrates that neural modeling performance scales reliably with dataset size, while model size scaling saturates, indicating a data-limited regime.
- Establishes a unified framework for flexible neural prediction, behavioral decoding, and neural forecasting at test time.

## Open Questions & Future Work

- [[neural-parameter-scaling-bottleneck]]

## Key Concepts

- [[neural-tokenization]]: The representation of discrete, standardized neural activity events as sequences suitable for transformer-based modeling.

## Archivist Review

I approved 'Neural Tokenization' as it captures the fundamental shift in representing neural dynamics as discrete tokens, which is central to the paper's multi-modal foundation modeling approach. I approved the open question regarding the 'neural-parameter-scaling-bottleneck' because it identifies a critical, structural limitation for future neuroscience-inspired foundation models. Other potential candidates were deemed either too generic or local to the specific implementation details of OmniMouse.

### Approved Concepts
- Neural Tokenization: Introduces the framing of brain activity as tokenized sequences for large-scale multi-modal modeling, analogous to language processing.

### Approved Open Questions
- Scaling bottleneck of neuron embeddings: This architectural bottleneck represents a fundamental barrier to scaling neural foundation models as high-density recording technologies continue to increase the number of monitored neurons.

## Links

- [Abstract](https://arxiv.org/abs/2604.18827)
- [PDF](https://arxiv.org/pdf/2604.18827)

