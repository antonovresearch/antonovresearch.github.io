---
title: 'Dr. Alexander Antonov'
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-biography
    content:
      username: "antonov"
    design:
      background:
        gradient_mesh:
          enable: true
      # spacing:
      #   padding: ["6", "6", "6", "6"]
      # columns: "1"

      # Name heading sizing to accommodate long or short names
      name:
        size: lg # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: square
 
  - block: resume-experience
    content:
      username: antonov
      title: "Academic Experience"
      items:
        - title: "Test"
          company: "Test"
          location: "Test"
          date_start: "2020-01-01"
          date_end: ""    
    design:
      date_format: 'January 2006'
      is_education_first: true 

  # ----------------- INSTITUTIONAL RESPONSIBILITIES -----------------
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

  # ----------------- LANGUAGES -----------------
  - block: resume-languages
    content:
      title: Languages
      username: antonov
    design:
      spacing:
        padding: ["1rem", "0", "1rem", "0"]

  # ----------------- TEACHING & FUNDING BUTTONS -----------------
  - block: cta-button-list
    content:
      title: ""
      buttons:
        - text: "Publications"
          url: "/publication"
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
