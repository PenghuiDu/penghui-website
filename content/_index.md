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
      
        - title: Undergraduate
          company: Southern University of Science and Technology
          company_url: 'https://www.sustech.edu.cn'
          company_logo: sustech
          location: Shenzhen, China
          date_start: '2020-08-27'
          date_end: '2024-06-27'
          description: |2-
              * Major: Intelligent Medical Engineering
              * Academic Supervisor: Professor Quanying Liu
              * GPA: 3.84 / 4 (92.79), Ranking 2 / 22
              * 2021 - 2022 Department of Biomedical Engineering "Fortunatt" Scholarship
              * 2021 - 2022 SUSTech Outstanding Student Scholarships - First Prize
        - title: Visiting Student
          company: University of Zurich
          company_url: 'https://uzh.ch/cmsssl/en.html'
          company_logo: UZH
          location: Zurich, Switzerland
          date_start: '2023-02-01'
          date_end: '2023-06-15'
          description: |2-
              * Main Subject: Neuroinformatics
              * GPA: 5.3 / 6
        
        - title: Undergraduate Research Assistant
          company: Athinoula A. Martinos Center for Biomedical Imaging, Harvard Medical School
          company_url: 'https://www.martinos.org/'
          company_logo: Martinos
          location: Charlestown, Unites States
          date_start: '2023-07-05'
          date_end: '2024-02-29'
          description: |2-
              * Research Topic (Ongoing): Mapping morphology of resting state metabolic (FDG-PET) and functional activations (R-fMRI)
              * Supervisor: Professor Jingyuan Chen
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
          date_end: '2022-07-01'
          date_start: '2021-12-01'
          description: 'In the competition, We designed a business plan for manufactoring brain health monitor devices for severely ill newborns. After seven months of hard work, we finally completed our work and won the first prize in the competition. As the team leader, I am responsible for thinking of technical ideas and designing business plan.'
          organization: Department of Education of Guangdong Province
          organization_url: http://edu.gd.gov.cn/
          title: 'First prize in 13th "Challenge Cup" Entrepreneurship Plan Competition.'
          url: ''
        

        - certificate_url: https://penghui-du.com/uploads/neuromatch.pdf
          date_end: ''
          date_start: '2022-07-30'
          description: 'In this summer school, I learned basic principles of computational neuroscience such as reinforcement learning, leaky Integrate-and-Fire models, Hodgkin-Huxley models and Bayesian inference with other students in our team. After that, we did an amazing project on RNN and working memory and gave a presentation on our result.'
          organization: Neuromatch Academy
          organization_url: https://neuromatch.io/
          title: 2022 Neuromatch Computational Neuroscience Summer School
          url: ''

        - certificate_url: https://penghui-du.com/uploads/CLS-CIBR-IDG.jpg
          date_end: ''
          date_start: '2022-07-10'
          description: 'In this summer school, researchers from molecular / cellular / systems / cognitive backgrounds gave us various exciting lectures on neuroscience. After that, we had discussion on some excellent works on cognitive neuroscience and gave a presentation on one of the them.'
          organization: Tsinghua University and Peking University
          organization_url: http://mcgovern.life.tsinghua.edu.cn
          title: Merit Student of CLS-CIBR-IDG Summer School in Neuroscience
          url: ''

        - certificate_url: https://penghui-du.com/uploads/bme.jpg
          date_end: '2022-07-01'
          date_start: '2022-03-20'
          description: 'In the competition, we trained a deep learning model to segment critical organs in CT images. We developed a novel pretraining approach and achieved an accuracy of 85% in the segmentation task. As a result of our efforts, our team won first prize in the competition, beating out 188 other teams. As the team leader, I was responsible for building the model and writing the report.'
          organization: Guangdong Biomedical Engineering Association
          organization_url: http://gdsbme.com/
          title: 'First Prize in 2022 Guangdong Undergraduate Biomedical Engineering Innovation Design Competition'
          url: ''

        - certificate_url: https://penghui-du.com/uploads/challenge_cup.pdf
          date_end: '2022-07-01'
          date_start: '2021-12-01'
          description: 'In the competition, We designed a business plan for manufactoring brain health monitor devices for severely ill newborns. After seven months of hard work, we finally completed our work and won the first prize in the competition. As the team leader, I am responsible for thinking of technical ideas and designing business plan.'
          organization: Department of Education of Guangdong Province
          organization_url: http://edu.gd.gov.cn/
          title: 'First prize in 13th "Challenge Cup" Entrepreneurship Plan Competition.'
          url: ''
        
        - certificate_url: https://penghui-du.com/uploads/cuda.png
          date_end: '2020-11-20'
          date_start: '2020-11-21'
          description: ''
          organization: Nvidia
          organization_url: https://www.nvidia.com/en-us/
          title: 'Certificate of Competency - Basics of CUDA-accelerated computing'
          url: ''
        

    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
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
  - block: tag_cloud
    id: topics
    content:
      title: Popular Topics
    design:
      columns: '2'
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
      email: duph2020@mail.sustech.edu.cn / undefined0326@gmail.com
      phone: +86 158 8937 2606 / +1 (617) 256-3945
      address:
        street: No.1088, Xueyuan Blvd
        city: Shenzhen
        region: Guangdong
        postcode: '518055'
        country: China
        country_code: CN
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
