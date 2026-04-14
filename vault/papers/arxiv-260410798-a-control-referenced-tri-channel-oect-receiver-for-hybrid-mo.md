---
# CSL-compatible fields
title: "A Control-Referenced Tri-Channel OECT Receiver for Hybrid Molecular Communication Toward Brain Organoid Interfaces"
author:
  - literal: "Hongbin Ni"
  - literal: "Ozgur B. Akan"
issued:
  date-parts:
    - [2026, 4, 12]
url: "https://arxiv.org/abs/2604.10798"

# Custom fields
paper_id: "2604.10798"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "control-referenced-molecular-receiver"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-14T05:04:50Z"
created_at: "2026-04-14T05:04:50Z"
---

# A Control-Referenced Tri-Channel OECT Receiver for Hybrid Molecular Communication Toward Brain Organoid Interfaces

**Authors**: Hongbin Ni, Ozgur B. Akan
**Date**: 2026-04-12
**Paper ID**: [arxiv:2604.10798](https://arxiv.org/abs/2604.10798)

## Summary

This paper explores a control-referenced tri-channel organic electrochemical transistor (OECT) receiver architecture designed for chemical signal readout in brain organoid interfaces. By employing a matched hydrogel control pixel alongside dopamine- and serotonin-selective pixels, the system effectively suppresses common-mode noise and low-frequency baseline drift. The authors integrate a multi-stage model covering molecular transport, sensing, and transduction, showing that this referencing technique substantially improves amplitude-based detection performance in hybrid molecular communication systems.

## Key Contributions

- Proposes a control-referenced tri-channel OECT receiver design using a dedicated hydrogel-matched pixel to mitigate common-mode drift and baseline fluctuations in molecular communication.
- Provides a comprehensive theoretical framework coupling molecular diffusion, aptamer binding, OECT transduction, and realistic noise models (thermal, flicker, and drift).
- Demonstrates that matched control referencing significantly reduces the Symbol Error Rate (SER) for Hybrid amplitude-based molecular decoding, achieving an LoD of 11866 molecules/symbol at a distance of 45 micrometers.

## Open Questions & Future Work

- [[oect-long-term-stability-drift-mitigation]]

## Key Concepts

- [[control-referenced-molecular-receiver]]: A receiver architecture utilizing a matched control sensor to suppress common-mode noise and low-frequency baseline drift in molecular communication systems.

## Archivist Review

I approved 'control-referenced-molecular-receiver' as a reusable architectural pattern for bio-chemical sensing. I also approved 'oect-long-term-stability-drift-mitigation' to capture the significant, unresolved bottleneck of sensor degradation and drift in long-term bio-interfacing applications. Other candidates were rejected to avoid duplication or excessive detail.

### Approved Concepts
- Control-Referenced Molecular Receiver: This architecture represents a fundamental technique for signal denoising in bio-interface sensing, specifically for molecular communication channels subject to drift.

### Approved Open Questions
- OECT Drift Mitigation Limits: As bio-integrated devices move from theoretical models to long-term deployment, the inability to account for physical degradation and signal drift limits the robustness of signal decoding.

### Rejected Candidates
- [open_question] OECT Receiver Stability and Mismatch (`oect-receiver-long-term-stability-and-mismatch`) - duplicate_existing: The proposed open question is a duplicate of the new 'oect-long-term-stability-drift-mitigation' entry but uses a more verbose and descriptive title.

## Links

- [Abstract](https://arxiv.org/abs/2604.10798)
- [PDF](https://arxiv.org/pdf/2604.10798)

