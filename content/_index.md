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
      carousel:
        slides:
          - image: Buno-Wedding-9.jpg
            title: The Chateau
            text: Our beautiful venue
          - image: Buno-Wedding-17.jpg
            title: The Gardens
            text: Stunning outdoor spaces
          - image: Buno-Wedding-18.jpg
            title: The River
            text: The tranquil Essonne river
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "navy"
        image:
          filename: Buno-Wedding-9.jpg
          filters:
            brightness: 0.7
  - block: cta-image-paragraph
    id: contact
    content:
      items:
        - title: The Chateau
          text: A Chateau steeped in history and mystery, with private rooms, a separate apartment, and 8 acres of forest and gardens by the tranquilly flowing Essonne.
          feature_icon: home
          features:
            - "Three story chateau on an island within the river"
            - "Surrounded by tall trees and flowers"
            - "Birds sharing the property year-round"
          # Upload image to `assets/media/` and reference the filename here
          image: Buno-Wedding-17.jpg
          map:
            enable: true
            latitude: 48.4722  # Replace with actual latitude
            longitude: 2.3508  # Replace with actual longitude
            zoom: 15
            height: 300px
          button:
            text: Get Directions
            url: https://www.google.com/maps/place/Chateau+de+Buno/@48.4722,2.3508,15z  # Replace with actual Google Maps URL
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900" 