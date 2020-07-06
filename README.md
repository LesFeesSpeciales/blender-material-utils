## Deprecation
This project has moved to [GitLab](https://gitlab.com/lfs.coop/blender/blender-material-utils).

-----

### Blender Material Utils
#### Material tuning
Change some material properties. Useful for recolorizing textures on multiple objects at the same time (eg. add a globally darker shade to a character in a given shot). Blender Internal only.

Internally, this add-on creates a Blender Internal shading nodetree including several filters, and exposes these filter nodes' interfaces in the Material Panel.

![Material Tuning settings](https://raw.githubusercontent.com/LesFeesSpeciales/blender-scripts-docs/master/material_tuning_settings.png "Material Tuning settings")  
The various parameters are simply applied from top to bottom. The `Color2` parameters sets a global hue with a factor.

You can copy the settings from the active object to selected objects.

#### Proxify
Create proxy images to enhance performance in scenes containing a large number of large textures.

-----

# License

Blender scripts shared by **Les Fées Spéciales** are, except where otherwise noted, licensed under the GPLv2 license.
