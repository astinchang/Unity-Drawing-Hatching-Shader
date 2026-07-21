# Unity-Drawing-Hatching-Shader
**Drawing/hatching shader post-processing effect including scripts, shader code, and sample scene** <br>
**Made for 3D Built-In Render Pipeline w/ the Post Processing package found in the standard Unity Registry**

I wrote a postprocessing effect that renders the scene as a
hatched ink sketch with outlines. Original scene is turned into greyscale, and
brightness is separated out into an adjustable number of shading layers, with
darker tones stacking more layers of procedural hatch strokes (triangle waves
over rotated screen coordinates). Each layer is at a different angle, multiplied
together so intersections darken like ink. Outlines come from sampling all
pixel neighbors from the camera's depth-normals texture. Lots of adjustable
features in inspector controls!

## Demo Screenshots:
<img width="616" height="708" alt="image" src="https://github.com/user-attachments/assets/c335b590-e917-48ff-8893-1ba0a6b8354b" />
<img width="615" height="345" alt="image" src="https://github.com/user-attachments/assets/b175b0ad-8098-4f40-bb4f-2583669abba2" />

**Credit for assets:** <br>
House: https://assetstore.unity.com/packages/3d/environments/fantasy/stylisedfantasy-house-257964 <br>
Trees: https://assetstore.unity.com/packages/3d/props/exterior/cartoon-lowpoly-tree-211305<br>
Grass: https://assetstore.unity.com/packages/2d/texturesmaterials/glass/stylized-grass-texture-153153 <br>

**Credit for inspiration:** <br>
https://www.youtube.com/watch?v=NrYGC4hyCVg <br>
Praun et al., "Real-Time Hatching" <br>

## Extra Screenshots:
<img width="618" height="710" alt="image" src="https://github.com/user-attachments/assets/b77ba837-5496-4395-805c-cb9c42ec8a4e" />
<img width="618" height="719" alt="image" src="https://github.com/user-attachments/assets/3d82b7d6-5eba-459c-8268-cca4e2cc405f" />
