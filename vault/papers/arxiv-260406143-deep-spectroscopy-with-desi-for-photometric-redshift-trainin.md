---
# CSL-compatible fields
title: "Deep Spectroscopy with DESI for Photometric Redshift Training and Calibration"
author:
  - literal: "Biprateep Dey"
  - literal: "Jeffrey A. Newman"
  - literal: "Tianqing Zhang"
  - literal: "J. Aguilar"
  - literal: "S. Ahlen"
  - literal: "A. Anand"
  - literal: "B. Andrews"
  - literal: "S. Bailey"
  - literal: "D. Bianchi"
  - literal: "D. Brooks"
  - literal: "F. J. Castander"
  - literal: "T. Claybaugh"
  - literal: "A. Cuceu"
  - literal: "K. S. Dawson"
  - literal: "A. de la Macorra"
  - literal: "J. Della Costa"
  - literal: "Arjun Dey"
  - literal: "P. Doel"
  - literal: "S. Ferraro"
  - literal: "A. Font-Ribera"
  - literal: "E. Gaztañaga"
  - literal: "Satya Gontcho A Gontcho"
  - literal: "D. Gruen"
  - literal: "G. Gutierrez"
  - literal: "J. Guy"
  - literal: "H. K. Herrera-Alcantar"
  - literal: "K. Honscheid"
  - literal: "M. Ishak"
  - literal: "R. Joyce"
  - literal: "R. Kehoe"
  - literal: "D. Kirkby"
  - literal: "T. Kisner"
  - literal: "A. Kremin"
  - literal: "O. Lahav"
  - literal: "M. Landriau"
  - literal: "L. Le Guillou"
  - literal: "A. Leauthaud"
  - literal: "M. E. Levi"
  - literal: "M. Manera"
  - literal: "P. Martini"
  - literal: "J. McCullough"
  - literal: "A. Meisner"
  - literal: "R. Miquel"
  - literal: "J. Moustakas"
  - literal: "A. D. Myers"
  - literal: "J. Myles"
  - literal: "S. Nadathur"
  - literal: "N. Palanque-Delabrouille"
  - literal: "W. J. Percival"
  - literal: "F. Prada"
  - literal: "I. Pérez-Ràfols"
  - literal: "G. Rossi"
  - literal: "L. Samushia"
  - literal: "E. Sanchez"
  - literal: "D. Schlegel"
  - literal: "M. Schubnell"
  - literal: "H. Seo"
  - literal: "J. Silber"
  - literal: "D. Sprayberry"
  - literal: "G. Tarlé"
  - literal: "B. A. Weaver"
  - literal: "N. Weaverdyck"
  - literal: "R. H. Wechsler"
  - literal: "R. Zhou"
  - literal: "H. Zou"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.06143"

# Custom fields
paper_id: "2604.06143"
paper_source: "arxiv"
domain: "other"
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
processed_at: "2026-04-08T04:54:38Z"
created_at: "2026-04-08T04:54:38Z"
---

# Deep Spectroscopy with DESI for Photometric Redshift Training and Calibration

**Authors**: Biprateep Dey, Jeffrey A. Newman, Tianqing Zhang, J. Aguilar, S. Ahlen, A. Anand, B. Andrews, S. Bailey, D. Bianchi, D. Brooks, F. J. Castander, T. Claybaugh, A. Cuceu, K. S. Dawson, A. de la Macorra, J. Della Costa, Arjun Dey, P. Doel, S. Ferraro, A. Font-Ribera, E. Gaztañaga, Satya Gontcho A Gontcho, D. Gruen, G. Gutierrez, J. Guy, H. K. Herrera-Alcantar, K. Honscheid, M. Ishak, R. Joyce, R. Kehoe, D. Kirkby, T. Kisner, A. Kremin, O. Lahav, M. Landriau, L. Le Guillou, A. Leauthaud, M. E. Levi, M. Manera, P. Martini, J. McCullough, A. Meisner, R. Miquel, J. Moustakas, A. D. Myers, J. Myles, S. Nadathur, N. Palanque-Delabrouille, W. J. Percival, F. Prada, I. Pérez-Ràfols, G. Rossi, L. Samushia, E. Sanchez, D. Schlegel, M. Schubnell, H. Seo, J. Silber, D. Sprayberry, G. Tarlé, B. A. Weaver, N. Weaverdyck, R. H. Wechsler, R. Zhou, H. Zou
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.06143](https://arxiv.org/abs/2604.06143)

## Summary

This paper presents the results of the 'DESI-Deep pilot' program, evaluating the suitability of the Dark Energy Spectroscopic Instrument (DESI) for training and calibrating photometric redshift estimates for future wide-field imaging surveys like LSST. The study demonstrates that DESI achieves high redshift success rates for faint targets (m_i <= 24.5) with significantly higher multiplexing capabilities than 10m-class telescopes. These findings provide a strategic foundation for designing a dedicated spectroscopic survey to mitigate systematic uncertainties in cosmological inference for upcoming imaging experiments.

## Key Contributions

- Demonstrated that the DESI facility is highly efficient for faint galaxy redshift measurements, matching 10m-class telescope performance with ~30x greater multiplexing.
- Validated that signal-to-noise ratios follow background-limited scaling for deep exposures (up to 7 hours) at m_i <= 24.5.
- Provided updated time-requirement predictions for spectroscopic calibration samples of imaging-based cosmological surveys.

## Open Questions & Future Work

- [[automated-redshift-reliability-metrics]]

## Archivist Review

The paper provides an empirical evaluation of spectroscopic hardware for astrophysical survey design. It does not introduce reusable machine learning methodologies, architectures, or unique datasets. I approved the open question regarding automated redshift reliability, as it identifies a clear, persistent bottleneck in automating scientific pipeline quality control for large-scale astronomical data analysis.

### Approved Open Questions
- Automated Redshift Reliability Metrics: Automated reliability metrics are essential for scaling deep spectroscopic surveys to the sample sizes required for next-generation photometric redshift calibration (e.g., for LSST), as manual inspection is too labor-intensive for the tens of thousands of spectra needed.

### Rejected Candidates
- [concept] DESI-Deep Pilot (`desi-deep-pilot`) - paper_local: This is a specific, one-off project or survey program rather than a reusable architectural pattern or ML method.

## Links

- [Abstract](https://arxiv.org/abs/2604.06143)
- [PDF](https://arxiv.org/pdf/2604.06143)

