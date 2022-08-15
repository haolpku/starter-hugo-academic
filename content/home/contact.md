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
  email: lianghao618@hotmail.com
  phone: (+86)13241935113
  address:
    street: Majiapu Street
    city: Beijing
    region: CN
    postcode: '100068'
    country: China
    country_code: CN
  coordinates:
    latitude: '40'
    longitude: '116'
  directions: 
  office_hours:
    - 'Weekdays 8:00AM to 12:00PM'
    - 'Weekends 12:00AM to 12:00PM'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
