---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem" 
  css: |
    body {
      margin: 0;
      padding: 0;
    }
    .container {
      padding-left: 0rem;
      padding-right: 0rem;
    }

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Recognizing that the ultimate aim of all research is to apply it in real-world scenarios, enhancing the interaction between humans and machines is interesting and challenging. My areas of research interest are in computer vision, transfer learning, and high performance machine learning. I aspire to transform these algorithms into practical engineering solutions that aid in human construction. Specifically, my research focuses on: (1) Robust Reinforcement learning from human feedback, (2) mobile navigaion, and (3) Large Language/Vision Models

  - block: markdown
    content:
      title: '📰 News'
      text: |-
        **07/2024:** I start my PhD research under the supervision of Prof. George Atia at UCF.
    
        **05/2024:** I have submitted my master thesis and graduated from New York University.
    
        **01/2024:** I begin my position as the software team leader for the NYU VIP Self-Drive project.
    
        **09/2023:** I start my master thesis research under the supervision of Prof. Chen Feng in the AI4CE LAB.
    
  - block: markdown
    content:
      title: '🏆 Awards & Honors'
      text: |-
        - **UCF Graduate Artificial Intelligence Initiative Fellowship** *2024 - 2025*
        - **NYU Graduate School of Engineering Scholarship** *2022 - 2024*
        - **The Appreciate Presenter at the 2021 4th International Conference on Computing and BigData** *Nov. 2021*
        - **The Meritorious Winner of 2021 Interdisciplinary Contest in Modeling** *Feb. 2021*
        - **The Successful Participant Award of Asia and Pacific Mathematical Contest in Modeling** *Nov. 2020*
        - **The Second prize of the 10th National MathorCup university mathematical modeling challenge** *Jun. 2020*

        
    # design:
    #   columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     links_to_page: false
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 0
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1




  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
