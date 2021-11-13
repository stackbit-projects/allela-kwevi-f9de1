---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contact
    content: "Pr. Clotilde-Chantal ALLELA-KWEVIALLELA\n\nMaître de Conférences, Art et Littérature hispano-américains <br>Université Omar Bongo <br> Faculté de Lettres et Sciences Humaines <br> Département\_ d’Etudes Ibériques et Latino-américaines <br> BP: 17004 | Tél: (+241) 01-73-76-42 <br> Libreville (GABON) <br>\n<yachadee1208@gmail.com> <br> <clotilde.allela@yahoo.com>\n\n"
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
      - input_type: email
        name: email
        label: Email
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
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
