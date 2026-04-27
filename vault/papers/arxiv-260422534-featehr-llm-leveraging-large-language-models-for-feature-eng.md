---
# CSL-compatible fields
title: "FeatEHR-LLM: Leveraging Large Language Models for Feature Engineering in Electronic Health Records"
author:
  - literal: "Hojjat Karami"
  - literal: "David Atienza"
  - literal: "Jean-Philippe Thiran"
  - literal: "Anisoara Ionescu"
issued:
  date-parts:
    - [2026, 4, 24]
url: "https://arxiv.org/abs/2604.22534"

# Custom fields
paper_id: "2604.22534"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
  - "healthcare"
  - "feature-engineering"
  - "llm"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-27T05:11:06Z"
created_at: "2026-04-27T05:11:06Z"
---

# FeatEHR-LLM: Leveraging Large Language Models for Feature Engineering in Electronic Health Records

**Authors**: Hojjat Karami, David Atienza, Jean-Philippe Thiran, Anisoara Ionescu
**Date**: 2026-04-24
**Paper ID**: [arxiv:2604.22534](https://arxiv.org/abs/2604.22534)

## Summary

FeatEHR-LLM is an automated feature engineering framework designed to address the challenges of irregular sampling and sparsity in Electronic Health Records. By combining tool-augmented generation with a schema-first approach, the LLM produces executable code for temporal feature extraction without accessing sensitive raw patient data. The system utilizes an iterative, validation-in-the-loop pipeline to refine features, demonstrating state-of-the-art results on standard clinical ICU prediction benchmarks.

## Key Contributions

- Introduced FeatEHR-LLM, a framework for generating clinically meaningful tabular features from irregular EHR time series using tool-augmented LLMs.
- Developed a privacy-preserving schema-based generation approach that avoids exposing raw patient records to the LLM.
- Achieved superior performance on eight clinical prediction tasks across four ICU datasets, outperforming baseline feature engineering methods by up to 6 percentage points in AUROC.

## Open Questions & Future Work

- [[modeling-missing-data-mechanisms-in-llm-feature-engineering]]

## Archivist Review

The paper presents a specific application of tool-augmented LLMs for feature engineering, but does not offer a novel or widely reusable methodology beyond established practices. The proposed open question regarding missing data mechanisms in clinical settings is a significant, tracking-worthy challenge that persists across healthcare AI research, justifying its inclusion.

### Approved Open Questions
- Modeling Missing Data Mechanisms: Modeling the mechanism of missingness is critical for clinical decision support, as the decision to order a test is often correlated with the patient's condition, and ignoring this may lead to biased predictions.

### Rejected Candidates
- [concept] FeatEHR-LLM (`featehr-llm`) - paper_local: This is a specific framework name rather than a transferable methodological concept or principle.

## Links

- [Abstract](https://arxiv.org/abs/2604.22534)
- [PDF](https://arxiv.org/pdf/2604.22534)

