---
# CSL-compatible fields
title: "Statistical Study of Balmer Continuum Enhancement in Solar Flares"
author:
  - literal: "Pranjali Sharma"
  - literal: "Lucia Kleint"
  - literal: "Jonas Zbinden"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11276"

# Custom fields
paper_id: "2604.11276"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:03:33Z"
created_at: "2026-04-14T05:03:33Z"
---

# Statistical Study of Balmer Continuum Enhancement in Solar Flares

**Authors**: Pranjali Sharma, Lucia Kleint, Jonas Zbinden
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11276](https://arxiv.org/abs/2604.11276)

## Summary

This study investigates the statistical properties, spatial distribution, and temporal evolution of near-ultraviolet (NUV) continuum enhancements in solar flares using data from the Interface Region Imaging Spectrograph (IRIS). The authors developed two robust detection pipelines that filter out false positives by leveraging spatio-temporal correlations between NUV and FUV emission across 234 observed events. The results show that these enhancements are localized to flare ribbon edges and correlate positively with flare intensity, offering critical new constraints for models of chromospheric energy transport and heating mechanisms.

## Key Contributions

- Conducted a comprehensive statistical study of near-ultraviolet (NUV) continuum enhancements across 234 IRIS solar flare observations.
- Developed two independent detection pipelines that utilize spatio-temporal correspondence between NUV and FUV emission to reliably eliminate false positives.
- Established that NUV continuum enhancement magnitude increases with flare class, providing empirical constraints for solar flare simulation models.

## Open Questions & Future Work

- [[nuv-fuv-continuum-correspondence-origin]]

## Archivist Review

The paper presents a domain-specific statistical analysis of solar flare data. While the detection pipelines are useful for this specific study, they do not represent generalizable machine learning methodologies or temporal forecasting paradigms. One open question regarding the physical coupling of NUV/FUV signals was approved as it touches on a fundamental diagnostic issue for solar flare modeling.

### Approved Open Questions
- NUV/FUV continuum correspondence origin: This correspondence is a critical diagnostic tool; understanding it is essential for refining radiative hydrodynamic flare models.

### Rejected Candidates
- [open_question] NUV enhancement ribbon-front association (`nuv-enhancement-ribbon-front-association`) - paper_local: This is a specific empirical validation task rather than a fundamental unresolved research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.11276)
- [PDF](https://arxiv.org/pdf/2604.11276)

