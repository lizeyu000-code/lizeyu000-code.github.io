---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        邮件联系优先，办公室电话可能打不通。
      email: lizeyu@sdust.edu.cn
      phone: 0532-80681170
      address:
        street: 
        city: 青岛
        region: 山东
        postcode: '266590'
        country: China
        country_code: PRC
      coordinates:
        latitude: '36.00042'
        longitude: '-120.12200'
      directions: 
      office_hours:
        - 'Workday 10:00 to 16:00 (Normally)'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
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
