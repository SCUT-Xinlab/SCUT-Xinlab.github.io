---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    design:
      css_class: "custom-hero"
      columns: "1"
    content:
      # title: "Zhang Xin"
      image:
        filename: "person.png"
      text: |
          <div class="text-content" style="font-size: 0.9em; line-height: 1.5;">
            <h2>Xin Zhang</h2>
            <p>Currently serving as <strong>Head of the Department of Artificial Intelligence, Assistant Dean of the School of Electronics and Information, South China University of Technology</strong>. Her research interests include
            <span>Machine Learning</span>, <span>Computer Vision</span>, <span>Intelligent Human-Computer Interaction</span>, and <span>Brain Imaging Data Processing</span>.</p>
            <p> From 2018 to 2020, she was sponsored as a visiting scholar at the
            <strong>Biomedical Research Imaging Center, University of North Carolina at Chapel Hill</strong>, where she worked on machine learning-based research in
            <span>Infant Brain Imaging</span> and <span>Neurodevelopmental Disorder Analysis</span>.</p>
          </div>



  
  - block: collection
    content:
      title: '📣 Latest News'
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: '📑 Latest Publications'
      text: ""
      count: 4
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'


  - block: markdown
    content:
      title: '🚀 Join Our Lab'
      subtitle: ''
      text: |-
        Our lab's research areas include but are not limited to: computer vision, machine learning, medical data analysis (imaging, pathology, genomics, clinical records, etc.), and multi-modal large models.

        We welcome new members to join us. Requirements:

        - Passion for research, clear goals, self-discipline, and motivation
        - Strong interest in artificial intelligence research
        - Relevant project experience and programming skills

        If interested, please send your CV via email: [Click here to send email](mailto:eexinzhang@scut.edu.cn) 😃
    design:
      columns: '1'
      # background:
      #   color: white

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Lab Members →" %}}
    design:
      columns: '1'
---
