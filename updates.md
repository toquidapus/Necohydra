# Changelog

## [3.2.0] 11/19/24

### Mod Updates
- Updated a small handful of mods.*
- Backported *Mine and Slash* from v5.9.12 to v5.8.3, as it caused issues when playing on servers.
- Backported  *Additional Placements* from v2.1.0 to v1.8.0, as it caused stairs in newly generated worlds to be rotated incorrectly.

### Config Changes
- Fixed the positioning of buttons for *Inventory Profiles Next* in missed GUIs.
- Added support for additional missed plants in the shaders config.

<sub><sup>Chat Heads, Connectivity, Deeper and Darker, First-Person Model, Simple Voice Chat, Skin Layers 3D, Sophisticated Backpacks, Sophisticated Core, Sophisticated Storage</sup></sub>

## [3.1.0] - 11/13/24

### General Adjustments & Fixes
- Fixed unidentified enchantments not being able to be identified at an enchanting table. This was caused by the custom enchanting mechanics added by *Quark: Oddities*. Disabled the enchantment module of *Iron's RPG Tweaks* to preserve functionality.
- Trying to destroy end crystals used to be impossible and would crash the client. This has been fixed by downgrading the versions of *InsaneLib* and *Enhanced AI*.
  
### Cosmetic & UI Improvements
- Repositioned *Quark’s* auto-walking HUD.
- Added a warning tooltip when changing the GUI’s scale to something other than 3x.
- Polished language files (e.g., the chat prompt to set up *Simple Voice Chat*, fixing grammar across mods, etc.) and improved several textures.
- Removed *Potato Shaders* and replaced them with *Complimentary Shaders*. Added compatibility with all modded ores and plants.
- Added a link to the [modpack’s GitHub page](https://github.com/toquidapus/Necohydra/issues) to the main menu.

### Bug Fixes & Enhancements
- Fixed the hunger bar textures when you have the hunger effect.
- When changing gamemodes or opening GUIs, the mouse cursor used to not lock to the window. This has been fixed by removing the *Custom Cursor* mod.

### JEI Changes
- Blacklisted extra Mine and Slash entities from *Jade*.
- Removed the sweet berry cake recipe from *Create: Food*.
- Hid all Ube-related items from *JEI*.
  
### Item & Currency Adjustments
- Replaced vanilla emeralds in villager trades with emerald coins.
- Added a 0.025% daily interest rate for money stored in banks.
- It now costs 1 emerald coin to gain an extra claimable chunk.
- It now costs 1 netherite coin to gain an extra force-loaded chunk.
- Made the minimum cost for traveling by waystone 1 iron coin.


## [3.0.0] - 10/8/24

### Performance Enhancements
- HEAVY performance boosts! Mods are now configured to work together more efficiently.
- Removed several mods (mainly world generation) to improve overall performance.
- Fixed the weird 1-second freeze when opening menus.

### Gameplay Improvements
- Profession XP can now be gained from modded seeds/ores!
- Added a currency system: buy and sell items from other players; money required for waystones usage.
- Rebalanced AI of mobs for improved predictability.
- Added more food items.
- Added ore creepers, which explode into minerals.
- The XP cost of anvils has been balanced.
- Bows with infinity no longer need one arrow in the player's inventory.
- Beds no longer explode.
- Added dummies to test out gear on.
- Added cosmetic armor.
- Added more villager and illager types.

### New Features
- Added lightweight shaders for a more medieval atmosphere.
- New music added (all royalty-free!).
- New 3rd person camera.
- New shields with parrying mechanics.
- On death, players now have 30 seconds to be revived by another player!
- If you ever get stuck, you can kill your character via the "Surrender" button in the pause menu.
- Added an advancement tracking system.
- Added new minigames:
  - Fishing (inspired by Stardew Valley)
  - Enchanting items
- Added a system to quickly compare items.
- Visual improvements on crafting tables and anvils.

### User Interface & Controls
- Improved keybinds! The "Reset Keys" button now resets to proper defaults.
- Reworked HUD and UI heavily.
- Loot beams now display properly.
- Pressing Middle Mouse now pings a block/entity.

### Mod Updates
- Updated most mods to their latest versions.
- Optimized and expanded the resource pack.
  
### Removed Content
- Enchantments Removed:
  - Protection
  - Sharpness
  - Smite
  - Bane of Arthropods
  - Power
  - Impaling
  - Sculk Smite
- Effects Removed:
  - Strength
  - Weakness
  - Resistance
- Removed the Physics mod (3D particles).
- Removed some unobtainable blocks and redundant items/entities (e.g., multiple mods adding crabs).
- Removed "End's Delight" due to useless food buffs.
- Removed a few features from the "Quark" mod.
- Removed extra weapons and effects from "Simply Swords".
