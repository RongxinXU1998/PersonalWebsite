---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null 
    username: admin
  id: about
  design:
    columns: "2"
  view: card
# - block: features
#   content:
#     items:
#     - description: 90%
#       icon: r-project
#       icon_pack: fab
#       name: R
#     - description: 100%
#       icon: chart-line
#       icon_pack: fas
#       name: Statistics
#     - description: 10%
#       icon: camera-retro
#       icon_pack: fas
#       name: Photography
#     title: Skills
# - block: experience
#   content:
#     date_format: Jan 2006
#     items:
#     - company: GenCoin
#       company_logo: org-gc
#       company_url: ""
#       date_end: ""
#       date_start: "2021-01-01"
#       description: |2-
#           Responsibilities include:
# 
#           * Analysing
#           * Modelling
#           * Deploying
#       location: California
#       title: CEO
#     - company: University X
#       company_logo: org-x
#       company_url: ""
#       date_end: "2020-12-31"
#       date_start: "2016-01-01"
#       description: Taught electronic engineering and researched semiconductor physics.
#       location: California
#       title: Professor of Semiconductor Physics
#     title: Experience
#   design:
#     columns: "2"
# - block: accomplishments
#   content:
#     date_format: Jan 2006
#     items:
#     - certificate_url: https://www.coursera.org
#       date_end: ""
#       date_start: "2021-01-25"
#       description: ""
#       organization: Coursera
#       organization_url: https://www.coursera.org
#       title: Neural Networks and Deep Learning
#       url: ""
#     - certificate_url: https://www.edx.org
#       date_end: ""
#       date_start: "2021-01-01"
#       description: Formulated informed blockchain models, hypotheses, and use cases.
#       organization: edX
#       organization_url: https://www.edx.org
#       title: Blockchain Fundamentals
#       url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#     - certificate_url: https://www.datacamp.com
#       date_end: "2020-12-21"
#       date_start: "2020-07-01"
#       description: ""
#       organization: DataCamp
#       organization_url: https://www.datacamp.com
#       title: Object-Oriented Programming in R
#       url: ""
#     subtitle: null
#     title: Accomplish&shy;ments
#   design:
#     columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: 
      I am a PhD student in the [Department of Economics](https://econ.fss.um.edu.mo/), [University of Macau](https://www.um.edu.mo/about-um/), supervised by Professor [Angus C. CHU](https://sites.google.com/site/angusccc/home?authuser=0). In July 2022, I earned my master's degree in economics from the University of Macau. My research findings have been published in journals, such as [*Journal of International Economics*](https://www.sciencedirect.com/journal/journal-of-international-economics) and [*Macroeconomic Dynamics*](https://www.cambridge.org/core/journals/macroeconomic-dynamics).\
      
      My current research areas include economic growth, innovation and intellectual property rights. Recently, I am working on topics related to endogenous takeoff from stagnation to economic growth, which combine theory and empirical evidence.
    title: About Me
  design:
    columns: "2"
    view: compact
  id: posts
  
# - block: portfolio
#   content:
#     buttons:
#     - name: All
#       tag: '*'
#     - name: Deep Learning
#       tag: Deep Learning
#     - name: Other
#       tag: Demo
#     default_button_index: 0
#     filters:
#       folders:
#       - project
#     title: Projects
#   design:
#     columns: "1"
#     flip_alt_rows: false
#     view: showcase
#   id: projects
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
# - block: collection
#   content:
#     filters:
#       featured_only: true
#       folders:
#       - publication
#     title: Featured Publications
#   design:
#     columns: "2"
#     view: card
#   id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      [**Export-Led Takeoff in a Schumpeterian Economy**](https://doi.org/10.1016/j.jinteco.2023.103798). *Journal of International Economic*, vol. 145, 103798. (with [Angus Chu](https://sites.google.com/site/angusccc/home?authuser=0) and [Pietro Peretto](http://public.econ.duke.edu/~peretto/))\
      \
      [**From Neolithic Revolution to Industrialization**](http://dx.doi.org/10.1017/S1365100523000214). *Macroeconomic Dynamic*, forthcoming. (with [Angus Chu](https://sites.google.com/site/angusccc/home?authuser=0))
    title: Selected Publications
  design:
    columns: "2"
    view: citation
  id: publication
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
- block: contact
  content:
    address:
      city: Macao SAR
      country: China
      country_code: CHN
      street: University of Macau
      # postcode: "94305"
      region: China
    # appointment_url: https://calendly.com
    autolink: true
    email: rongxin.xu@connect.um.edu.mo
    phone: (+86)18163416889 / (+853)63416889
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/Rongxin_Xu
      name: https://twitter.com/Rongxin_Xu
    # - icon: skype
    #   icon_pack: fab
    #   link: skype:echo123?call
    #   name: Skype Me
    # - icon: video
    #   icon_pack: fas
    #   link: https://zoom.com
    #   name: Zoom Me
    # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    # form:
    #   formspree:
    #     id: null
    #   netlify:
    #     captcha: false
    #   provider: netlify
    # office_hours:
    # - Monday 10:00 to 13:00
    # - Wednesday 09:00 to 10:00
    # phone: 888 888 88 88
    # subtitle: null
  #   text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
  #     ut magna et, vehicula efficitur enim.
    title: Contact
  design:
    columns: "2"
  id: contact
type: landing
# type: "widget_page"  
---
