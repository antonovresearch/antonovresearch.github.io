---
title: 'Dr. Alexander Antonov'
type: landing

design:
  spacing: '5rem'

sections:
  - block: resume-biography
    content:
      username: "antonov"
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg # Options: xs, sm, md, lg (default), xl
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle
 
  - block: resume-experience
    content:
      username: antonov
    design:
      date_format: 'January 2006'
      is_education_first: true

  - block: resume-experience
    content:
      title: "Institutional Responsibilities"
      items:
        - title: "Senior Developer"
          company: "Saint Petersburg University"
          date_start: "2020-09-01"
          date_end: "2023-02-01"

        - title: "Vice Chair of the Department of Physical Organic Chemistry"
          company: "Saint Petersburg University  "
          location: "New York, NY"
          date_start: "2021-09-01"
          date_end: "2023-02-01"
    design:
      columns: "1"
    
  - block: markdown
    content:
      title: "Institutional Responsibilities"
      text: |
        - 🏛 **Scientific supervisor of the Bachelor education program “Chemistry”**  
          Saint Petersburg University  
          Sep 2021 – Feb 2023

        - 🏛 **Vice Chair of the Department of Physical Organic Chemistry**  
          Saint Petersburg University  
          Sep 2021 – Feb 2023

        - 🏛 **Member of the Academic Senate of the Faculty of Chemistry**  
          Southern Federal University  
          Feb 2017 – Apr 2018

        - 🏛 **Chairman of the Young Researchers Council**  
          Southern Federal University  
          Jan 2017 – Apr 2018

        - 🏛 **Dean for Research of the Faculty of Chemistry**  
          Southern Federal University  
          Jun 2015 – Nov 2016
    design:
      columns: "1"
      spacing:
        padding: ["1rem", "0", "1rem", "0"]
      text_align: left

  - block: resume-languages
    content:
      title: Languages
      username: antonov
    design:
      spacing:
        padding: ["1rem", "0", "1rem", "0"]

  - block: cta-button-list
    content:
      title: ""
      buttons:
        - text: "Publications"
          url: "/publications"
          icon: "document-text"
        - text: "Funding"
          url: "/funding"
          icon: "currency-euro"
        - text: "Teaching"
          url: "/teaching"
          icon: "book-open"
    design:
      columns: "3"
      spacing:
        padding: ["1rem", "0", "1rem", "0"]
---
