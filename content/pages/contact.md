---
title: Contacto
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >-
      ¡Hola! Muchas gracias por tu intéres en trabajar juntos. Por favor,
      llena el formato de contacto o escríbeme a
      [midori.yamamoto26@ciencias.unam.mx](mailto:example@example.com).
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu email
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Please select
        options:
          - Error en el sitio
          - Cotización
          - Otro
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que esta forma almacena mi información para 
          poder ser contactado.
    submit_label: Enviar Mensaje
seo:
  title: Contacto
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
