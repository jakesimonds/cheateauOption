---
title: 'Accueil'
date: 2023-10-24
type: landing

design:
  # Espacement par défaut des sections
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Château de Buno
      text: Lieu d'événement à 50 km de Paris.
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # Pour plein écran, ajoutez `min-h-screen` ci-dessous
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Ajoutez votre image de fond dans `assets/media/`.
          filename: Buno-Wedding-17.jpg
          filters:
            brightness: 0.7
  - block: cta-image-paragraph
    id: events
    content:
      items:
        - title: Événements
          text: |
            Le château de trois étages est situé sur une île au sein de la rivière, entouré de grands arbres et de fleurs, avec des oiseaux partageant la propriété toute l'année. Un paradis tranquille à seulement un train de Paris.

          feature_icon: home
          features:
            - "81 185 m² de terrain"
            - "Parking sur place"
            - "Terrain privé, non visible par les voisins"
            - "Rivière avec accès aux bateaux"
            - "Accessible en transport en commun (RER D)"
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
        - title: Réservation
          text: |
            Locations journalières disponibles, à partir de 1 500 € le week-end, 1 200 € en semaine et 700 € la demi-journée.

          feature_icon: home
          features:
            - "email : chateau.buno.essonne@gmail.com"
            - "Adresse : 2 Rue de l'Essonne 91720 Gironville-sur-Essonne"
            - "Contactez-nous dès aujourd'hui pour vérifier la disponibilité ou pour toute question."
          image: Buno-Wedding-18.jpg
          button:
            text: Voir sur la carte
            url: https://www.google.com/maps/place/48%C2%B021'40.4%22N+2%C2%B022'59.0%22E/@48.3615215,2.3821031,18z/data=!4m4!3m3!8m2!3d48.3612222!4d2.3830556?entry=ttu&g_ep=EgoyMDI1MDQyOS4wIKXMDSoJLDEwMjExNDU1SAFQAw%3D%3D
    design:
      image_position: left
      css_class: "bg-gray-100 dark:bg-gray-900"

  - block: cta-image-paragraph
    id: gallery
    content:
      items:
        - title: Beaucoup d'espace
          image: interior.jpg
        - title: Commodités modernes
          image: interiorBathroom.jpg
        - title: Invitez vos amis !
          image: interiorMeal.jpg
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"

---