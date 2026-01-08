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
      title: "Experience"
      items:
        - title: "Senior Developer"
          company: "Tech Company"
          location: "San Francisco, CA"
          date_start: "2020-01-01"
          date_end: ""
          description: |
            * Led development of key features
            * Mentored junior developers
            * Improved system performance by 40%
        - title: "Software Engineer"
          company: "Startup Inc"
          location: "New York, NY"
          date_start: "2018-06-01"
          date_end: "2019-12-31"
          description: "Developed web applications using modern technologies"
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
          url: "/#funding"
          icon: "currency-euro"
        - text: "Teaching"
          url: "/#teaching"
          icon: "book-open"
    design:
      columns: "3"
      spacing:
        padding: ["1rem", "0", "1rem", "0"]
---
