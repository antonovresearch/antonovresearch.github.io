---
title: Alumni
type: landing

sections:
  - block: team-showcase
    id: alumni
    content:
      title: Alumni
      subtitle: Where our graduates go next
      user_groups:
        - name: Alumni
          sort_by: graduation_year
          sort_ascending: false
      sort_by: graduation_year      # global fallback
      sort_ascending: false
    design:
      show_role: true               # show role if present; falls back to affiliation
      show_organizations: true      # keeps first affiliation visible
      show_interests: false         # typically skip on alumni grids; set true if concise
      max_interests: 0              # hide interests even if provided
      align: left                   # more editorial feel; use center if preferred
      max_columns: 3                # 3-wide tends to read best for bios/photos
      show_social: true             # keep if you capture LinkedIn/Google Scholar
      show_empty_groups: false      # hide the section if empty
---
