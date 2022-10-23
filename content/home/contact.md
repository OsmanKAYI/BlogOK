---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: osmankayi06@gmail.com
  phone: +90 5** *** ** **
  address:
    street: Etlik
    city: Ankara
    postcode: '06210'
    country: Türkiye
    country_code: TR
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Send me a message
      link: 'https://www.linkedin.com/in/osman-kayi-0761aa173/'

design:
  columns: '2'
---
