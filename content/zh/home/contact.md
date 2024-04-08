---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: '## 联系方式'
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # # Email form provider
  # form:
  #   provider: netlify
  #   formspree:
  #     id:
  #   netlify:
  #     # Enable CAPTCHA challenge to reduce spam?
  #     captcha: false

  # Contact details (edit or remove options as required)
  email: +++@szu.edu.cn, 请将+++三个字符替换成我的姓氏拼音全拼
  # phone: 888 888 88 88
  address:
    street: 深圳大学, 沧海校区, 致腾楼, 1034办公室
    city:
    # region: Shenzhen
    # postcode: '94305'
    country: China
    country_code: CN
  coordinates:
    # latitude: '37.4275'
    # longitude: '-122.1697'
  directions: 
  office_hours:
    # - 'Monday 10:00 to 13:00'
    # - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    # - icon: twitter
    #   icon_pack: fab
    #   name: DM Me
    #   link: 'https://twitter.com/Twitter'
    # - icon: video
    #   icon_pack: fas
    #   name: Zoom Me
    #   link: 'https://zoom.com'

design:
  columns: '1'
  spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
    padding: ["20px", "0", "20px", "0"]
---
