---
title: ""
date: 2026-11-26
type: landing
design:
  spacing: "6rem"
sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV (Word)
        url: uploads/CV_JaeseLee_2026.docx
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: research
    content:
      title: My Research
      subtitle: Microwave remote sensing of soil moisture and vegetation
      text: |-
        **Physics-informed retrieval.** I combine radiative transfer modeling and deep learning to estimate soil moisture and vegetation properties from passive and active microwave observations. Recent work addresses time-varying vegetation scattering in SMAP retrievals and soil moisture and surface roughness estimation from ALOS-2 PALSAR-2 observations.

        **Satellite data harmonization.** I develop methods to translate observations across sensors, including ASCAT2SMAP, ASCAT2SMAP-V2, and ASTRA. These approaches connect C-band and L-band observations to support consistent soil moisture and vegetation optical depth estimates.

        **Ecohydrological applications.** I investigate soil moisture–vegetation relationships and contribute to research on drought monitoring, wildfire assessment, and environmental reconstruction from satellite data.

        I welcome collaborations on microwave remote sensing, soil moisture, vegetation dynamics, and physics-informed learning. [Get in touch](mailto:jaeselee@gist.ac.kr).
    design:
      columns: '1'
  - block: research-resources
    id: highlights
  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: 'See [all publications](/publication/) and [manuscripts under review or revision](/manuscripts/).'
      count: 6
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
