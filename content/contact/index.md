---
title: 联系我们
date: 2022-10-24
type: landing

sections:
  - block: contact
    content:
      title: 联系我们
      text: |-
        欢迎与我们联系。如需了解科研合作、人才培养、招生或学术交流等信息，请通过以下方式与研究所取得联系。
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: 塞拉商城 450 号
        city: 斯坦福
        region: 加利福尼亚州
        postcode: '94305'
        country: 美国
        country_code: US
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: 进入 1 号楼后上楼，前往二层 200 室
      office_hours:
        - '周一 10:00–13:00'
        - '周三 09:00–10:00'
      appointment_url: 'https://calendly.com'
      autolink: true
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          captcha: false
    design:
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
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
