+++
title = "Modélisation 3D"
date = 2018-10-13T20:05:25+02:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["3D"]

# Project summary to display on homepage.
summary = "Modélisation mathématique et implémentation en 3D de la surface d'un océan en C++."

# Optional image to display on homepage.
image_preview = "oceancap.jpg"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "wavemodelprev.png"
caption = "Rendu du modèle de Philips"

+++

Nous avons fait ce projet en binôme. Le but était de modéliser la surface d'un océan.
Il a été entièrement codé en **C++**. Nous sommes partis de rien et
nous avons tout défini : Les vecteurs, la FFT, les matrices, ... Nous
avons utilisé le **modèle de Philips** pour représenter la houle.

Nous avons tout de même utilisé **OpenGL** pour faire le rendu graphique.

{{< youtube Iwg73ez3Uy4 >}}
