---
title: 'Landing Page'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: neonowl.studio
      text: a digital pedagogy studio in a cyber-physical world
      primary_action:
        text: What is digital pedagogy?
        url: /#faqs
        icon: rocket-launch
      secondary_action:
        text: View the FAQs
        url: /#faqs
      announcement:
        text: "Another"
        link:
          text: "neonowl.website"
          url: "https://neonowl.website"
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
    id: about
    content:
      items:
        - title: Neonowl Studio
          text: AKA Jerm's Apartment, a place for
          feature_icon: bolt
          features:
            - "Reading"
            - "Writing"
            - "Thinking"
          # Upload image to `assets/media/` and reference the filename here
          image: neonowlstudio.jpg
          button:
            text: Join neonowl on Discord
            url: https://neonowl.social
  - block: markdown
    id: faqs
    content:
      title: FAQs
      subtitle: What is digital pedagogy?
      text: Digital pedagogy is the use of technology and digital tools to enhance teaching and learning experiences, making education more interactive, engaging, and accessible for students.
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
