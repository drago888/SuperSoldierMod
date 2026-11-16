# Super Soldier Mod

An Owlcat-template mod for **Warhammer 40,000: Rogue Trader** that adds **Super Soldier**, a new archetype based on the Soldier:

> A genetically engineered Super Soldier who is superior to normal humans in every way.

## Requirements

> [!IMPORTANT]
> **[MicroPatches](https://www.nexusmods.com/warhammer40kroguetrader/search/?keyword=MicroPatches) by microsoftenator2022 is required.**
> Without it this mod will not load correctly. Install the latest version of MicroPatches **before** installing this mod.

MicroPatches is a Unity Mod Manager mod. You can install it manually or through [ModFinder](https://www.nexusmods.com/warhammer40kroguetrader/search/?keyword=ModFinder).

## Features

- **Super Soldier career path** (tier 1), selectable at character creation for the Rogue Trader, Navigator start and custom companions.
- **Super Veteran** (tier 2) and **Super Ascension** (tier 3) career paths that follow on from it.
- Super Soldier also counts as a valid tier 1 path for the vanilla tier 2 archetypes (Veteran, Tactician, Hunter) and for Ascension.
- **Prologue fixes for the new class:**
  - Abelard hands over the Soldier starting weapons after the Warrant Chamber.
  - The class chest after meeting Argenta spawns with the Soldier gear and the key to the nearby door.
- **Voidship buff:** the starting frigate (Sword class, which the Firestorm class inherits from) gets **240 hull integrity** and **24 armour** on every side.

## Installation

1. Install **MicroPatches** (see Requirements).
2. Download this mod and extract the `SuperSoldierMod` folder into:
   ```
   %userprofile%\AppData\LocalLow\Owlcat Games\Warhammer 40000 Rogue Trader\Modifications\
   ```
   The result should be `...\Modifications\SuperSoldierMod\OwlcatModificationManifest.json`.
3. Enable the mod in `OwlcatModificationManagerSettings.json` (or with ModFinder / the Owlcat mod manager).
4. Start a **new game**. The prologue and voidship changes only apply to fresh playthroughs.

## Compatibility

- Mods that change the same blueprints (prologue gear, the class chest, the player starship, or the vanilla career path prerequisites) may conflict.
- Enabling mods disables achievements unless you use a mod that re-enables them.

## Troubleshooting

Check `GameLogFull.txt` in:
```
%userprofile%\AppData\LocalLow\Owlcat Games\Warhammer 40000 Rogue Trader\
```
Search it for `SuperSoldierMod` to see whether the mod and its patches loaded.

## Author

Ng Kock Leong
