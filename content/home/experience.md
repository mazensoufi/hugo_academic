---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006
active: true
# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Assistant Professor
    company: Nara Institute of Science and Technology, Imaging-based Computational Biomedicine Lab (ICB lab)
    company_url: 'http://icb-lab.naist.jp/english/index.html'
    company_logo: naist
    location: Nara, Japan
    date_start: '2018-02-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        * Master/PhD course student research mentorship
        * Research and development: multiple projects involving MRI, CT and histopathology image analysis
        * Teaching (limited)
        * Lab environment duties (GPU cluster "slurm+singularity/docker" and data servers "Windows Server, NAS" management, Fujifilm Vincent Workstaion)
        * Operation of standing MRI scanner (E-MRI Brio G-Scan, Esaote) for image acquisition
        
  - title: Visiting Scientist
    company: University Hospital Bonn, Computational Imaging Reserach (Albarqouni Lab)
    company_url: 'https://albarqouni.github.io/'
    company_logo: ukb
    location: Bonn, Germany
    date_start: '2022-12-05'
    date_end: '2023-03-31'
    description: Research visit on the application of federated learning for musculoskeletal segemtnation in CT images.

  - title: Post-doctoral Researcher (PD-JSPS)
    company: Kyushu University, Artificial intelligence-based Diagnostic and Treatment Systems (Arimura Lab)
    company_url: 'http://web.shs.kyushu-u.ac.jp/~arimura/'
    company_logo: kyushu
    location: Fukuoka, Japan
    date_start: '2017-10-01'
    date_end: '2018-01-31'
    description: Research on applications of radiomics in cancer patient progonostic prediction. I particularly investigated the temporal stability of radiomic features in lung cancer patient imaging based on EPID images, and the identifying the optimal radiomic wavelet features for prognostic prediction of lung cancer patients from CT images.


design:
  columns: '2'
---
