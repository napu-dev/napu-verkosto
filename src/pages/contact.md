---
title: Kontakt
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      Hei! Wollt ihr uns kontaktieren oder unserem Verteiler beitreten? Dann
      füllt dieses Kontaktformular aus :)


      Ihr könnt uns auf Deutsch, Finnisch oder Englisch  anschreiben.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Dein Name
        label: Name
        default_value: Dein Name
        is_required: true
      - input_type: email
        name: email
        label: E-Mail
        default_value: Deine E-Mail-Adresse
        is_required: true
      - input_type: select
        name: Betreff
        label: Betreff
        options:
          - Verteilerbeitritt
          - Anderes Anliegen
      - input_type: textarea
        name: message
        label: Nachricht
        default_value: Deine Nachricht
      - input_type: checkbox
        name: consent
        label: >-
          Ich bin damit einverstanden, dass die Daten in diesem Formular zur
          Kontaktaufnahme gespeichert werden
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
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
template: advanced
---
