---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m James. I build software to get the most out of data.'
    subtitle: >-
      From automated data cleaning to simple presentation, my software solutions
      make insights that are robust and reliable.
    actions:
      - label: Contact Me
        url: /contact
        style: primary
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: features_section
    title: What I do
    features:
      - title: Analytics and modelling
        subtitle: Extracting value from data
        content: >
          I create insights by following a proven approach to data analysis. The
          first step is data cleaning; understanding what parts of the data hold
          value and bringing together data from a range of places. This is often
          the hardest part and requires care, and can involve many levels of
          automation. Once a robust, repeatable data cleaning process is in
          place I can produce valuable insights with confidence. Depending on
          the business problem this can involve using the appropriate
          statistical methodology to extract further information from the data,
          or find the right visualisations to make results easy to understand.
        actions:
          - label: See some of my work
            url: /work
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/analytics.svg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: fourty
      - title: Process automation
        subtitle: 'Efficient, automated business processes'
        content: >-
          Automation saves time and reduces errors. Almost every task is worth
          automating to some extent. Using the appropriate tools I automate
          process, from simple file management tasks through to large data
          pipelines.
        actions:
          - label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/process_automation.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: fourty
      - title: Software development
        subtitle: Products that do exactly what you need
        content: >-
          I develop products that solve data problems. From efficient back-end
          services to customer centric visualisations and dashboards. Software
          is at the core of what I do, with robust code behind every output from
          websites to research.
        actions:
          - label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/software_development.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: fourty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Current and past projects
    subtitle: Highlighted work
    grid_items:
      - content: >
          The RiverGuide is contains the only single source for all river flow
          and rainfall data in New Zealand, with over 1000 live gauges. It also
          features recreational guides with interactive features for editing
          content and logging activities.
        image: images/RiverWikiLogo.png
        image_position: left
        image_width: twenty-five
        actions:
          - label: Learn more about the RiverGuide
            url: /riverguide
            style: secondary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        image_align: center
        title: The New Zealand RiverGuide
      - content: >
          This Shiny R application was developed rapidly at the start of New
          Zealand's COVID-19 lock-down. With a robust data pipeline it has
          scaled to showing hundreds of different datasets in a simple user
          interface.
        image_position: left
        image_width: twenty-five
        image: images/Auckland-weekly-traffic-light.jpg.svg
        actions:
          - label: Learn more about the Data Portal
            url: '#'
            style: secondary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        title: COVID-19 Data Portal
      - title: Confronting dark matter theory with data
        title_align: left
        content: >
          While we known some kind of dark matter exists, the nature of it is
          not yet understood. In this work I confronted some possible dark
          matter theories with data, which involved large computational efforts.
        content_align: left
        actions:
          - label: Learn more about my dark matter work
            url: dark-matter-studies
            style: secondary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: left
        image_width: twenty-five
        image_align: left
        image_has_padding: false
        type: grid_item
        subtitle: From experiment to theory
        image: images/stars.png
      - title: The Hubble flow of the universe
        subtitle: 'The universe is expanding, but with respect to who?'
        title_align: left
        content: >
          This paper explores the concept of a universal frame of reference,
          what is background on which the universe is expanding. It also explore
          systematic statistical bias in observational data.
        content_align: left
        actions:
          - label: Learn more about our expanding universe
            url: '#'
            style: secondary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: left
        image_width: twenty-five
        image_align: left
        image_has_padding: false
        type: grid_item
        image: images/telescope.svg
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
  - title: Blog
    subtitle: Thoughts and ideas
    actions: []
    blog_feed_cols: two
    enable_cards: true
    show_recent: false
    recent_count: 0
    show_date: true
    show_categories: false
    show_author: false
    show_excerpt: false
    show_image: true
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: blog_feed_section
  - type: form_section
    content: >
      ## Let's talk


      If you would like more information about how I could help your business,
      please contact me using this form.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: James McKay
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: James McKay
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: James McKay
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
