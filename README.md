# ARPG Prototype

A 3D roguelike action-RPG prototype made in Godot 4.7. You fight down through randomly generated floors across six biomes: jungle, desert, city, dungeon, castle and abyss. Each floor is a large map with a fixed set of enemy packs to clear, ending with an elemental guardian. You're expected to die, then return to camp, grow your permanent skill tree, take on quests from the camp's characters, and go again.

**Download:** see [Releases](../../releases). Pick the Windows `.zip` or the Linux `.tar.gz`.

## Running
- **Windows:** unzip and run `arpg.exe`. The game isn't code-signed, so SmartScreen may warn you. Click *More info → Run anyway*.
- **Linux:** extract, then run `./arpg.x86_64`. If it isn't executable, run `chmod +x arpg.x86_64` first.

**Requirements:** a 64-bit OS and a GPU with Vulkan support (Windows can also use Direct3D 12). If neither is available, the game falls back to OpenGL with simpler visuals. You can pick a graphics preset (Low to Ultra) under Settings.

## Controls (default; keyboard and mouse can be rebound in Settings)
| Action | Keyboard / mouse | Gamepad |
|---|---|---|
| Move / aim | WASD or click / mouse | Left stick / right stick |
| Primary attack | Left mouse (hold) | RT or LT (hold) |
| Spells | Q E R F | X Y LB RB |
| Dash | Space | B |
| Ultimate (once charged) | G | LB + RB together |
| Interact | Space | A |
| Skill tree (view-only during runs) | K | D-pad Up |
| Quest log | J | Pause menu |
| Inventory and spellbook | Tab | View |
| Stats / map | C / M | |
| Menu (settings, abandon run, quit to menu) | Esc | Start |

## Progression
- **Essence:** earned every run. Spend it at the camp Altar on permanent skill-tree nodes (Fire, Poison, Frost) and new spells.
- **Legendary shards:** salvage a legendary item to get one. Use them during runs to reforge or empower gear, and at the forge to upgrade heirlooms.
- **Deeds:** earned from camp quests and first guardian kills. They unlock auras, starting kits, heirloom slots and ultimates (each guardian's heart unlocks one).

## Status
This is an early prototype, so expect rough edges and balance changes. Saves are stored in your user data folder: `%APPDATA%\Godot\app_userdata\ARPG Prototype` on Windows and `~/.local/share/godot/app_userdata/ARPG Prototype` on Linux.

## Credits
- Engine: [Godot Engine](https://godotengine.org), MIT license (see `GODOT_LICENSE.txt`)
- Characters, dungeon and hex props: [KayKit](https://kaylousberg.com) by Kay Lousberg, CC0
- Bosses, hero, special enemies and landmark props: generated with Meshy AI
- Spell effects, textures, music and sound: made procedurally for this game
