---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Discover Distribute and Store Valuable Mini Drama
      image:
        filename: cover.vcat.png
      cta:
        label: Download
        url: https://funon.xyz/download/
        icon_pack: fas
        icon: download
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzc
      text: |
        <br>
        <font>
        FunOn is a Web2-Compatible Decentralized Content Platform aiming to build the backbone infrastructure for the next generation of videos.
        </font>
        <br><br>
    design:
      # Choose an optional background color, gradient, image, or video
      css_class: fullscreen
      background:
        gradient_end: '#FFFFFF'
        gradient_start: '#FFFFFF'
        text_color_light: false
  - block: markdown
    content:
      text: |
        <div class="brand-container">
          <div class="image-content">
            <img src="cover.vcat.png">
          </div>
          <div class="text-content">
            <p>Your text goes here. It will be centered in the left side of the container.</p>
          </div>
        </div>
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: portfolio
    id: projects
    content:
      title: Drama Category
      filters:
        # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: Action
          tag: Action
        - name: Adventure
          tag: Adventure
        - name: Comedy
          tag: Comedy
        - name: Crime and Mystery
          tag: Crime and Mystery
        - name: Fantasy
          tag: Fantasy
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: features
    content:
      title: My Interests
      subtitle: Section subtitle
      text: Section text
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
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
---