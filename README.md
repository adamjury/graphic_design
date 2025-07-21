# graphic_design

This is a folder of resources I have made as a graphic designer. Many are not advanced rocket science, they are simple tools that do single jobs.

## indesign

### KerningHack.idml

InDesign used to let you make Character Styles that applied kerning. This is technically wrong, illogical, extremely naughty, and also: sometimes very useful. At some point they made it impossible for you to make new Character Styles in this way, but previously-existing styles still work just fine.

This IDML file contains a number of character styles that will apply kerning — and nothing else — to your text. They range from -1000 to +1000. If you need to apply a global modification to all kerning hack styles, modify "kerning_parent" Character Style.

## photoshop_actions

### make_layercomp_artistdefault.atn

Run this when you open a new piece of art/design. It will take the current layer settings and make a layer comp named "artist_default" so you can easily revert to the settings the artist used.

In almost all situations you will want to modify layered artwork for your own purposes — removing a background color, lightening the glow/shadow, etc. Saving them as layer comps is often better than re-saving/forking the image, but you always want to be able to back up to what the artist originally intended.