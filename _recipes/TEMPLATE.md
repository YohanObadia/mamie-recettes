---
layout: recipe

# Titre de la recette
title: "NOM DE LA RECETTE"

# Type de repas (choisir parmi : Entrée, Plat, Dessert, Goûter, Petit-déjeuner, Apéritif, Boisson)
meal_type: "Plat"

# Qui est à l'origine de la recette
source:
  person: "Nom de la personne"        # ex: "Mamie Alice", "Tante Sarah"
  note: "Détail éventuel"             # ex: "Recette de sa maman", peut être vide

# Pour combien de personnes
portions: 6

# Temps (en minutes, pour pouvoir faire du dynamique plus tard)
prep_time_minutes: 30
cook_time_minutes: 45

# Vidéo (optionnel)
video:
  type: "youtube"                     # "youtube" ou "file" ou "" si pas de vidéo
  url: ""                             # ex: "https://www.youtube.com/watch?v=XXXX"

# Photos (optionnel) – chemins vers les fichiers dans assets/images
photos:
  - /assets/images/nom-de-la-recette-1.jpg
  # - /assets/images/nom-de-la-recette-2.jpg

# Liste structurée d'ingrédients
ingredients:
  - name: "Nom de l'ingrédient"
    quantity: 1.5
    unit: "kg"
    note: "détail optionnel (épluché, ramolli, etc.)"
  - name: "..."
    quantity: 200
    unit: "g"
    note: ""

# Étapes : une phrase par étape (ou plus)
steps:
  - "Première étape de la recette..."
  - "Deuxième étape..."
  - "Troisième étape..."
---

<!-- Texte libre optionnel : anecdotes, histoire de la recette, conseils, etc. -->
