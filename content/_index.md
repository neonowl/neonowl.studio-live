---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: neonowl.studio
      text: 🧱 built with HugoBlox  🧱
      primary_action:
        text: Get Started
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
      announcement:
        text: "Announcing the release of version 1."
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: cta-image-paragraph
    id: signup
    content:
      items:
        - title: Neonowl Studio
          text: AKA Jerm's Apartment
          feature_icon: bolt
          features:
            - "Reading"
            - "Writing"
            - "Thinking"
          # Upload image to `assets/media/` and reference the filename here
          image: neonowlstudio.jpg
          button:
            text: Join Our Discord
            url: https://neonowl.social
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
