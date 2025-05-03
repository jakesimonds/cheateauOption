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
      title: Jake and Megan's Wedding
      text: A beautiful day at the chateau
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
          filename: Buno-Wedding-9.jpg
          filters:
            brightness: 0.7
  - block: features
    id: events
    content:
      title: Wedding Events
      text: Join us for our special day
      items:
        - name: Ceremony
          icon: heart
          description: The main event where we'll exchange our vows and become husband and wife.
        - name: Reception
          icon: glass-cheers
          description: Celebrate with us at our reception following the ceremony.
        - name: Dinner
          icon: utensils
          description: Enjoy a delicious meal with family and friends.
        - name: Dancing
          icon: music
          description: Let's dance the night away together!
        - name: Photos
          icon: camera
          description: Capture beautiful memories throughout the day.
        - name: Details
          icon: info-circle
          description: Find all the important information about the day's events.
  - block: cta-image-paragraph
    id: contact
    content:
      items:
        - title: The Chateau
          text: |
            A Chateau steeped in history and mystery, with private rooms, a separate apartment, and 8 acres of forest and gardens by the tranquilly flowing Essonne.


          feature_icon: home
          features:
            - "Three story chateau on an island within the river"
            - "Surrounded by tall trees and flowers"
            - "Birds sharing the property year-round"
          # Upload image to `assets/media/` and reference the filename here
          image: Buno-Wedding-17.jpg
          map:
            enable: true
            latitude: 48.3612222
            longitude: 2.3830556
            zoom: 15
            height: 300px
          button:
            text: Get Directions
            url: https://www.google.com/maps/place/48%C2%B021'40.4%22N+2%C2%B022'59.0%22E/@48.3615215,2.3821031,18z/data=!4m4!3m3!8m2!3d48.3612222!4d2.3830556?entry=ttu&g_ep=EgoyMDI1MDQyOS4wIKXMDSoJLDEwMjExNDU1SAFQAw%3D%3D
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---