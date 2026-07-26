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

  # This pulls your standard Experience/Education from data/authors/antonov.yaml
  - block: resume-experience
    content:
      username: antonov
    design:
      date_format: 'January 2006'
      is_education_first: true

  # NEW: Responsibilities in resume-experience style, but sourced from page front matter
  - block: resume-responsibilities
    id: responsibilities
    content:
      title: "Institutional Responsibilities"
      items:
        - title: "Programme Director, BSc programme “Chemistry”"
          company: "Saint Petersburg University"
          date_start: "2021-09-01"
          date_end: "2022-11-30"
          description: ""

        - title: "Vice Chair of the Department of Physical Organic Chemistry"
          company: "Saint Petersburg University"
          date_start: "2021-09-01"
          date_end: "2022-11-30"
          description: ""

        - title: "Member of the Academic Senate of the Faculty of Chemistry"
          company: "Southern Federal University"
          date_start: "2017-02-01"
          date_end: "2018-04-01"
          description: ""

        - title: "Chairman of the Young Researchers Council"
          company: "Southern Federal University"
          date_start: "2017-01-01"
          date_end: "2018-04-01"
          description: ""

        - title: "Dean for Research of the Faculty of Chemistry"
          company: "Southern Federal University"
          date_start: "2015-06-01"
          date_end: "2016-11-01"
          description: ""
    design:
      columns: "1"

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

  - block: "team-showcase"
    id: heroes
    content:
      title: "My Heroes"
      user_groups:
        - name: Heroes

    design:
      show_role: true               # show role if present; falls back to affiliation
      show_organizations: true      # keeps first affiliation visible
      show_interests: false         # typically skip on alumni grids; set true if concise
      max_interests: 0              # hide interests even if provided
      align: left                   # more editorial feel; use center if preferred
      max_columns: 4                # 3-wide tends to read best for bios/photos
      show_social: true             # keep if you capture LinkedIn/Google Scholar
      show_empty_groups: false      # hide the section if empty
      css_class: " "
      spacing:
        padding: ["5rem", 0, "5rem", 0]
---
