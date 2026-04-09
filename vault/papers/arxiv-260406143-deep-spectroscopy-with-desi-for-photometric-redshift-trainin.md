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
domain: "computer-vision"
tags:
  - "computer-vision"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-09T04:56:47Z"
created_at: "2026-04-09T04:56:47Z"
---

# Deep Spectroscopy with DESI for Photometric Redshift Training and Calibration

**Authors**: Biprateep Dey, Jeffrey A. Newman, Tianqing Zhang, J. Aguilar, S. Ahlen, A. Anand, B. Andrews, S. Bailey, D. Bianchi, D. Brooks, F. J. Castander, T. Claybaugh, A. Cuceu, K. S. Dawson, A. de la Macorra, J. Della Costa, Arjun Dey, P. Doel, S. Ferraro, A. Font-Ribera, E. Gaztañaga, Satya Gontcho A Gontcho, D. Gruen, G. Gutierrez, J. Guy, H. K. Herrera-Alcantar, K. Honscheid, M. Ishak, R. Joyce, R. Kehoe, D. Kirkby, T. Kisner, A. Kremin, O. Lahav, M. Landriau, L. Le Guillou, A. Leauthaud, M. E. Levi, M. Manera, P. Martini, J. McCullough, A. Meisner, R. Miquel, J. Moustakas, A. D. Myers, J. Myles, S. Nadathur, N. Palanque-Delabrouille, W. J. Percival, F. Prada, I. Pérez-Ràfols, G. Rossi, L. Samushia, E. Sanchez, D. Schlegel, M. Schubnell, H. Seo, J. Silber, D. Sprayberry, G. Tarlé, B. A. Weaver, N. Weaverdyck, R. H. Wechsler, R. Zhou, H. Zou
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.06143](https://arxiv.org/abs/2604.06143)

## Summary

This paper reports on the 'DESI-Deep pilot' program, which evaluates the capacity of the Dark Energy Spectroscopic Instrument (DESI) to provide precise redshift measurements for faint galaxies (m_i <= 24.5) essential for calibrating photometric redshift estimates. The study finds that DESI achieves exceptional efficiency and multiplexing compared to 10m-class telescopes, making it a highly effective facility for generating benchmark samples for future imaging surveys like LSST. These findings provide a clear roadmap for using DESI-Deep observations to mitigate systematic errors in cosmological inference.

## Key Contributions

- Demonstrated that the Dark Energy Spectroscopic Instrument (DESI) achieves high redshift success rates for faint targets (m_i <= 24.5) comparable to 10m-class telescopes with significantly higher multiplexing.
- Validated that DESI's signal-to-noise ratio remains background-limited even for extended exposure times (up to ~7 hours).
- Developed a strategy for using deep spectroscopic samples to train and calibrate photometric redshift (photo-z) estimates for large-scale imaging surveys like the Vera C. Rubin Observatory's LSST.

## Open Questions & Future Work

- [[automated-redshift-reliability-metrics]]
- [[cosmological-impact-spectroscopic-incompleteness]]

## Archivist Review

The paper provides a domain-specific evaluation of DESI for calibrating future photometric redshift surveys. I have approved two open questions that capture the fundamental statistical and reliability challenges in scaling spectroscopic training sets for cosmology. No new concepts or datasets were approved as the findings are primarily domain-specific empirical results within astrophysics rather than reusable ML methodology.

### Approved Open Questions
- Automated Redshift Reliability Metrics: Automated reliability assessment is crucial for scaling spectroscopic training sets to the size and depth required for future imaging experiments like LSST, as manual visual inspection campaigns are not sustainable at large scales.
- Cosmological Impact of Incompleteness: A better understanding of how spectroscopic incompleteness maps into cosmological biases is essential for designing efficient training sets that maximize the constraining power of upcoming surveys like LSST.

## Links

- [Abstract](https://arxiv.org/abs/2604.06143)
- [PDF](https://arxiv.org/pdf/2604.06143)

