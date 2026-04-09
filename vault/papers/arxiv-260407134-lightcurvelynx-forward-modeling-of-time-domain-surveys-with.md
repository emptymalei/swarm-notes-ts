---
# CSL-compatible fields
title: "LightCurveLynx: Forward Modeling of Time-Domain Surveys with Application to ZTF SN Ia DR2"
author:
  - literal: "Mi Dai"
  - literal: "Jeremy Kubica"
  - literal: "Konstantin Malanchev"
  - literal: "Alex I. Malz"
  - literal: "Olivia Lynn"
  - literal: "Andrew Connolly"
  - literal: "Rachel Mandelbaum"
  - literal: "W. M. Wood-Vasey"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07134"

# Custom fields
paper_id: "2604.07134"
paper_source: "arxiv"
domain: "astronomy"
tags:
  []
architectures:
  []
datasets:
  - "ztf-sn-ia-dr2"
concept_slugs:
  []
dataset_slugs:
  - "ztf-sn-ia-dr2"
skill: "GeneralMLSkill"
processed_at: "2026-04-09T04:53:48Z"
created_at: "2026-04-09T04:53:48Z"
---

# LightCurveLynx: Forward Modeling of Time-Domain Surveys with Application to ZTF SN Ia DR2

**Authors**: Mi Dai, Jeremy Kubica, Konstantin Malanchev, Alex I. Malz, Olivia Lynn, Andrew Connolly, Rachel Mandelbaum, W. M. Wood-Vasey
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07134](https://arxiv.org/abs/2604.07134)

## Summary

LightCurveLynx is an extensible software framework designed for high-fidelity forward modeling of time-domain astronomical light curves. It enables researchers to simulate survey data based on real metadata, prospective survey strategies, or custom configurations, facilitating pipeline validation and inference studies. The framework is validated against the ZTF SN Ia Data Release 2, demonstrating excellent statistical agreement in both parameter distributions and noise characteristics.

## Key Contributions

- Introduced LightCurveLynx, an extensible framework for end-to-end forward modeling of astronomical time-domain light curves.
- Demonstrated simulation fidelity by replicating ZTF SN Ia DR2 parameter distributions with KL divergence values of 0.01-0.02.
- Validated simulation-based inference capabilities by confirming redshift completeness limits consistent with previous empirical studies.

## Open Questions & Future Work

- [[supernova-simulation-noise-modeling]]

## Archivist Review

The review process focused on identifying reusable scientific contributions versus software-specific tools. LightCurveLynx was rejected as a concept because it is a specific software implementation rather than a general method. The ZTF SN Ia DR2 dataset was approved as a standard reference point for astronomical survey evaluation, and the noise modeling question was approved as a substantive research challenge in simulation fidelity.

### Approved Open Questions
- Refining Supernova Light Curve Noise: Accurate noise estimation is critical for characterizing systematic biases and for reliable cosmological inference in time-domain surveys; discrepancies between simulations and real data hinder the validation of analysis pipelines.

### Rejected Candidates
- [concept] LightCurveLynx (`lightcurvelynx`) - paper_local: This is a specific software framework/tool rather than a reusable architectural pattern or ML concept.

## Datasets

- [[ztf-sn-ia-dr2]]

## Links

- [Abstract](https://arxiv.org/abs/2604.07134)
- [PDF](https://arxiv.org/pdf/2604.07134)

