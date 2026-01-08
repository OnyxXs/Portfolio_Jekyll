---
layout: contact
title:  "Contacts"
permalink: "/Contacts/"
forms:
  - to: timeo.donnaes@gmail.com
    subject: New submission!
    redirect: /
    form_engine: formspree
    fields: 
      - name: name
        input_type: text
        placeholder: Name
        required: true
      - name: email
        input_type: email
        placeholder: Email address
        required: true
      - name: message
        input_type: textarea
        placeholder: Message
        required: true
      - name: submit
        input_type: submit
        placeholder: Submit form
        required: true
---
