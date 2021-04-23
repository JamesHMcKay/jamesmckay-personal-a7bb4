---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m James. I build software to make the most out of data.'
    subtitle: >-
      From data cleaning to simple and clean presentation, software helps us
      make processes robust and repeatable.
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
    subtitle: Latest work
    grid_items:
      - content: |
          The New Zealand RiverGuide
        image: images/RiverWikiLogo.png
        image_position: left
        image_width: twenty-five
      - content: |
          COVID-19 data response

          *Shiny R dashboard*
        image_position: left
        image_width: thirty-three
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
  - type: form_section
    content: >
      ## Let's talk


      If you would like more information about my services and pricing, please
      contact me using this form.
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
