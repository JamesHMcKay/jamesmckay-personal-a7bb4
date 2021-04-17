---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m James. I write code to help you make the most of your data.'
    subtitle: Example text
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
        subtitle: 'Website, blog, social media and more.'
        content: >
          I extract value from data by using the right statistical methods for
          the given problem.
        actions:
          - label: See Writing Samples
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-1.svg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
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
        image: images/feature-3.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
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
        image: images/Rlogo.svg
        image_position: left
        image_width: twenty-five
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
    content: >-
      ## Let's talk


      If you would like more information about my services and pricing, please
      contact me using the form below.
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
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
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
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
