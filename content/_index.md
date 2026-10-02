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
        - **Sep 2026:** 🧠 *iGENMap* was accepted as a **Late-Breaking Abstract** at
          [SfN 2026](#talks). See you in Washington, DC!
        - **Aug 2026:** 🎉 Our fPET-FDG metabolic connectivity paper is finally out in
          [*European Journal of Nuclear Medicine and Molecular Imaging*](https://doi.org/10.1007/s00259-026-08109-5)!
        - **Mar 2026:** 📄 Our conference paper on tri-modal EEG-fPET-fMRI analysis is
          now online in the
          [Asilomar 2025](https://doi.org/10.1109/IEEECONF67917.2025.11443781)
          proceedings.
        - **Mar 2026:** 🎤 Presented our metabolic connectivity work at the
          [Molecular Connectivity Online Symposium](#talks).
        - **Mar 2026:** 🔬 Started as a Visiting Graduate Student in the
          [Buckner Lab](https://bucknerlab.fas.harvard.edu) at Harvard, supported by
          the **EPFL/HMS Bertarelli Fellowship**. Excited for the year ahead!
        - **Aug 2024:** 📚 Began the MSc in Neuro-X at EPFL.
        - **Jul 2024:** 🎓 Graduated from SUSTech with a BSc in Intelligent Medical
          Engineering and the **2024 Distinguished Graduate Award**!
    design:
      columns: '1'

  - block: collection
    id: research
    content:
      title: Research
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
            * [Buckner Lab](https://bucknerlab.fas.harvard.edu), supervised by Prof. Randy Buckner.
            * Supported by the **EPFL/HMS Bertarelli Fellowship**.

      - title: Summer Intern
        company: Max Planck Institute for Human Cognitive and Brain Sciences
        company_url: https://www.cbs.mpg.de/en
        company_logo: MPI
        location: Leipzig, Germany
        date_start: '2025-06-01'
        date_end: '2025-08-31'
        description: |2-
            * [Cognitive Neurogenetics Lab](https://cng-lab.github.io), supervised by Dr. Bin Wan and Prof. Sofie Valk.

      - title: Master Student in Neuro-X
        company: École Polytechnique Fédérale de Lausanne (EPFL)
        company_url: 'https://www.epfl.ch/'
        company_logo: epfl
        location: Ecublens, Switzerland
        date_start: '2024-09-01'
        date_end: '2027-02-28'
        description: |2-
            * **GPA:** 5.40 / 6
            * **EPFL/HMS Bertarelli Fellowship**

      - title: Undergraduate Research Assistant
        company: Martinos Center for Biomedical Imaging, Harvard Medical School
        company_url: 'https://www.martinos.org/'
        company_logo: Martinos
        location: Charlestown, MA, USA
        date_start: '2023-07-05'
        date_end: '2023-12-20'
        description: |2-
            * Supervised by [Prof. Jingyuan Chen](https://jechenlab.com/).

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
      title: Photos
      subtitle: ''
      text: |-
        {{< gallery album="my_album" >}}
    design:
      columns: '1'
---
