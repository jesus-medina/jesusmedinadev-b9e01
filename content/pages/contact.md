---
title: Mupper
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      ¡El crédito Mupper estará disponible muy pronto! ¿Quieres aprovechar tu oportunidad? Envíanos un mensaje en el siguiente formulario.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: ¿Cómo te llamas?
        is_required: true
      - input_type: email
        name: email
        label: Correo electrónico
        default_value: Y ¿tu correo electrónico?
        is_required: true
      #- input_type: select
      #  name: subject
      #  label: Subject
      #  default_value: Please select
      #  options:
      #    - Error on the site
      #    - Sponsorship
      #    - Other
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Me encantaría convertirme en un profesional de la industria de la tecnología.
      - input_type: checkbox
        name: consent
        label: >-
          Me gustaría ser contactado cuando el crédito esté disponible.
    submit_label: Enviar mensaje
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
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
