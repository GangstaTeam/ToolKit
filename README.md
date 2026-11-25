[![Download Latest Release](https://img.shields.io/github/v/release/GangstaTeam/ToolKit?display_name=release&label=Download%20Latest%20Release&color=21ABC7)](https://github.com/GangstaTeam/ToolKit/releases/latest/download/ToolKit.zip)

# ToolKit

Modding toolkit for Scarface: The World Is Yours (PC).

| Workspace | What it does |
|---|---|
| Pure3D | Opens and edits `.p3d` files: chunk tree, properties, hex view, textures and a 3D viewport. Imports your own models as characters on the game's skeleton, and animations from Mixamo/Blender (`.fbx`, `.glb`). |
| Frontend | Shows the menus and HUD (`frontend/*.p3d`) as the game draws them; move, edit and multi-select elements. |
| Archive | Browses `.rcf` archives: extract, add, replace and rebuild. Plays the sounds inside and shows their original names. Files opened from an archive save back into it. |
| Script | Edits TorqueScript (`.cs`) with highlighting, live errors and autocomplete for the game's natives and functions, and compiles it to `.cso` (F7). |
| Game | Inspects the running game's menus and HUD, live. |
| NIS | Edits cutscenes (`art/nis/fsc/*.fsc`) on a timeline. |

## What's new

- Script workspace: write TorqueScript with syntax colours, errors as you type, suggestions and descriptions for every game native, and compile it to `.cso` with F7.
- Archive: compiled scripts (`.cso`, `.dso`) open as readable source and extract as `.cs`.
- Animations: play any clip on a character, then rename, trim, change speed or loop, duplicate, replace or export it.
- Import animations from Mixamo or Blender (`.fbx`, `.glb`, `.gltf`) onto the game's characters, with a live preview.
- Export a character for Mixamo straight from the viewport.

## Screenshots

| | |
|---|---|
| ![Pure3D](images/pure3d.png) | ![Character import](images/character-import.png) |
| Pure3D: Tony with his skeleton | Character import: a custom model on the game's skeleton |
| ![Frontend](images/frontend.png) | ![Frontend](images/frontend-vendor.png) |
| Frontend: the Empire menu | Frontend: the street vendor |
| ![Frontend](images/frontend-blackjack.png) | ![NIS](images/nis.png) |
| Frontend: blackjack | NIS: a cutscene timeline |

## Installation

1. Download [ToolKit.zip](https://github.com/GangstaTeam/ToolKit/releases/latest/download/ToolKit.zip).
2. Extract it anywhere and run `ToolKit.exe`.
3. For the Game workspace, copy `plugins/ToolKitLink.asi` into the game's `plugins` folder.

> [!NOTE]
> The Game workspace needs the v1.00.2 game executable and an ASI loader.
