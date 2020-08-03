# VirtuaLightJS

A Physically Based Rendering engine created from scratch in WebGL2, compatible with at least Windows and Linux. (Smartphones not supported, can't test on macOS)

## Demo

Right here: https://frguthmann.github.io/VirtuaLightJS/

## Features

- Multiple meshes loading from .ply or .off files. Plys preferred as they provide UV textures.
- Individual control over meshes position, size and orientation through GUI.
- Multiple point lights with control over color, intensity and position through GUI.
- Fully Physically Based Shading of objects including albedo, metallic, ambient occlusion and roughness map.
- Normal mapping with TBM matrix computed on the fly by the graphic card.  
- Shadow Map for 1 light generated by simulating a directionnal light (WIP) with Percentage Closer Filtering
- Skybox transformed from equirectangular to cubemap at runtime
- Environnement based diffuse lighting with irradiance map baked on the fly from environnement map
- Specular IBL using split sum approximation by Epic Games (Unreal Engine 4) with precomputation at startup.

## Textured Models

- Material ball in 3D-Coat by 3d-coat is licensed under CC Attribution (Sketchfab)
https://sketchfab.com/models/a6bdf1d11d714e07b9dd99dda02de965
- Mask Paint Ball by Odissey Super is licensed under CC Attribution (Sketchfab)
https://sketchfab.com/models/f91ad6cc72c84c6890462907a756a6c8
- Withered Blade by French Baguette is licensed under CC Attribution (Sketchfab)
https://sketchfab.com/models/7647daa204154718a4278e191638909e
- Cerberus by Andrew Maximov
http://artisaverb.info/PBT.html

## Textures

- https://freepbr.com/materials/rusted-iron-pbr-metal-material-alt/
- https://freepbr.com/materials/rough-spaced-tile-pbr-material/
- https://freepbr.com/materials/scuffed-gold-pbr-metal-material/

## IBL Environment
- Arches Pine Tree : http://www.hdrlabs.com/sibl/archive.html

## Great Teachers

- Tamy Boubekeur : http://perso.telecom-paristech.fr/~boubek/
- Joey De Vries : https://learnopengl.com/#!About - https://joeydevries.com/#home
- Etay Meiri : http://ogldev.atspace.co.uk/
- Opengl-tutorials : http://www.opengl-tutorial.org/

### Special Thanks

The original name was coined by Quentin Beauvillard, on Facebook Messenger by a warm night of summer 2017
