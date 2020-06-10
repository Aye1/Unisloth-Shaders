# README
Unity package with some useful shaders

## 2D shaders
### Sprite Outline
Creates a pixel perfect outline around a sprite.
As this shader is based on differences of translations of the sprite, be sure not to put an outline thickness too big.

It may not work either with sprites with really complex shapes if you put a thickness too big.

## 3D shaders
### Water reflection - Case study Zelda Ocarina of Time
This shaders recreates the water reflection effect which can be found in Zelda Ocarina of Time in the Zora's domain.
It blends a given texture with a generated and animated water effect.
