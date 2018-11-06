+++
title = "Jeu 3D"
date = 2018-10-13T10:22:59+02:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Gaming", "3D"]

# Project summary to display on homepage.
summary = "Développement d'un moteur d'un jeu 3D avec OpenGL."

# Optional image to display on homepage.
image_preview = "dinocap.png"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "dinopre.png"
caption = "Capture in game"

+++

Le principe du jeu est simple : éviter les boites qui sortent du tunnel.
Le dinosaure peut être controlé avec les flèches droite et gauche du clavier.

Le jeu devient de plus en plus difficile et un score est calculé à la fin.

Nous avons fait ce projet à 3. Il a été fait avec **OpenGL** et nous avons écrit nous-mêmes les shaders.
Nous avons mis en place le **modèle de Phong** pour
les effets de lumières. Nous avons aussi utilisé une **heightmap** pour les reliefs.
Nous avons utilisé un **modèle hiérarchique** pour réaliser le bonhomme.


{{< youtube 0PcmvwCwzTk >}}
