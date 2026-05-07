---
# CSL-compatible fields
title: "From Classical to Quantum-Mechanical Data Assimilation: A Comparison between DATO and QMDA"
author:
  - literal: "Emanuele Donno"
  - literal: "Giovanni Conti"
  - literal: "Paolo Oddo"
  - literal: "Silvio Gualdi"
  - literal: "Luca Mainetti"
  - literal: "Giovanni Aloisio"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04881"

# Custom fields
paper_id: "2605.04881"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dato-da"
  - "qmda-da"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-07T05:14:52Z"
created_at: "2026-05-07T05:14:52Z"
---

# From Classical to Quantum-Mechanical Data Assimilation: A Comparison between DATO and QMDA

**Authors**: Emanuele Donno, Giovanni Conti, Paolo Oddo, Silvio Gualdi, Luca Mainetti, Giovanni Aloisio
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04881](https://arxiv.org/abs/2605.04881)

## Summary

This paper presents a comparative study of two operator-theoretic data assimilation frameworks: Data Assimilation with Transfer Operators (DATO) and Quantum Mechanical Data Assimilation (QMDA). By casting both methods into a unified mathematical structure, the authors evaluate their respective performance, interpretability, and computational scalability. Through empirical testing on dynamical system benchmarks, the study identifies distinct operational regimes where each framework excels, providing guidance for future research in operator-based data assimilation.

## Key Contributions

- Provides a unified operator-theoretic framework to map and compare Data Assimilation with Transfer Operators (DATO) and Quantum Mechanical Data Assimilation (QMDA).
- Systematically analyzes differences between DATO and QMDA regarding state-space structure, update mechanisms, and structural preservation.
- Empirically benchmarks DATO and QMDA across various dynamical systems under noisy, sparse, and partial observational regimes to identify regime-specific performance advantages.

## Open Questions & Future Work

- [[qmda-diagnostics-derivation]]
- [[non-stationary-operator-da]]

## Key Concepts

- [[dato-da]]: A data assimilation framework that leverages transfer operators to represent uncertainty propagation and assimilation updates within an operator-theoretic structure.
- [[qmda-da]]: A data assimilation paradigm that frames state inference as a quantum measurement process using the von Neumann postulate.

## Archivist Review

I have approved DATO and QMDA as core concepts because they represent distinct, foundational paradigms in operator-theoretic data assimilation that serve as reference points for future comparative research. The open questions were approved as they identify fundamental theoretical gaps in diagnostics and stationarity that limit the applicability of current operator-based assimilation frameworks in operational and non-stationary contexts.

### Approved Concepts
- Data Assimilation with Transfer Operators (DATO): It represents a distinct class of operator-theoretic data assimilation that warrants separate categorization from standard classical methods.
- Quantum Mechanical Data Assimilation (QMDA): QMDA introduces a specific paradigm shift by casting data assimilation as a quantum measurement problem, providing a novel algorithmic structure distinct from classical Bayesian or operator-based approaches.

### Approved Open Questions
- Diagnostics for QMDA framework: Diagnostics like OI and FSOI are critical for understanding the sensitivity of an assimilation system to observations and for monitoring its performance; without them, QMDA is less transparent in operational settings.
- DA for non-stationary dynamics: Many real-world dynamical systems exhibit non-stationary behaviors, making the assumption of a static invariant measure a major limitation for long-term assimilation stability and accuracy.

## Links

- [Abstract](https://arxiv.org/abs/2605.04881)
- [PDF](https://arxiv.org/pdf/2605.04881)

