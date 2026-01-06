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
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: tue
    
  - block: resume-awards
    content:
      title: Institutional Responsibilities
      username: antonov
  
  - block: resume-languages
    content:
      title: Languages
      username: antonov

  - block: cta-button-list
    content:
      title: ""
      buttons:
        - text: "Publications"
          url: "/publication"
          icon: "document-text"
        - text: "Funding"
          url: "/#Funding"
          icon: "currency-euro"
        - text: "Teaching"
          url: "/teaching"
          icon: "book-open"
    design:
      columns: "3"
---
