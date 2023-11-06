---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      text: |
        <br><br><br><br>
        <font color=white size=45>**Discover Distribute and Store Valuable Mini Drama**</font>
      buttons:
        - title: down now
          icon: arxiv
          url: https://arxiv.org/abs/2304.01852
        - title: join us
          icon: youtube
          url: https://youtube.com
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
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        <br><br><br><br><br><br><br><br>
        <font color=white size=45><center>Decentralized Content Distribution Engine</center></font>
      buttons:
        - title: down now
          icon: arxiv
          url: https://arxiv.org/abs/2304.01852
        - title: join us
          icon: youtube
          url: https://youtube.com
    design:
      columns: '1'
      background:
        image: 
          filename: background.webp
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
      buttons:
        - title: Read my latest paper on LLMs
          icon: arxiv
          url: https://arxiv.org/abs/2304.01852
        - title: Watch my new YouTube video to achieve 20x productivity
          icon: youtube
          url: https://youtube.com
        - title: Connect with me on LinkedIn
          icon: linkedin
          url: https://linkedin.com
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Backers →" %}}
    design:
      columns: '1'

footer:
  block: minimal
  copyright:
    notice: '© {year} Me. Copyright@2021-2023 FUNON PTE. LTD. | Contact us at hello@funon.xyz'
    license:
      enable: true
      allow_derivatives: false
      share_alike: false
      allow_commercial: false
  # For multilingual sites, show a language chooser in the footer?
  show_translations: false
---