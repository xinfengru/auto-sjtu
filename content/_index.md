---
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        上海交通大学
        自动化研究所
      image:
        filename: welcome.jpg
      text: |
        <br>

        欢迎访问**上海交通大学自动化研究所**。我们致力于自动化、控制科学与人工智能领域的科学研究、人才培养与技术创新。

  - block: collection
    content:
      title: 最新动态
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
          filename: coders.jpg
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
      title: 最新预印本
      text: ''
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
        {{% cta cta_link="./people/" cta_text="认识我们的团队 →" %}}
    design:
      columns: '1'
---
