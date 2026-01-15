---
title:  Dicidi a te✨!
content_blocks:
  - _bookshop_name: hero
    heading:
      title: Welcome - Dicidi a te✨!
      content: |-
        A blog created to share my studies and personal projects with the world.
      width: 6
    background:
      color: primary
      subtle: true
    illustration:
      image: "/img/image.png"
      ratio: 16x9
    width: 8
    links:
      - title: About me
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
      title: More posts
    padding: 0
    limit: 3
    class: border-0 card-zoom card-body-margin

  - _bookshop_name: articles
    heading:
      title: Projects
      align: start
    background:
      background: body-tertiary
    hide-empty: false
    input:
      section: projects
      reverse: false
      sort: date
    more:
      title: More projects
    cols: 1
    padding: 4
    limit: 2
    icon-style: fa-5x
    header-style: none
    footer-style: tags
    orientation: horizontal-sm
    class: border-1 card-emphasize
---
