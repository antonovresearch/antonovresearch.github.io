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
    
  # ----------------- EDUCATION -----------------
  - block: markdown
    content:
      title: "Education"
      text: |
        <div class="text-left">
        - 🎓 **PhD in Organic Chemistry**  
          Southern Federal University  
          Oct 2011 – Sep 2014

        - 🎓 **MS in Organic Chemistry**  
          Southern Federal University  
          Sep 2009 – Jun 2011

        - 🎓 **BS in Physical Chemistry**  
          Southern Federal University  
          Sep 2005 – Jun 2009
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["1rem", "0", "1rem", "0"]

  # ----------------- ACADEMIC EXPERIENCE -----------------
  - block: markdown
    content:
      title: "Academic Experience"
      text: |
        <div class="text-left">
        - 💼 **Researcher**  
          Regensburg University  
          May 2023 – Present

        - 💼 **Invited Lecturer**  
          Ludwig-Maximilians-Universität München  
          Apr 2024 – Jul 2025

        - 💼 **Associate Professor**  
          Saint Petersburg University  
          Sep 2019 – Feb 2023

        - 💼 **Senior Researcher**  
          Saint Petersburg University  
          Apr 2018 – Aug 2019

        - 💼 **Senior Researcher**  
          Southern Federal University  
          Jan 2016 – Mar 2018

        - 💼 **Assistant Professor**  
          Southern Federal University  
          Sep 2012 – Dec 2015
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["1rem", "0", "1rem", "0"]
    
  - block: resume-experience
    content:
      username: antonov
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true 
    
- block: resume-experience
  content:
    title: "Academic Experience"
    username: ""      # empty username disables pulling default education
    items:
      - title: "Senior AI Research Scientist"
        company: "Meta AI"
        location: "San Francisco, CA"
        date_start: "2020-01-01"
        date_end: ""
        description: |
          * Led development of key features
          * Mentored junior developers
          * Improved system performance by 40%
      - title: "AI Research Intern"
        company: "OpenAI"
        location: "San Francisco, CA"
        date_start: "2019-06-01"
        date_end: "2019-12-31"
        description: "Worked on GPT-3 scaling. Co-authored paper on prompt engineering."
  design:
    columns: "1"

  # ----------------- INSTITUTIONAL RESPONSIBILITIES -----------------
  - block: markdown
    content:
      title: "Institutional Responsibilities"
      text: |
        <div class="text-left">
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
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["1rem", "0", "1rem", "0"]

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
