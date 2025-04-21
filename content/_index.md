---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:  |
        Ecology and complex systems
        
      subtitle: 'Centro Austral de Investigaciones Científicas (CADIC)'
      text: |
        <br>
        
        The Ecological Complex Systems Lab investigates how ecological systems are shaped by interactions across scales—spatial, temporal, and organizational—using complex systems theory, quantitative modeling, and network approaches. 
    design:
      columns: '1'
      background:
        image: 
          filename: antartida-cassie-matias.png
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover

      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen


  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: jaguarFireForest.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Publications & Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: ''
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
