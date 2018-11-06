+++
# Projects widget.
widget = "projects"
active = true
date = 2016-04-20T00:00:00

title = "Projets"
subtitle = ""

# Order that this section will appear in.
weight = 50

# Content.
# Display content from the following folder.
# For example, `folder = "project"` displays content from `content/project/`.
folder = "project"

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# To show all items, set `tag` to "*".
# To filter by a specific tag, set `tag` to an existing tag name.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
 [[filter]]
   name = "Tous"
   tag = "*"

 [[filter]]
   name = "Gaming"
   tag = "Gaming"

 [[filter]]
   name = "Traitement Image"
   tag = "image-processing"

  [[filter]]
     name = "Modélisation 3D"
     tag = "3D"

  [[filter]]
        name = "Machine learning"
        tag = "machine-learning"

 [[filter]]
    name = "Autres"
    tag = "other"

+++
