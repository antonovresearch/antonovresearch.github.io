---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: hero
    id: about
    content:
      title: |
        Physical Organometallic Chemistry
      text: |
        We are a research group focused on the investigation of the role of non-covalent interactions in the structural features, synthetic methodology and reactivity of main group organometallics.<br><br>
        As of now we are a subgroup of the group of Prof. Ruth Gschwind at the University of Regensburg.
      primary_action:
        text: View Publications
        url: '#publications'
        icon: hero/academic-cap
      # announcement:
        # text: "We are hiring PhD students!"
        # link:
          # text: "Apply now"
          # url: "/opportunities"
    design:
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        image:
          filename: hero-bg.jpg
          size: cover
          position: center
          #filters:
        #     brightness: 0.6
        #     contrast: 1.1
        
        # Option B: Team/lab image (uncomment to use instead of gradient mesh)
        # image:
        #   filename: "team-lab-hero.jpg"
        #   filters:
        #     brightness: 0.6
        #     contrast: 1.1  

  - block: stats
    content:
      items:
        - statistic: "36"
          description: Publications in top-tier journals
           #sub_metric: Nature, Science, Cell, PNAS
          icon: hero/document-text
        - statistic: "6"
          description: Brilliant team members
           #sub_metric: From 8 countries worldwide
          icon: hero/user-group
        #- statistic: "$5M"
          #description: Active research funding
           #sub_metric: NSF, NIH, DOE grants
          #icon: hero/currency-dollar
        - statistic: "4"
          description: Active research projects
           #sub_metric: Across 3 major domains
          icon: hero/academic-cap
    design:
      layout: cards
      # Section background color (CSS class)
      css_class: " "
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: research-areas
    id: research-areas
    content:
      title: Research Focus Areas
      subtitle: Expanding the Frontiers of Organometallic Chemistry with Non-covalent Interactions
      items:
        - name: Organolithium Chemistry
          description: Steric effects in synthesis, structure and reactivity of organolithium compounds
          icon: custom/icon_Li
          gradient: from-green-400 to-emerald-600
            
        - name: Heterocyclic chemistry
          description: Non-covalent interactions in synthesis and functionalisation of heterocyclic compounds
          icon: custom/icon_N
          gradient: from-blue-400 to-indigo-600

        - name: Pnictogen and boron chemistry
          description: New methods for the synthesis of organopnictogens
          icon: custom/icon_P
          gradient: from-purple-400 to-pink-600

    design:
      layout: cards
      css_class: " "
      spacing:
        padding: ["5rem", 0, "5rem", 0]

  - block: research-areas
    id: team
    content:
      title: Meet Our Team
    design:
      spacing:
        padding: ["1rem", "0", "0", "0"]
        margin: [0, 0, 0, 0]
    
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: antonov
      text: ''
      # Show a call-to-action button under your biography? (optional)
      headings:
        about: ''
        education: ''
        interests: ''
      button:
        text: Detailed CV
        url: /antonov
        icon: 'arrow-left'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true
      spacing:
        padding: ["0", "0", "0", "0"]
        margin: [0, 0, 0, 0]
    
      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle 
      
  - block: team-showcase
    content:
      user_groups:
        - "Postdoctoral Researchers"
        - "PhD Students"
        - "Undergraduate Students"

      author_page_urls:
        antonov: "/antonov/"

      cta:
        text: "Alumni"
        url: "/alumni/"
        icon: "user-group"

    design:
      show_role: true
      show_organizations: true
      show_interests: true
      show_social: true
      spacing:
        padding: ["0", "0", "5rem", "0"]
    
  - block: collection
    id: publications
    content:
      title: "Recent Publications"
      filters:
        folders:
          - publications
      # don't need featured_only, we pick latest automatically
      count: 4                 # number of items to display
      sort_by: date            # sort by publication date
      sort_ascending: false    # newest first
    design:
      view: article-grid
      css_class: " "
      columns: 2
      spacing:
        padding: ["5rem", 0, "5rem", 0]
        
        
  - block: research-areas
    id: funding
    content:
      title: Research Funding
      items:
        - name: Organolithium reagents in the synthesis and functionalization of nitrogen heterocycles
          description: Russian Science Foundation, № 21-73-10040, 2021-2024
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: custom/rsf

        - name: "Sterically assisted activation of dialkylamino group in the synthesis of fused nitrogen heterocycles"
          description: Russian Foundation for Basic Research, № 20-33-70205, 2019-2021
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: custom/rfbr
    
        - name: The development of novel BINOL based organocatalysts
          description: Deutscher Akademischer Austauschdienst, 2020. Three month research stay in the group of Prof. Ruth Gschwind (Regensburg University)
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: custom/daad    


        - name: Superbasic non-nucleophilic polymeric materials based on proton sponges
          description: Russian Science Foundation, № 18-73-00020, 2018-2020
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: custom/rsf


        - name: Organometallic derivatives of 1,8-bis(dimethylamino)naphthalene
          description: Russian Foundation for Basic Research, № 16-33-60030, 2016-2018
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: custom/rfbr


        - name: "Novel principle for pyrrole ring construction: synthesis of benzo[g]indoles"
          description: Russian Foundation for Basic Research, № 12-03-31172, 2016-2018
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: custom/rfbr
      cta:
        text: See All Funding
        url: /funding
        icon: hero/arrow-right
    
    design:
      layout: cards
      show_logo: true        
      css_class: " "
      spacing:
        padding: ["5rem", 0, "5rem", 0]
       
  - block: collection
    id: news
    content:
      title: Lab News & Updates
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      css_class: " "
      columns: 1
    
  - block: research-areas
    id: teaching
    content:
      title: Recent Teaching Activities
      subtitle: Courses Offered by Our Lab
      items:
        - name: "Organic Chemistry: Seminar" 
          description: Bachelor (in German), Regensburg University, since 2025
          status: active
          icon: hero/book-open
          gradient: from-yellow-400 to-yellow-600
    
        - name: "Modern Organometallic Synthesis: Lecture" 
          description: Master (In English), Regensburg University, since 2025
          status: inactive
          icon: hero/book-open
          gradient: from-yellow-400 to-yellow-600

        - name: "New Synthetic Methods in Organic Chemistry: Lecture" 
          description: Master (In English), Ludwig-Maximilians-Universität München, 2024 - 2025
          status: inactive
          icon: hero/book-open
          gradient: from-yellow-400 to-yellow-600
      cta:
        text: See All Teaching Activities
        url: /teaching
        icon: hero/arrow-right    
    
    design:
      layout: cards
      show_logo: true        
      css_class: " "
      spacing:
        padding: ["5rem", 0, "5rem", 0]

  - block: "team-showcase"
    id: collaborations
    content:
      title: "Our Collaboration Partners"
      user_groups:
        - " "
    design:
      show_role: true
      show_organizations: true
      show_interests: false
      show_social: true
      css_class: " "
      spacing:
        padding: ["5rem", 0, "5rem", 0]

  - block: contact-info
    id: contact
    content:
      title: Contact Us
      subtitle: Get in touch with our research team
      visit_title: Visit Our Lab
      connect_title: Connect With Us
      address:
        lines:
          - Antonov Laboratory
          - AK Gschwind
          - Institute of Organic Chemistry
          - University of Regensburg
          - Universitätsstr. 31
          - 93053 Regensburg
          - Germany
       #office_hours:
         #- "Monday - Friday: 8:00 AM - 4:00 PM"
        #- "Lab Meetings: Fridays 2:00 PM"
      email: alexander.antonov@ur.de
      #phone: "+1 (555) 123-4567"
      social:
        - icon: brands/x
          url: https://x.com/Alex_S_Antonov
        - icon: brands/linkedin
          url: https://www.linkedin.com/in/alexander-antonov-98836a27b/
        - icon: brands/bluesky
          url: https://bsky.app/profile/alexanderantonov.bsky.social

      #map_url: https://maps.google.com/?q=University+of+Excellence
      show_form: false
    design:
      css_class: " "
      spacing:
        padding: ["5rem", 0, "5rem", 0]

  - block: cta-card
    content:
      title: Join Our Research Team
      text: We are always looking for talented and motivated researchers to join our lab.
      button:
        text: View Open Positions
        url: /opportunities
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300 dark:bg-primary-700"
        css_style: ''
---
