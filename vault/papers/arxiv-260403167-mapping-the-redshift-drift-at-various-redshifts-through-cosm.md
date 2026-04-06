---
# CSL-compatible fields
title: "Mapping the redshift drift at various redshifts through cosmography"
author:
  - literal: "Anna Chiara Alfano"
  - literal: "Orlando Luongo"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.03167"

# Custom fields
paper_id: "2604.03167"
paper_source: "arxiv"
domain: "cosmology"
tags:
  - "cosmology"
  - "cosmography"
  - "redshift-drift"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-06T05:01:55Z"
created_at: "2026-04-06T05:01:55Z"
---

# Mapping the redshift drift at various redshifts through cosmography

**Authors**: Anna Chiara Alfano, Orlando Luongo
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.03167](https://arxiv.org/abs/2604.03167)

## Summary

This paper examines the redshift drift as a kinematic probe of cosmic expansion, utilizing cosmographic frameworks based on Taylor expansions and Padé approximants. By combining various observational datasets including SNeIa, GRBs, and DESI BAO measurements, the authors constrain cosmological parameters and evaluate their consistency with $\Lambda$CDM and $w_0w_1$CDM paradigms. The study demonstrates how future Sandage-Loeb data can refine current estimates of deceleration and jerk parameters, while highlighting tensions that arise when incorporating different data combinations.

## Key Contributions

- Evaluated redshift drift using cosmographic parameterizations (Taylor expansion and Padé approximants) to test consistency with expansion models.
- Constrained (H0, q0, j0) parameters using Pantheon+, SH0ES, GRBs, and DESI DR2 BAO data.
- Assessed the potential of mock Sandage-Loeb catalogs to improve constraints on deceleration (q0) and jerk (j0) parameters.

## Open Questions & Future Work

- [[model-independent-bao-extraction]]

## Archivist Review

This paper applies standard cosmological techniques (cosmography using Taylor/Padé expansions) to evaluate model consistency. It does not introduce new machine learning methodology. The open question regarding model-independent BAO extraction is a significant, ongoing methodological challenge in physical cosmology and is therefore approved for tracking.

### Approved Open Questions
- Model-independent BAO distance extraction: The reliance of current BAO measurements on fiducial models limits their ability to independently test alternative dark energy scenarios, potentially obscuring evidence for non-standard physics.

### Rejected Candidates
- [concept] Cosmographic Frameworks (`cosmographic-frameworks`) - not_novel: Cosmography is a standard astronomical methodology rather than a novel ML-specific reusable concept.
- [concept] Redshift Drift Analysis (`redshift-drift-analysis`) - not_reusable: This is a domain-specific research task rather than a reusable architectural or algorithmic concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.03167)
- [PDF](https://arxiv.org/pdf/2604.03167)

