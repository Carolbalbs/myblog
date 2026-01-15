---
title: Dicidi a te✨!
content_blocks:
  - _bookshop_name: hero
    heading:
      title: Bem vindos - Dicidi a te✨!
      content: |-
        Um blog criado para compartilhar meus estudos e projetos pessoais com o mundo. 
      width: 6
    background:
      color: primary
      subtle: true
    illustration:
      image: "/img/image.png"
      ratio: 16x9
    width: 8
    links:
      - title: Sobre mim
        url: about.md
        icon: fas chevron-right
    orientation: horizontal
    justify: center

  - _bookshop_name: articles
    heading:
      title: Posts
      align: start
    input:
      section: blog
      reverse: true
      sort: title
    hide-empty: false
    header-style: none
    more:
      title: Mais posts
    padding: 0
    limit: 3
    class: border-0 card-zoom card-body-margin
    
  - _bookshop_name: articles
    heading:
      title: Projetos
      align: start
    background:
      background: body-tertiary
    hide-empty: false
    input:
      section: projects
      reverse: false
      sort: date
    more:
      title: Mais projetos
    cols: 1
    padding: 4
    limit: 2
    icon-style: fa-5x
    header-style: none
    footer-style: tags
    orientation: horizontal-sm
    class: border-1 card-emphasize
---

