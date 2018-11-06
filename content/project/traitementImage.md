+++
title = "Traitement Image"
date = 2018-10-14T11:25:54+02:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["image-processing"]

# Project summary to display on homepage.
summary = "Développement d'algorithmes en C de débruitage et de détection de contours."

# Optional image to display on homepage.
image_preview = "imageprocessing.jpg"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

Dans ce projet en binôme nous avons implémenté plusieurs algorithmes de débruitage et de détection de contours.
Pour le débruitage nous avons utilisé :

 * filtre gaussien

 * filtre médian

 * filtres adaptatifs (récursif, bilatéral, ...)

Pour la détection de contours nous avons mis en place le filtre LoG (Laplacian of Gaussian).

Nous avons ensuite évalué les performances de chacune de ces méthodes.
