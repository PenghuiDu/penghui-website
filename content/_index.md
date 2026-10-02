---
# Leave the homepage title empty to use the site title
title: Penghui Du
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:

  # ---------------------------------------------------------------------------
  # NEWS
  #   Keep this to the 5-6 most recent items and delete older ones outright.
  #   A stale news list is worse than no news list.
  # ---------------------------------------------------------------------------
  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |-
        - **Oct 2026** — *iGENMap* accepted as a **Late-Breaking Abstract** at
          [SfN 2026](#talks).
        - **Mar 2026** — Started as a Visiting Graduate Student in the
          [Buckner Lab](https://bucknerlab.fas.harvard.edu) at Harvard, supported by
          the **EPFL/HMS Bertarelli Fellowship**.
        - **Mar 2026** — Our fPET-FDG metabolic connectivity paper is out in
          [*European Journal of Nuclear Medicine and Molecular Imaging*](https://doi.org/10.1007/s00259-026-08109-5).
        - **Mar 2026** — Presented our metabolic connectivity work at the
          [Molecular Connectivity Online Symposium](#talks).
        - **Oct 2025** — Conference paper on tri-modal EEG-fPET-fMRI analysis
          presented at [Asilomar 2025](https://doi.org/10.1109/IEEECONF67917.2025.11443781).
    design:
      columns: '1'

  - block: collection
    id: research
    content:
      title: Research
      text: |-
        A few of the questions I have been working on. Each links to a short write-up.
      filters:
        folders:
          - project
    design:
      columns: '2'
      # `compact` shows each project's `summary` and degrades gracefully when a
      # project has no featured image. `list` would show titles only.
      view: compact

  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        See also my [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=RMFYKDYAAAAJ).
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  - block: collection
    id: talks
    content:
      title: Talks and Posters
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact

  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:

      - title: Visiting Graduate Student
        company: Harvard University
        company_url: https://www.harvard.edu/
        company_logo: Martinos
        location: Cambridge, MA, USA
        date_start: '2026-03-02'
        date_end: '2027-02-28'
        description: |2-
            * Supervised by [Prof. Randy Buckner](https://bucknerlab.fas.harvard.edu), supported by the **EPFL/HMS Bertarelli Fellowship**.
            * **[Precision mapping for personalized TMS](#research):** comparing empirical, group-level, and individualized targeting strategies, and assessing their relative benefits and practical trade-offs.
            * **[iGENMap](#research):** developed a generative method that uses individual functional eigenmodes to map individual-specific cortical networks, matching the reliability of MS-HBM with roughly a quarter of the fMRI data.

      - title: Summer Intern
        company: Max Planck Institute for Human Cognitive and Brain Sciences
        company_url: https://www.cbs.mpg.de/en
        company_logo: MPI
        location: Leipzig, Germany
        date_start: '2025-06-01'
        date_end: '2025-08-31'
        description: |2-
            * [Cognitive Neurogenetics Lab](https://cng-lab.github.io), supervised by Dr. Bin Wan and Prof. Sofie Valk.
            * **[Predicting glucose metabolism from MRI](#research):** built a deep learning framework to predict individual brain glucose metabolism from structural and functional MRI features.

      - title: Master Student in Neuro-X
        company: École Polytechnique Fédérale de Lausanne (EPFL)
        company_url: 'https://www.epfl.ch/'
        company_logo: epfl
        location: Ecublens, Switzerland
        date_start: '2024-09-01'
        date_end: '2027-02-28'
        description: |2-
            * **GPA:** 5.40 / 6 · **EPFL/HMS Bertarelli Fellowship**
            * **[Semester project at MIP Lab](#research)** (2025/09 - 2026/01), supervised by Michael Chan and [Prof. Dimitri Van De Ville](https://miplab.epfl.ch): characterized structure-informed functional connectivity using statistical signal analysis on graphs.

      - title: Undergraduate Research Assistant
        company: Martinos Center for Biomedical Imaging, Harvard Medical School
        company_url: 'https://www.martinos.org/'
        company_logo: Martinos
        location: Charlestown, MA, USA
        date_start: '2023-07-05'
        date_end: '2023-12-20'
        description: |2-
            * Supervised by [Prof. Jingyuan Chen](https://jechenlab.com/).
            * **[Cortical organization of metabolic connectivity](#research):** characterized resting-state fPET-FDG metabolic connectivity, identifying a robust superior-inferior gradient driven by low-frequency dynamics. Published in *Eur J Nucl Med Mol Imaging*.

      - title: Visiting Student in Neuroinformatics
        company: University of Zurich
        company_url: 'https://uzh.ch/cmsssl/en.html'
        company_logo: UZH
        location: Zurich, Switzerland
        date_start: '2023-02-01'
        date_end: '2023-06-15'
        description: |2-
            * Exchange semester in the Neuroinformatics program, jointly run by the University of Zurich and ETH Zurich.

      - title: BSc in Intelligent Medical Engineering
        company: Southern University of Science and Technology
        company_url: 'https://www.sustech.edu.cn'
        company_logo: sustech
        location: Shenzhen, China
        date_start: '2020-08-27'
        date_end: '2024-06-27'
        description: |2-
            * Academic supervisor: Dr. Quanying Liu.
            * **GPA:** 3.84 / 4 (92.79), ranked **2 / 22**.
            * **2024 Distinguished Graduate Award**; BME "Fortunatt" Scholarship (2022); SUSTech Outstanding Student Scholarship (2022).

    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        The fastest way to reach me is email.
      # Contact (add or remove contact options as necessary)
      email: penghui-du@outlook.com
      address:
        street: 52 Oxford Street
        city: Cambridge
        region: MA
        postcode: '02138'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'

  - block: markdown
    id: gallery
    content:
      title: Beyond the Lab
      subtitle: ''
      text: |-
        {{< gallery album="my_album" >}}
    design:
      columns: '1'
---
