---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: yajing.yan@univ-smb.fr
  phone: +33(0) 4 50 09 65 36
  address:
    street: 5 chemin de Bellevue, CS80439,
    city: Annecy
    region: 
    postcode: '74944'
    country: France
    country_code: FR
  coordinates:
    latitude: '45.919665'
    longitude: '6.158151'
  directions: Enter Building "Polytech Annecy-Chambéry" and take the stairs to Office 206 on Floor 2
  #office_hours:
    #- 'Monday 10:00 to 13:00'
    #- 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

design:
  columns: '1'
---
