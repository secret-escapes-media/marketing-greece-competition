---
layout: competition
id: competition
permalink: /
nav: true
nav-order: 5
nav-title: Win

title: "Win a 5-night stay at a stunning 5* beachside hotel in Crete worth over £1,000"
enter-cta: Enter Now

features:
  - id: luxury-sea-view-room-private-pool
    title: Luxury sea view room & private pool
    description: You'll win a five-night stay at the 5* Porto Elounda Golf & Spa Resort in a stunning superior sea view room with your own private pool just a few steps from your terrace (handy if the ouzo has been flowing the night before). Soak up that Mediterranean sunshine in this ultra-glamorous setting. Your stay also includes breakfast served daily.
  - id: fine-dining
    title: Fine Dining
    description: Treat yourselves to a stylish and decadent meal at any one of the eight restaurants on-site, each serving up delicious dishes from traditional Greek delights, to Italian cuisine served al fresco. Afterwards, why not sit back and unwind with a drink at one of the four sophisticated lounges as you listen to the waves of the Aegean lap the shore.
  - id: six-senses-spa
    title: Six Senses Spa
    description: Also at your fingertips is the award-winning Six Senses Spa, with a comprehensive menu of therapies and wellness treatments to choose from; all designed for total mind and body relaxation.

competition-form:
  id: comp
  post-url: "#getFormUrl"
  expiry-date: 2050-01-01
  fields:
    - id: name
      type: text
      label: Name
      required: true
    - id: email
      type: email
      label: Email
      required: true
    - id: qualify
      type: radio
      label: Are you a UK resident and over the age of 18?
      required: true
      options:
        - id: qualify-true
          label: 'Yes'
          value: 'yes'
        - id: qualify-false
          label: 'No'
          value: 'no'
          invalid: true
    - id: opt-in
      type: radio
      label: Would you like to receive emails from Secret Escapes?
      required: true
      options:
        - id: opt-in-true
          label: 'Yes'
          value: 'yes'
        - id: opt-in-false
          label: 'No'
          value: 'no'
  submit: Submit Entry
  terms: >
    By submitting your entry, you agree to the <a href="#" class="js-open-modal link--underlined" data-open-modal="competition-terms">terms and conditions</a> of this competition and have read our <a class="link--underlined" href="https://www.secretescapes.com/privacy-policy" target="_blank">privacy policy</a>.
---