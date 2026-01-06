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
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Senior Software Engineer
          company: Tech Corp
          company_url: ''
          company_logo: ''
          location: San Francisco, CA
          date_start: '2023-01-01'
          date_end: ''
          description: |2-
            * Lead development of microservices architecture serving 1M+ users
            * Improved API response time by 40% through optimization
            * Mentored team of 5 junior developers
            * Tech stack: React, Node.js, PostgreSQL, AWS
        - title: Full-Stack Developer
          company: Startup Inc
          company_url: ''
          company_logo: ''
          location: Remote
          date_start: '2021-06-01'
          date_end: '2022-12-31'
          description: |2-
            * Built and deployed 3 production applications from scratch
            * Implemented CI/CD pipeline reducing deployment time by 60%
            * Collaborated with design team on UI/UX improvements
            * Tech stack: Next.js, Express, MongoDB, Docker
        - title: Junior Developer
          company: Web Agency
          company_url: ''
          company_logo: ''
          location: New York, NY
          date_start: '2020-01-01'
          date_end: '2021-05-31'
          description: |2-
            * Developed client websites using modern web technologies
            * Maintained and updated legacy codebases
            * Participated in code reviews and agile ceremonies
            * Tech stack: React, WordPress, PHP, MySQL
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

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
