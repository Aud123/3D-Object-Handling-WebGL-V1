# Handling of objects using WebGL (PIXI lib):
# https://github.com/pixijs/pixi.js/releases/tag/v4.5.1

## Description
This project allows the handle of object in 3D motion using a tablet or mobile phone. This is the beginning of what I wish to become a share project. The square object used here has been generated using Blender. Sprites were done with imageMagik.
Tasks remaining:
 1 Improve object / bring cool objects to project
 2 Improve layout algorithm
 3 Improve calculation algorithm

## Infrastructure
## Start
index.html
## Folder data
contains json files with coordinates of objectTextures
## Folder silver_sprites
contains all sprites

###Requires
lib:pixi.js
currently using <script src="https://cdnjs.cloudflare.com/ajax/libs/pixi.js/4.5.1/pixi.min.js"></script>

###Methods
-> create new app PIXI.js line 31
-> load sprites  line 37
-> Play with the onAssetsLoaded function
