---
# CSL-compatible fields
title: "Generative Diffusion Prior Distillation for Long-Context Knowledge Transfer"
author:
  - literal: "Nilushika Udayangani"
  - literal: "Kishor Nandakishor"
  - literal: "Marimuthu Palaniswami"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11414"

# Custom fields
paper_id: "2605.11414"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "generative-diffusion-prior-distillation-gdpd"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:25:46Z"
created_at: "2026-05-13T05:25:46Z"
---

# Generative Diffusion Prior Distillation for Long-Context Knowledge Transfer

**Authors**: Nilushika Udayangani, Kishor Nandakishor, Marimuthu Palaniswami
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11414](https://arxiv.org/abs/2605.11414)

## Summary

This paper introduces Generative Diffusion Prior Distillation (GDPD), a knowledge distillation framework designed to enhance time-series classification models constrained by short input prefixes. By modeling short-context student features as degraded observations of teacher-derived full-context features, GDPD utilizes a diffusion-based generative prior to reconstruct and transfer missing long-range information. This approach effectively provides students with a distribution of task-relevant context, significantly improving classification accuracy under partial sequence constraints.

## Key Contributions

- Proposes GDPD, a novel knowledge distillation framework that leverages diffusion-based generative priors to bridge the generalization gap between partial and full-context time-series classifiers.
- Treats short-context student features as degraded observations of teacher features, using posterior sampling to derive task-relevant long-context target representations.
- Demonstrates consistent performance improvements across multiple earliness settings and architectures in time-series classification tasks.

## Open Questions & Future Work

- [[generalizability-of-generative-diffusion-distillation]]

## Key Concepts

- [[generative-diffusion-prior-distillation-gdpd]]: A knowledge distillation framework for time-series classification that uses a diffusion-based generative prior to guide the transfer of long-context knowledge to short-context students.

## Archivist Review

I approved the GDPD framework as a novel concept in knowledge distillation that re-frames the student-teacher context gap through a generative diffusion lens. I also approved a refined version of the open question focused on the transferability of this mechanism to other temporal and modality-constrained tasks, as this addresses the broader potential of the technique. I rejected no candidates because only these two were provided and they met the high threshold for vault inclusion.

### Approved Concepts
- Generative Diffusion Prior Distillation (GDPD): GDPD provides a novel approach to knowledge distillation for time-series classification by framing short-context student features as degraded observations of full-context teacher features, solved via diffusion-based generative priors.

### Approved Open Questions
- Generalizing Generative Diffusion Distillation: Expanding the scope of generative knowledge distillation to domains beyond time series classification and tasks beyond supervised classification is critical for demonstrating the framework's universality and addressing its limitations in diverse input spaces.

## Links

- [Abstract](https://arxiv.org/abs/2605.11414)
- [PDF](https://arxiv.org/pdf/2605.11414)

