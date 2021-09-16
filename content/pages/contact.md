---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      Why hello! Thank you for popping on over. Please
      fill in the contact form below or send me an email at
      [luketodd@zoho.com](mailto:luketodd@zoho.com).
    form_id: contactForm
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
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Luke Todd - Contact
  description: Contact page to get in touch with Luke Todd
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Luke Todd - Contact
      keyName: property
    - name: 'og:description'
      value: Contact page to get in touch with Luke Todd
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Luke Todd - Contact
    - name: 'twitter:description'
      value: Contact page to get in touch with Luke Todd
layout: advanced
---
