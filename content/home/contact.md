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
  email: gvsmothish@gmail.com
  phone: +91-9959793510
  address:
    street: old Bustand
    city: Nellore
    region: Andhra Pradesh
    postcode: '524315'
    country: INDIA
    country_code: IND
 # coordinates:
   # latitude: '37.4275'
   # longitude: '-122.1697'
 # directions: look for address
  office_hours:
    - 'Monday 10:00 to 13:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
  #  - icon: video
  #    icon_pack: fas
  #    name: Zoom Me
  #    link: 'https://zoom.com'

design:
  columns: '2'
---
