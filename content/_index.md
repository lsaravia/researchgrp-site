---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Ecology and complex systems
        CADIC Research Group
      image:
        filename: Antartida.jpg
      text: |
        <br>
        
        The Ecological Complex Systems Lab investigates how ecological systems are shaped by interactions across scales—spatial, temporal, and organizational—using complex systems theory, quantitative modeling, and network approaches. Our research spans ecosystems from the Amazon basin to the Southern Ocean, addressing pressing questions about biodiversity loss, food web stability, climate change, fragmentation, and disturbance regimes such as wildfires.

        We develop and apply tools grounded in network theory, spatial ecology, and stochastic modeling to explore how species interactions—both trophic and non-trophic—govern the resilience and functioning of ecosystems under anthropogenic stressors. Our lab integrates theory with empirical data, collaborating across disciplines to inform both fundamental ecology and environmental decision-making.

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
        publication_type: 'article'
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
