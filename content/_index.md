---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <br>**Discover Distribute and Store Valuable Video**
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
        <br/>
        <font color=gray size=3>FunOn is a Web2-Compatible Decentralized Content Platform aiming to build the backbone infrastructure for the next generation of videos.</font>
        <br/><br/>
    design:
      css_class: fullscreen
      css_style: ''
      background:
        gradient_end: '#FFFFFF'
        gradient_start: '#FFFFFF'
        text_color_light: false
  - block: markdown
    content:
      text: |
        <div class="row">
          <div class="col-12 mx-auto col-md-6 board-media" >
            <center>
            {{< figure src="cover.vgirl.png" caption="" numbered="false" style="border-radius: 15px 50px 30px 5px;">}}
            </center>
          </div>
          <div class="col-12 col-md-6 text-center text-md-left">
            <br/><br/>
              <h2>Fonon App is a Web3 content aggregator aiming to gather and integrate Web’3 excellent videos to combine with users’ social portraits.</h2>
            <br/><br/>
            <font color=gray size=3>
            push the content that users are interested in , and at the same time, grant NFT copyright to Web3’s article authors,and then commercially promote and profit after gaining user volume.
            </font>
          </div>
        </div>
    design:
      columns: '1'
      css_class: fullscreen
      spacing:
        padding: ['80px', '0', '80px', '0']
      background:
        # image: 
        #   filename: coders.jpg
        #   filters:
        #     brightness: 1
        #   parallax: false
        #   position: center
        #   size: cover
        text_color_light: false  # Text color (true=light, false=dark, or remove for the dynamic theme color).
        color: '#FFFFFF'  # Choose a color such as from https://html-color-codes.info
  - block: hero
    content:
      title: |
        <br><h1>Capture wonders in life</h1>
      image:
        filename: cover.vboy.png
      text: | 
        <br/>
        <font color=gray size=3>Record moments in life with fun props and easy editing.</font>
        <br/><br/>
    design:
      css_class: fullscreen
      css_style: ''
      background:
        color: '#FFFFFF'
        text_color_light: false
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Backers →" %}}
    design:
      columns: '1'
---