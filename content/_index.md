---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: daikitsutsumi
      text: ""
      # Show a call-to-action button under your biography? (optional)
    design:
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: chatgpt.webp
          filters:
              brightness: 0.4
  - block: resume-experience
    content:
      # The user's folder name in `content/authors/`
      username: daikitsutsumi
      title
    design:
      columns: '1'
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
---
