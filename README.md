# Object handling / visualization  using WebGL (PIXI lib):
projet réalisé avec: [PIXI.js lib](https://github.com/pixijs/pixi.js/releases/tag/v4.5.1)

## Description
This project allows the handle of object in 3D motion on a tablet or mobile phone. This is the beginning of what I wish to become a share project. The square object used here has been generated using Blender. Sprites were done with imageMagik.

## Why is the project useful?
The calculation is done through GPU (powerful CPU designed to perform graphical and graphics related calculations)
Tasks remaining:
 - Improve object / bring cool objects to project
 - Improve layout algorithm
 - Improve calculation algorithm
 - Comment code
 - other?

## Infrastructure
######Start:
index.html

######Folder data:
contains json files with coordinates of objectTextures

######Folder silver_sprites:
contains all sprites

## Requires
lib:pixi.js
currently using
<script src="https://cdnjs.cloudflare.com/ajax/libs/pixi.js/4.5.1/pixi.min.js">
</script>

## Methods
- Create new app PIXI.js line 31
- Load sprites  line 37
- Modify elements in the onAssetsLoaded function
