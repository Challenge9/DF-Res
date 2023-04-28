# DF-Res

## Description
**NOTE** Not to be confused with upstream [DF-Res](https://github.com/Doom2D/DF-Res/)!

This repository contains game files for [Doom 2D Forever](https://github.com/Challenge9/doom2d-forever) and is meant to be used with [dfwad](https://github.com/Challenge9/dfwad).

## Resources
The resources contained in this repository are organized into the following categories:

- `game`: Audio, image and text files essential to the game.
  - `standart`: Builds into `standart.wad`, containing common resources for map building.
  - `game`: Builds into `game.wad`, containing basic resources such as monsters, weapons and fonts
  - `shrshade`: Builds into `shrshade.wad`, which provides shadow effects/shading.
  - `editor`: Builds into `editor.wad`, containing game editor specific resources
- `maps`: Right now contains the default map pack.
  - `doom2d`: Builds into `doom2d.wad`, which is the default map pack for Doom 2D Forever.
- `model`: Right now contains the default player model.
  - `doomer`: Builds into `doomer.wad`, which is the default model for Doom 2D Forever.

## Examples
- Build `game.wad` using [dfwad](https://github.com/Challenge9/dfwad): `dfwad ./game/game ./game.wad --zlib-level best pack`

## Usage
To use the resources in this repository, either download them from the Releases page or use the download script in [Doom 2D Forever](https://github.com/Challenge9/doom2d-forever) repository.
