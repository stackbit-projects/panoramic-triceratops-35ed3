---
title: ContactoFormulario
sections:
  - type: hero_section
    title: Estamos para apoyarte
    subtitle: Escríbenos tus dudas o sugerencias
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >-

      ### Privacidad

      Los datos proporcionados en el formulario almacenan la información enviada
      para que puedan ser contactados.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre y apellido
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu dirección de correo electrónico
        is_required: true
        options: []
      - input_type: select
        name: subject
        label: Asunto
        default_value: Selecciona un asunto
        options:
          - Presupuesto
          - Consulta
          - otros
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario almacena mi información enviada para que
          puedan ser contactados.
        is_required: true
    submit_label: Enviar
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
template: advanced
---
