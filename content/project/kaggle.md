+++
title = "Kaggle"
date = 2018-11-06T10:12:05+01:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["machine-learning"]

# Project summary to display on homepage.
summary = "Classification de crimes à San Francisco codé en Python (Tensorflow, Keraz, Pandas, ...)"

# Optional image to display on homepage.
image_preview = "kagglecap.png"

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "kagglepre.png"
caption = ""

+++
Ce projet a été fait en équipe de 4.
Il consistait à mettre au point un classifieur de crimes : étant donné
certaines données du crime (date, heure, localisation, ...) il s'agissait de prédire
 la catégorie de celui-ci (Burglary, driving under the influence, ...).
 Nous avions pour cela à notre disposition un ensemble de données de crimes fournis
  par la ville de San Francisco.

Nous avons utilisé : **réseau de neurones** (Keraz), **forêt aléatoire** (Scikit-learn),
 **k-means**, ...
