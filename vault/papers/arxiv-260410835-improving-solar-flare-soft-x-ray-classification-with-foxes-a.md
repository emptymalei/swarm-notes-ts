---
# CSL-compatible fields
title: "Improving Solar Flare Soft X-ray Classification With FOXES: A Framework For Operational X-ray Emission Synthesis"
author:
  - literal: "Griffin T. Goodwin"
  - literal: "Alison J. March"
  - literal: "Jayant Biradar"
  - literal: "Christoph Schirninger"
  - literal: "Robert Jarolim"
  - literal: "Angelos Vourlidas"
  - literal: "Viacheslav M. Sadykov"
  - literal: "Lorien Pratt"
issued:
  date-parts:
    - [2026, 4, 12]
url: "https://arxiv.org/abs/2604.10835"

# Custom fields
paper_id: "2604.10835"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "foxes-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:04:38Z"
created_at: "2026-04-14T05:04:38Z"
---

# Improving Solar Flare Soft X-ray Classification With FOXES: A Framework For Operational X-ray Emission Synthesis

**Authors**: Griffin T. Goodwin, Alison J. March, Jayant Biradar, Christoph Schirninger, Robert Jarolim, Angelos Vourlidas, Viacheslav M. Sadykov, Lorien Pratt
**Date**: 2026-04-12
**Paper ID**: [arxiv:2604.10835](https://arxiv.org/abs/2604.10835)

## Summary

The authors present the Framework for Operational X-ray Emission Synthesis (FOXES), a Vision Transformer-based model designed to convert spatially-resolved Extreme Ultraviolet (EUV) solar observations into synthetic soft X-ray (SXR) irradiance. By generating both a global 1-8Å flux prediction and patch-wise attribution, the model addresses the lack of spatial resolution in current GOES observations. This approach enables enhanced flare detection and interpretation, providing a pathway for accurate space weather forecasting from multiple viewpoints across the heliosphere.

## Key Contributions

- Introduces FOXES, a Vision Transformer-based framework that synthesizes global and spatially-resolved 1-8Å SXR flux from EUV observations.
- Achieves a translational mean absolute error of 0.051 dex for integrated SXR measurements, outperforming single-point GOES observations by providing spatial context.
- Enables multiviewpoint monitoring of solar flares beyond Earth's line of sight by overcoming the spatial limitations inherent to GOES data.

## Open Questions & Future Work

- [[limb-flare-synthesis-limitations]]
- [[cross-platform-sxr-synthesis]]

## Key Concepts

- [[foxes-framework]]: A Vision Transformer-based framework that translates spatially-resolved EUV solar observations into synthetic global and patch-level soft X-ray irradiance.

## Archivist Review

I approved the FOXES framework as a significant methodological advancement in physical signal synthesis through vision-based attribution. The two open questions address critical bottlenecks in scaling this approach to arbitrary viewing angles and diverse mission instrumentation, which are essential for its long-term viability in operational space weather forecasting.

### Approved Concepts
- Framework for Operational X-ray Emission Synthesis (FOXES): It establishes a novel paradigm for cross-modal physical signal synthesis in solar physics, moving from point-source satellite measurements to spatially-resolved reconstructions.

### Approved Open Questions
- Limb Flare Synthesis Limitations: Addressing this is necessary to ensure consistent space weather forecasting performance regardless of the solar flare's location relative to the observer's line of sight.
- Cross-Platform SXR Synthesis Robustness: This is a prerequisite for creating a unified 'virtual GOES' capability across disparate international solar space missions.

## Links

- [Abstract](https://arxiv.org/abs/2604.10835)
- [PDF](https://arxiv.org/pdf/2604.10835)

