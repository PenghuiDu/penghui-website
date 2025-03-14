---
# Leave the homepage title empty to use the site title
title: Penghui's Website
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

        - title: Master Student in Neuro-X
          company: École Polytechnique Fédérale de Lausanne (EPFL)
          company_url: 'https://www.epfl.ch/'
          company_logo: epfl
          location: Ecublens, Switzerland
          date_start: '2024-09-01'


        - title: Undergraduate Research Assistant
          company: Martinos Center for Biomedical Imaging, Harvard Medical School
          company_url: 'https://www.martinos.org/'
          company_logo: Martinos
          location: Charlestown, Unites States
          date_start: '2023-07-05'
          date_end: '2023-12-20'
          description: |2-
              * **Supervisor:** Dr. Jingyuan Chen (https://jechenlab.com/)
              * **Research Focus:** Human Cerebral Cortex Organization Estimated by Functional PET-FDG "Metabolic Connectivity"

  
        - title: Regular Visiting Student in Neuroinformatics
          company: University of Zurich
          company_url: 'https://uzh.ch/cmsssl/en.html'
          company_logo: UZH
          location: Zurich, Switzerland
          date_start: '2023-02-01'
          date_end: '2023-06-15'
      

        - title: BSc in Intelligent Medical Engineering
          company: Southern University of Science and Technology
          company_url: 'https://www.sustech.edu.cn'
          company_logo: sustech
          location: Shenzhen, China
          date_start: '2020-08-27'
          date_end: '2024-06-27'
          description: |2-
              * **Academic Supervisor:** Dr. Quanying Liu
              * **GPA:** 3.84 / 4 (92.79), Ranking 2 / 22
              * 2024 Outstanding BSc Award
              * 2022 BME "Fortunatt" Scholarship
              * 2022 Outstanding Student Scholarships (First Prize)
        

    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:

        - certificate_url: https://penghui-du.com/uploads/challenge_cup.pdf
          date_end: '2022-05-01'
          date_start: '2021-11-01'
          description: 'We designed a business plan for manufactoring seizure monitor devices for severely ill newborns, and won first prize in the competition. I am team captain in this competition, and I am responsible for proposing technical ideas and designing business plan.'
          organization: Department of Education of Guangdong Province
          organization_url: http://edu.gd.gov.cn/
          title: 'First prize in 13th "Challenge Cup" Entrepreneurship Competition.'
          url: ''

        - certificate_url: https://penghui-du.com/uploads/neuromatch.pdf
          date_end: ''
          date_start: '2022-07-30'
          description: 'I studied computational neuroscience fundamentals such as reinforcement learning, leaky Integrate-and-Fire models, Hodgkin-Huxley models with my teammates. We then conducted an project on RNN and working memory, and presented our results to other teams.'
          organization: Neuromatch Academy
          organization_url: https://neuromatch.io/
          title: 2022 Neuromatch Computational Neuroscience Summer School
          url: ''

        - certificate_url: https://penghui-du.com/uploads/CLS-CIBR-IDG.jpg
          date_end: ''
          date_start: '2022-07-10'
          description: 'I attended various neuroscience lectures in the summer school, followed by our teams presentation on a chosen paper. I was recognized with a Merit Student Award.'
          organization: Tsinghua University and Peking University
          organization_url: http://mcgovern.life.tsinghua.edu.cn
          title: Merit Student of CLS-CIBR-IDG Summer School in Neuroscience
          url: ''

        - certificate_url: https://penghui-du.com/uploads/bme.jpg
          date_end: '2022-07-01'
          date_start: '2022-03-20'
          description: 'We designed a deep learning model, combining Transformer and UNet, for labeling the key organs involved in radiotherapy in CT images. Our unique pre-training approach ensured high segmentation accuracy and reduced computational cost, earning us first prize in the competition.'
          organization: Guangdong Biomedical Engineering Association
          organization_url: http://gdsbme.com/
          title: 'First Prize in 2022 Guangdong Undergraduate Biomedical Engineering Innovation Design Competition'
          url: ''

    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      # default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-

      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="my_album" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-

      # Contact (add or remove contact options as necessary)
      email: penghui-du@outlook.com / penghui.du@epfl.ch
      phone: +41 77 211 89 07 / +86 158 8937 2606
      address:
        street: 4 Rue Favre-Louis
        city: Ecublens
        region: Vaud
        postcode: '1024'
        country: Switzerland
        country_code: CH
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
