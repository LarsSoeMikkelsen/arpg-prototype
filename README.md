# ARPG Prototype

A 3D roguelike action-RPG prototype made in Godot 4.7. You fight down through randomly generated floors across six biomes: jungle, desert, city, dungeon, castle and abyss. Each floor ends with a guardian boss. You're expected to die, then return to camp, spend what you brought back, and go again.

**Download:** see [Releases](../../releases). Pick the Windows `.zip` or the Linux `.tar.gz`.

## Running
- **Windows:** unzip and run `arpg.exe`. The game isn't code-signed, so SmartScreen may warn you. Click *More info → Run anyway*.
- **Linux:** extract, then run `./arpg.x86_64`. If it isn't executable, run `chmod +x arpg.x86_64` first.

**Requirements:** a 64-bit OS and a GPU with Vulkan support (Windows can also use Direct3D 12). If neither is available, the game falls back to OpenGL with simpler visuals. You can pick a graphics preset (Low to Ultra) under Settings.

## Controls (default; everything can be rebound in Settings, including mouse buttons)
| Action | Keyboard / mouse | Gamepad |
|---|---|---|
| Move | WASD | Left stick |
| Aim | Mouse | Right stick |
| Primary attack | Left mouse (hold) | RT |
| Dash | Space | |
| Spells | Q E R F | X Y LB RB |
| Interact | Space | A |
| Inventory and spellbook | Tab | View |
| Menu (settings, abandon run, quit to menu) | Esc | Start |

## Status
This is an early prototype, so expect rough edges and balance changes. Saves are stored in your user data folder: `%APPDATA%\Godot\app_userdata\ARPG Prototype` on Windows and `~/.local/share/godot/app_userdata/ARPG Prototype` on Linux.

## Credits
- Engine: [Godot Engine](https://godotengine.org), MIT license (see `GODOT_LICENSE.txt`)
- Characters, dungeon and hex props: [KayKit](https://kaylousberg.com) by Kay Lousberg, CC0
- Bosses, hero, special enemies and landmark props: generated with Meshy AI
- Spell effects, textures, music and sound: made procedurally for this game
