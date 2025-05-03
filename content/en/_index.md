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
      title: Chateau Buno
      text: Event venue 50 km from Paris.
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
          filename: Buno-Wedding-17.jpg
          filters:
            brightness: 0.7
  - block: cta-image-paragraph
    id: events
    content:
      items:
        - title: Events
          text: |
            The three story chateau sits on an island within the river, surrounded by tall trees and flowers, with birds sharing the property with us all year round. A quiet paradise only a train away from Paris, and is exceptionally affordable as it is currently being renovated.


            


          feature_icon: home
          features:
            - "81,185m² of land"
            - "On-site parking"
            - "Private grounds not visible to neighbors"
            - "River with boat access"
            - "Accessible by public transportation (RER D)"
          # Upload image to `assets/media/` and reference the filename here
          image: Buno-Wedding-9.jpg
          map:
            enable: true
            latitude: 48.3612222
            longitude: 2.3830556
            zoom: 15
            height: 300px
  - block: cta-image-paragraph
    id: booking
    content:
      items:
        - title: Booking
          text: |
            Daily rentals available, starting from weekend €1,500, weekday €1,200 and half-day €700.

          feature_icon: home
          features:
            - "email: chateau.buno.essonne@gmail.com"
            - "Address: 2 Rue de l'Essonne 91720 Gironville-sur-Essonne"
            - "Reach out today to secure availability, or with any questions."
          # Upload image to `assets/media/` and reference the filename here
          image: Buno-Wedding-18.jpg
          map:
            enable: true
            latitude: 48.3612222
            longitude: 2.3830556
            zoom: 15
            height: 300px
          button:
            text: See on Map
            url: https://www.google.com/maps/place/48%C2%B021'40.4%22N+2%C2%B022'59.0%22E/@48.3615215,2.3821031,18z/data=!4m4!3m3!8m2!3d48.3612222!4d2.3830556?entry=ttu&g_ep=EgoyMDI1MDQyOS4wIKXMDSoJLDEwMjExNDU1SAFQAw%3D%3D
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---