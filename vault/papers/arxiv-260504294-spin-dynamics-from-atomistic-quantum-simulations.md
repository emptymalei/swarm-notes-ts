---
# CSL-compatible fields
title: "Spin Dynamics from Atomistic Quantum Simulations"
author:
  - literal: "Enrico Drigo"
  - literal: "Marquis M. McMillan"
  - literal: "Benjamin Pingault"
  - literal: "Yinan Dong"
  - literal: "F. Joseph Heremans"
  - literal: "David D. Awschalom"
  - literal: "Giulia Galli"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.04294"

# Custom fields
paper_id: "2605.04294"
paper_source: "arxiv"
domain: "computer-vision"
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
skill: "GeneralMLSkill"
processed_at: "2026-05-07T05:16:05Z"
created_at: "2026-05-07T05:16:05Z"
---

# Spin Dynamics from Atomistic Quantum Simulations

**Authors**: Enrico Drigo, Marquis M. McMillan, Benjamin Pingault, Yinan Dong, F. Joseph Heremans, David D. Awschalom, Giulia Galli
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.04294](https://arxiv.org/abs/2605.04294)

## Summary

This paper presents a theoretical framework for predicting spin dynamics in solid-state quantum defects at elevated temperatures by relating spin-lattice and decoherence times to correlation functions of spin-lattice couplings via Kubo linear-response theory. The methodology integrates molecular dynamics simulations with machine learning-accelerated ab-initio spin-lattice interaction models to capture complex dynamics. The approach is successfully validated through comparison with experimental T1 data for the NV center in diamond.

## Key Contributions

- Derives expressions for spin-lattice (T1) and decoherence (T2) times using Kubo linear-response theory based on spin-lattice coupling correlation functions.
- Combines atomistic molecular dynamics with ML-based ab-initio spin-lattice interaction modeling to predict quantum defect dynamics at high temperatures.
- Validates the theoretical framework against experimental T1 measurements for the NV center in diamond, demonstrating high accuracy.

## Open Questions & Future Work

- [[multi-defect-cooperative-dynamics-modeling]]

## Archivist Review

The paper proposes a specific application of Kubo linear-response theory coupled with ML-accelerated molecular dynamics to predict quantum defect spin-lattice relaxation. While methodologically sound, the approach is highly domain-specific to atomistic physics; no standalone concepts were found that represent reusable ML architectural patterns or methodological primitives distinct from existing physics-informed ML approaches. One open question regarding multi-defect interaction modeling was retained, as it represents a significant, non-routine research frontier in the simulation of quantum materials.

### Approved Open Questions
- Multi-defect cooperative dynamics modeling: This is a fundamental bottleneck for applying atomistic spin-dynamics simulations to realistic high-density quantum device architectures.

### Rejected Candidates
- [open_question] Modeling multiple spin defects (`multi-defect-zfs-modeling`) - other: Renamed to be more descriptive of the broader physical modeling challenge beyond just ZFS.

## Links

- [Abstract](https://arxiv.org/abs/2605.04294)
- [PDF](https://arxiv.org/pdf/2605.04294)

