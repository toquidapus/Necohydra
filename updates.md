# Changelog

## §6[3.4.1] §7- §79/6/25

### Gameplay
- Mining with weapons is now allowed by default.
- [G] now quick consumes *Mine and Slash* potions, rather than Quick Turning with *Parcool!*
- Pressing [Middle Mouse] on water no longer grants you a boat with Minecraft's Pick Block behavior.
- Disabled the keybind for *Deeper and Darker's* Sculk Transmitter by default.
- The ability to open other players Backpacks has been disabled completely.
- Skeletons now flee players from a smaller range, and are slower when fleeing.
- Removed the Soulsteal effect.
- Removed the Reach effect from *Friends & Foes*.
- Updated *ETF*.
### Visual Improvements
- A handful of quests have been updated to have images in their descriptions.
- Reverted the "Hub" icon to access the *Mine and Slash* hub whilst holding [E].
- Made the "Update Available!" text on the titlescreen flash to increase visibility.
### Balancing
- Horses, Mules, Donkeys, Camels, Llamas, and Trader Llamas no longer drop Leather.
- Camels and Llamas now have the same rarity, increased health, and 20% damage reduction like Horses, Mules, and Donkeys.
- *Minecolonies* town Visitors now have the same rarity, increased health, and 50% damage reduction like Citizens.
- Entities that spawn with Backpacks no longer get health / potion effect buffs.
- Backpack upgrades now only automatically work if the Backpack is equipped.
- Reduced gear drop rates from 18 > 14.
- Reduced currency drop rates from 3 > 2.
- Decreased the mob and item level variance from 3 > 2.
- Favor is now capped at 1000 (mythic).
- Gear now gains +5% physical damage per sharpness level.
### Bug Fixes & Consistency
- Disabled Mipmap levels by default, to prevent an unloaded texture glitch. (It is unknown if this actually fixes the bug! Please report if this bug remains.)
- Weapon mastery now works properly!
- Fixed *FTBQuests* commands not working (PVP Toggle, *Mine and Slash's* mastery button).
- Removed the Shadow Hands enchantment, as it would crash clients and corrupt chunks at random.
- Disabled the Fen, Fungal Fen, Marsh, Frozen Pine Taiga, Pine Slopes, Pine Taiga, Icy Heights, Mountains, Redwoods, Sparse Redwoods, Rainforest, Sparse Rainforest, Rocky Reef, Bayou, Tropics, Tropical River, and Willow Forest biomes from *Regions Unexplored*, as other mods already have Dead, Pine, Redwood, and Willow Wood.
- Disabled Pine, Dead Pine, Dead, Redwood, Palm, and Willow Wood / Hedges from *Regions Unexplored* in *Every Compat*.
- Players are no longer required to choose an icon upon Domain creation, as it can be bypassed anyways.
- Removed the buttons on Domain creation that allows changing the type of world generation (ex. Superflat) and customization of world generation, as they do not work.
- Disabled a bugged Curio slot.
- For consistency, the tooltip when hovering over the "Cosmetic Armor" button in the player's inventory has been removed.
- Disabled Firefly particles from *Subtle Effects*, as *Subtle Effects* has Firefly entities.


## §6[3.4.0] §7- §79/2/25

### Gameplay
- Added the mod *Better Durability Reforged*. Items can no longer fully break, but once at minimum durability, they are disabled. (Bug: You must reequip armor after repairing it for their bonuses to take effect.)
- Necohydra now implements *You Shall Not Spawn!* to disable Creepers from spawning. This is due to a *Mine and Slash* bug where Creepers down players in one hit. There are still several alternatives to obtaining gunpowder, and many other tweaks were tested to prevent this change. All Creepers from *Creeper Overhaul* have been removed aswell. Don't worry, Ore Creepers will remain!
- Rather than dealing damage, Ore Creepers now have the Blindness affect, and will affect players with it if hit.
- Ore Creepers no longer explode into ore. Killing them still drops ore, and instead, the player must kill them before it explodes to gain its loot. Due to this, Ore Creepers now drop severely more loot when killed!
- Removed the mod *Airdropped Loot Mobs* in place of Ore Creepers.
- Imbuing has been updated to support all LVL >I enchantments.
- Removed Ancient Tomes from *Quark*, as *Illager Invasion's* Imbuing Table and related items have a more in depth and balanced alternative.
- *Mine and Slash* Stones can now be combined to craft rarer ones.
- Removed several keybinds from *Inventory Profiles Next*. (No more random "Created new "Default" profile..." messages!)
- Changed the keybind to access *Create's* Toolboxes from [Left Control] to [Tab].
- Disabled Auto Refilling of items with *Inventory Profiles Next / IPN* by default. It can now be toggled by pressing [F7].
- Features from *Parcool!* can now be toggled by pressing [F6].
- *Better Lost Candle* has been added to make *Illager Invasion's* Lost Candle item have dynamic lighting, and detect non-vanilla ores.
- Readded Spawn Eggs in the creative inventory.
- Special Horse Feed can now be crafted to permanently increase a horse's max speed / jump height.
- Horses can no longer kick off their riders in fear of hostile mobs.
- Updated 128 mods.

### Visual Improvements
- Added the resource pack *Wolf Variants* from Forest on Modrinth. The Wolf variants from newer Minecraft versions will now display!
- Added the resource pack “Comforts Modernized” from pedro041506 on CurseForge / Modrinth. Items from the *Comforts* mod now match the style of Minecraft more.
- Hid the horizontal scrollbar on the Changelog on the title screen. (Note: It unfortunately cannot be fully disabled.)
- Updated the "Hub" icon for *Mine and Slash* while holding [E].
- Changed Minecraft's "Leave Bed" text to more accurately say "Stop Sleeping" due to mods.
- Restored Vanilla particles shown when throwing Bottles of Essence.
- Updated the texture for horse inventories, and Custom Tacks.
- Changed the texture of *Create's* Haunted Bell to have its "soul" be magenta.
- Changed the texture of *Illager Invasion's* Imbuing Table, and Primal Essence to fit into the modpack more.
- Increased the volume of MIMI by default from 5 > 10.
- Disabled fog from *Particle Rain*.
- Vanilla styled Boats have all been renamed and remodeled to Canoes to match *Small Ships*. Credit to DiegoxDios's "Boats and Canoes" model!
- Added custom sound effects to Ore Creepers.
- Blacklisted several entities from *Jade*.
- Removed the mod *Better Fog*, as it messed with visuals given by the Blindness and Darkness effects.
- Removed the "Executed # Commands..." text from FTBQuests. (Note: This was done via a language file change, please keep note of this if you use custom functions!)
- Removed *Fast Workbench's* Crafting Table tooltip to match with modded Crafting Tables.
- Increased the size of player pings with [Middle Mouse] from 150% > 200%.
- Ore Creepers now have improved visuals on death that simulate Necohydra's block breaking visuals.
- Sound effects of Ore Creepers have been changed to differentiate them from regular Creepers.
- Modified screen effects when being affected by potions to be shorter, and less obtrusive.

### Balancing
- Increased the loot multiplier of higher rarities.
- Replaced the Soulsteal and Patrol Bane enchantments from Beacons with Poison Resistance and Nourishment.
- All Horses, Donkeys, and Mules now have significantly increased health, and 20% damage reduction.
- The rarities of Ore Creepers have been modified to match their ore rarity.
- Skeleton and Zombie Horses no longer have loot to prevent farming items when set as a personal horse. (Issue: Essence still drops.)

### Bug Fixes & Consistency
- (Excluding Zombie and Skeleton Horses) All vanilla Horses / Mules / Donkeys will now automatically be replaced with modded variants.
- Removed Tin Cans from *Aquaculture,* and replaced fishing loot tables that give them with the ones from *Crabber's Delight*.
- For consistency, Vanilla styled modded Boats have been removed.
- Removed all Horse Armor, and instead implemented horse tacks to be used instead as they go in the same slot.
- *Simply More* now uses a Forge file instead of a Fabric file.
- Tweaked *MineColonies* research for *Mine and Slash* compatibility, and to use more items from Necohydra.
- Combined the Technology and Unlockbles University trees in *MineColonies*.
- To match newer Minecraft snapshots, and to add convenience for Necohydra's mods regarding horses, Saddles can now be crafted.
- Removed the Blackstone Furnace from *Quark*, as *Nether's Delight* has a duplicate alternative.
- Fixed *Create's* Toolbox inventory sorting buttons.
- Slightly modified fishing loot tables.
- Fixed an incorrect tutorial regarding Stamina.
- Disabled the Ore Scenting and Total Recall enchantments from *Domestication Innovation*.
- Features of *Parcool!* have been updated to not work in newly added *Mine and Slash* dimensions.
- Updated *Waystones* to not allow traveling in and out of the new Harvest dimension.
- Fully removed missed Crab items from *Friends and Foes*.
- Hid Horse stats from *Jade*, as they are not accurate after the stats of the Horse are modified.
- Fixed and repositioned inventory sorting buttons in a handful of GUIs.

## §6[3.3.1] §7- §75/10/25

### Visual Improvements
- The *Blur* mod no longer has its visuals display when the Build Tool from *MineColonies* is in use.
- The player can no longer hear themselves with *Simple Voice Chat* in echoey rooms with the *Sound Physics* mod.
  - This behavior can be reverted by going to *Sound Physics* Config > Client > Hear Self: ON.

### Bug Fixes & Consistency
- The initial keybinds that come with Necohydra now properly work, with no issues!
- Fixed our Discord invite link on the title screen, and the CurseForge page.
- Updated the CurseForge button on the title screen to have proper punctuation.
- The low RAM allocation warning no longer appears when the player has the exact amount of suggested RAM allocated.
- For most launchers, Necohydra will now automatically ship with 8192MB of RAM automatically allocated.
- Fixed the gender mod and cosmetic menu, and disabled breast physics from *Wildfire's Gender Mod* PROPERLY this time. (Yes, you read that correctly.)
- Creepers no longer explode upon being slain.
- Back buttons within *Mine and Slash's* GUI now work properly. This unfortunately is not possible with the Stats menu, so the back button here has been removed.
- Added a back button to *Mine and Slash's* Ascendancy, Prophecy, and Map pages, and implemented Necohydra's custom mouse cursor on each as well.
- Increased the size of chat from 60% to 90%.
- Increased the width of chat from 222px to 252px.
- Updated *Mine and Slash's* favor textures to properly match its rarity.
- Changed the video loading icon in *WATERMeDIA* to fit the style of Minecraft more.
- Blacklisted bullets from appearing on *Jade.*
- *Jade* now displays if a block is unbreakable.
- Removed the mod *Shoot Glass,* as its behavior would also delete thrown Tridents. Unfortunately, disabling this deletion in the mod's config would make projectiles float midair, so it has been removed altogether.
- The mod *Better Farmers Combat* has been removed, as it was accidentally left over as a disabled mod in v3.3.0. Whoops!

## §6[3.3.0] §7- §73/1/25

### Gameplay
- Added a weapon mastery system with *FTB Quests.* This adds 498 quests!
- Added the mod *MineColonies.* Build your own town, and reclaim Panjeria by rebuilding it from the ground up!
  - §7(§5EXPERIMENTAL. §7Please §7report §7any §7bugs §7/ §7inconsistencies §7you §7may §7find §7on §7Necohydra's §7Github §7issues §7page!)
- Added the mod *WATERFrAMES.* This allows for videos to be played in game!
- Added *The Fletching Table Mod.* Arrows can now be given potion effects in mass quantities.
- When holding an empty bottle, right clicking now consumes 20 essence §7(experience) points to fill it up! While you lose a few extra points compared to simply finding one naturally, this is useful for crafting recipes and quests that require essence.
- Added guns with *ewewukek's Musket Mod,* which are compatible with *Mine and Slash* and can be used by mobs!
- Added the mod *Simply More,* which adds 10 more weapons.
- Added the mod *Stick n' Stone,* giving all *Simply Swords / More* weapons wooden and stone variants.
  - All of the weapons above have been properly integrated into *Mine and Slash,* and can now also be found as natural loot!
- Added extra bows with the mod *Iron Bows,* and gave them smoother animations.
- Enabled the "Enhanced Ladders" feature on *Quark:* right clicking a ladder with another one will place it, allowing you to drop ladders downwards.
- When the player's soul lingers §7(when §7the §7player §7needs §7to §7be §7revived §7from §7the §7*Hardcore §7Survival* §7mod), there is now a button that allows them to call for help.
- Added the mod *Dropped Buffs.* Small chunks of health, absorption, haste, or speed now have a small chance to drop when entities are slain.
- Added extra bows and crossbows with the mod *Iron Bows.*
- Added the datapack *True Ending* to make fighting the Ender Dragon more intense.
- Increased the maximum amount of saveable *Mine and Slash* characters from 7 to 8.
- Reimplemented several *YUNG's Better...* mods, similar to past Necohydra versions. (Performance issues are now fixed!!)

### Visual Improvements
- Updated the icon of the modpack.
- Improved visuals on the main menu of the game.
- Fixed all HUD to display properly on a basic 1080p display at 2x scaling.
- For all impacted screens, forced GUI scales have been removed.
- Added a built in LUT map to give the modpack a more medieval theme! Fabulous mode must be enabled in the game's graphics settings for this to work.
- Made *Loot Beams* compatible with *Mine and Slash.* (No more missing out on rarer items!)
- Removed the mod *Clear Despawn,* as *Interactic* makes its added visuals not display.
- A brief red flash now shows when the player takes damage.
- Entity healthbars now only display when the entity is not at full health. §7(This §7behavior §7can §7be §7reverted §7in §7*Mine §7and §7Slash's* §7config §7-> §7*Neat.*)
  - Due to this, Shulkers, Villagers, Guard Villagers, and Wandering Traders / Bakers now have visible healthbars.
- Disabled *Traveler's Titles* in *Mine and Slash* dungeons.
- Fixed language file errors regarding the *Tips* mod.
- Added support for sending and receiving images in chat! There is now a button in chat to auto input the required command to do so.
- Hid buttons from *Inventory Profiles Next* in the player's inventory.
- Most instances of the word "world" have been replaced with "domain" for consistency regarding v3.2.0's language file changes.
  - On top of this, several language files have been changed to increase consistency between mods.
- Vanilla experience has been renamed to "essence." §7(Don't §7worry, §7it §7still §7functions §7the §7same!)
- Blacklisted various entities from appearing within *Jade.*
- Fixed *Loot Journal's* HUD being too high up.
- Made it more obvious that screenshots are copied to the clipboard in screenshot text.
- Villagers, Guard Villagers, Wandering Traders / Bakers, Trader Goblins, and Citizens now have healthbars that look similar to one of a player.
  - This also includes their zombified variants.
- Players now have special visual effects on death.
- Mining blocks now have different visuals.
- Disabled *Quark's* "usage ticker" feature.
- Added an arachnophobia resource pack. 
- Updated the amount of rows that *JEI* displays.
- Textures and item names in *Lightman's Currency* and related mods have been updated to be more medieval.
- Changed how the player's coin balance from *Lightman's Currency* appears ( ex: 2n5d8e3g7i4c -> $2,583.74 )
- When events are occurring in our official Minecraft server, the title screen will now update to match!
- Reimplemented the custom mouse cursor from previous versions of the modpack. (Now bug-free!)
- Added the mod *Particle Rain.*
- Some chestplates now have visible gloves to add more depth to them.
- It is now easier to see when using any shield or crossbow variant with the *First Person Model* mod.
- Updated death waypoints to fit the theme of the modpack better.
- Changed the textures for gold armor.
- Added the mod *Camera Overhaul.* Dodging and flying feels extra satisfying now!
- Added the mod *Soul Fire'd.*
  - §7Soul §7fire §7in §7first §7person §7does §7not §7visually §7appear §7lower §7like §7regular §7fire §7due §7to §7limitations!
- Additional weapons now display on your side properly when unequipped.
- All skin customization settings can now quickly be changed from a keybind, which can also be accessed by holding [E] and selecting "Customization."
  - Quick buttons have been added in this menu for the *EMF, Ears, and 3D Skin Layers* mods.
  - To match the citizens of *Minecolonies,* you can now change your gender on this screen as well.
- Disabled *Amendments's* ability for tipped arrows to appear on crossbows for consistency, as it doesn't support modded crossbows.
- Changed the positioning of the icons in *Simple Voice Chat* to be above the local player's icon in the bottom left corner.
- Added support for additional plants in the modpack's built in shaders.
- Renamed the default crafting table for consistency.
- Hid unneeded *FTB* buttons from the inventory.
- Disabled *Appleskin's* hunger exhaustion underlay, as it causes confusion when the player has saturation.
- Added the mod *Runelic,* which adds an extra usable font and banner patterns. 
- All (non *Mine and Slash*) soul related items have been changed to be magenta for lore.	
  - Due to this, *Illager Invasion's* magic fire is now green.
- Added back buttons on *Mine and Slash's* GUI screens.
- Updated the end poem for lore consistency.
- The heartbeat effect that appears when the player has low health has been modified.
- Hid unneeded *FTB* buttons from the inventory.
- Fixed the description for the Lightweight enchantment.
- Removed the mod *First Person Model,* due to mod incompatibilities. </3
- Modified the visuals of *Mine Menu.*
- Players can now change the icon of newly created Domains.
- Domains will now have the option for randomly generated names on creation. There are 42,403,600 possible combinations!
- Loot beams no longer only appear on items that are on the ground §7(this §7was §7done §7with §7items §7floating §7in §7water §7in §7mind).
- Music no longer plays when the player's soul fades away.
- *Create's* Contraption speed HUD is now properly visible.
- Added the mod *Wakes.* Water now has improved visual effects, with waves and splashes!
- Disabled *Quark's* attribute tooltips, as they are misleading regarding *Mine and Slash* stats.
- Renamed the "Minecraft with Workbench" item to "Minecart with Crafting Table."
- Jewels have been renamed to Emblems, to prevent confusion with Gems.
- Added the mod "*Highlight.*" Selection outlines of blocks are now more consistent!

### Multiplayer
- Renamed the default server to Panjeria, and updated its IP.
- Added the mod *e4mc.* Players can now easily play multiplayer with other players without the need of hosting a server!
- Added an easier method toggleable PVP per player §7(off §7by §7default). This can be accessed by holding [E] and selecting "PVP Settings."

### Performance
- Added a warning that displays if less than 8192 MB of RAM is allocated to the modpack.
- Improved performance regarding pathfinding.
- *Better Stats* and related dependencies have been removed, as it caused issues when connecting to servers.
- Removed the mod *Global Gamerules,* and put its equivalent data in a datapack to save storage.
- Blacklisted several phrases from being printed in the game's logs in order to prevent excessive disk space usage.
- Added the mod *Structure Essentials.*
- Fixed several issues regarding shader crashes by updating *Iris & Oculus Flywheel Compat.*

### Balancing
- The level of mobs is now synced to nearby players once again, rather than the distance to spawn.
- Movement related ablities of *ParCool* are no longer usable in *Mine and Slash* dungeons (Breakfalling and Flipping is still possible!) (While it isn't from *Parcool,* dodge rolling is still possible as well.)
- Players now drop 10% of the coins in their wallet on death.
- Players now lose 10% of their essence §7(experience) on death. Players also now spawn in with 5 starting levels.
- (Finally) disabled pickaxe zombies.
- Disabled the ability for mobs to use Fishing Rods on players.
- The range of all skeleton variants have been decreased.
- Mobs can no longer detect players through walls as well.
- Mobs with the blindness effect now have their pathfinding range reduced by 75%.
- Bosses now regain health if a player dies nearby.
- *Anti Mob Farm* now affects *all* dropped loot, instead of *Mine and Slash* loot only.
- Removed Skelewag Skulls.
- Witches can no longer throw potions of weakness. They also throw normal potions of harming I, instead of harming II.
- Disabled the ability for Witches to drink potions of instant health.
- Increased the chance for Tumbleweeds to spawn.
- Increased the cooldown for Warp Stones and Scrolls from 32 ticks to 50 ticks.
- Villagers, Wandering Traders / Bakers, and Citizens now have a 50% damage reduction.
- Zombie Villagers, Guard Villagers, and Mercenaries now have a 10% damage reduction.
- Guard villagers will no longer attack wandering bakers.
- Guard villagers now spawn with an increased variety of gear.
- Doubled the amount of rewards given from *Bountiful,* and decreased the cost of bounties by 15%.
- Abilities of *ParCool* are no longer usable in *Mine and Slash* dungeons.
- Fire no longer spreads, but still ticks.
- Coins have been added to the cost of *Mine and Slash* recipes.
- Players now gain 12% more *Mine and Slash* player level experience.
- The player now only gets less *Mine and Slash* player experience when defeating a mob that is 3 levels above / below them, rather than *any* difference in level.
- When dying, the player will now lose half less *Mine and Slash* player experience compared to before.
- The drop rate of gear when killing mobs has been increased by 20%.
- Upon soul loss, the player will now receive 80% less experience debt compared to before.
- The Quickdraw spell no longer grants the player a stack of arrows.
- Increased the default max health from 80 to 400.
- Increased the default max mana and dexterity from 50 to 80.
- Players now start off with 80 magic shield.
- Players now start off with a flat dodge rating of 2.
- Armor points now give you some *Mine and Slash* armor.
- Natural health regeneration has reduced heavily. To mirror the style of other games, magic shield will now be the player's main form of regenerating health.
- Each point of strength now gives +20 health, instead of +5.
- Each point of strength now gives +0.5 additional health regeneration per second, instead of +0.25.
- Each point of intelligence now gives +2% magic shield, instead of +0.5%.
- Magic shield now scales with your player level.
- Severely increased the chance for *Mine and Slash* gems, runes, and currency related items to drop.
- The level requirement of loot can now vary by two levels, instead of one.
- Doubled the time downed players have for their souls to be recovered.
- Every Ender Dragon kill will now drop an egg. §7(Added §7with §7servers §7in §7mind!)
- Slightly increased the chance for Launching Creepers to spawn.
- Reduced the explosion power of creepers by 0.5.

### Bug Fixes & Consistency
- Some removed enchantments have been reimplemented, and are now functional.
- The Backstabbing enchantment has been removed.
- Thrown tridents now deal damage.
- Equipping charms in your offhand no longer crashes the game.
- Fixed a *Mine and Slash* bug where mmorpg:invisible_item items and Omens could be picked up.
- Removed the sonorous staff from *Deeper Darker.*
- Blacklisted additional items and entities from *Carry On.*
- Updated keybinds that should not be changed on the keybinds list to display as [UNUSED].
- Macaw's wall lanterns have been removed, as *Amendments* has the same functionality but with the same lanterns.
- Blacklisted the Dragon Egg from the *Trash Slot* mod.
- Removed all copper buttons from *Infinity Buttons,* as *Friends and Foes* has equivalent, more functional counterparts.
- Removed iron and gold buttons from *Quark,* as *Infinity Buttons* has equivalent, more functional counterparts.
- Removed all items relating to forge energy (FE), as no mods in Necohydra implement it. §7(Not §7to §7be §7confused §7with §7*Create’s* §7kinetic§7 energy.)
- Re-added *Create: Food's* sweet berry cake recipe.
- Removed the coin mint from *Lightman's Currency.*
- More mobs can now play instruments from the *MIMI* mod.
- A few example Vanilla Minecraft songs are now pre packaged as midi files for *MIMI!*
- Added the mod *Better Mob Combat.*
- Made all glass blocks / panes breakable from shooting arrows and fall damage, rather than *only* vanilla blocks. All regular ice and grass can now be broken from fall damage as well.
  - §7(Unfortunately, §7this §7behavior §7is §7not §7supported §7by §7guns.)
- Removed the mod *Claim Shop for Lightman's Currency,* as its functionality was broken.
- Repositioned the player's paper doll to the bottom right corner of the screen §7(in §7honor §7of §7earlier §7Necohydra §7versions!)
- Removed *Better Tridents,* as some of its features conflicted with *Progressive Bosses.*
- Fixed several inconsistent food eating animations.
- Disabled *Quark's* "Elytra Indicator," as it would cause all GUI to move to be shifted to the left.
- Removed Brown Bears from *Naturalist* as *Alex's Mobs* has more functional, and highly similar Brown Bears. (Related crafting recipes that used bear fur from *Naturalist* now use bear fur from *Alex's Mobs.*)
- Changed the "Player Reporting" button to say "Player List" instead.
- Disabled *Quark's* Greener Grass feature.
- Disabled the "Pole Climbing" feature of *ParCool,* as players can inconsistently climb the corners of connected fences. Rope items have replaced this feature.
- Only villagers, zombie villagers, and citizens can equip MIMI instruments. (This is not enabled on Wandering Traders, as the way this feature is implemented is buggy on them.) (This is not enabled on Wandering Bakers, as they always are visually holding a barrel.)
- Disabled *Quark's* beacon redirection, as *CERBON's Better Beacons* adds similar functionality.
- You can now mine blocks with weapons by *default.* You can press [F4] to toggle this!
- Updated a handful of mods. †
  
### Accessibility
- Added controller functionality via Steam's Big Picture mode! There is now a button that shows how to set this up next to the "Keyboard Settings" button in the game's settings.
- Readded vanilla Minecraft’s accessibility onboarding screen.
- 
### §4Introduced Bugs
- The positioning of curios elements with *InventoryHUD+* is no longer possible in-game. For an unknown reason, it no longer detects the *Curios* mod.
- Soul vulture textures are buggy, due to the "soul_vulture_glow" texture. I have been unable to get any soul vulture textures to work properly.

Finally, the credits of the game have also been modified to give credit to all active Panjerians prior to v3.3.0, and to all mod and resource pack creators! §aThank §ayou §aall §aso §amuch §afor §ayour §acontinuous §asupport! :green_heart:

§3Note: §7All §7language §7file §7related §7changes §7are §7in §7English §7- §7US §7(en_us) §7only.

† ETF, EMF, Leawind, Dynamic FPS, Cherished Worlds, ImmediatelyFast, World Play Time, Skin Layers 3D, Sound Physics Remastered, Aquaculture, Amendments, Enhanced Celestials, Guard Villagers, Chat Heads, Etched, Item Borders, ModernFix, First-person Model, Entity Culling, Bad Wither No Cookie, Sophisticated Core, Sophisticated Storage, Sophisticated Backpacks, Curios API


## §6[3.2.0] §7- §711/19/24

### Mod Updates
- Updated a small handful of mods. †
- Backported *Mine and Slash* from v5.9.12 to v5.8.3, as it caused issues when playing on servers.
- Backported  *Additional Placements* from v2.1.0 to v1.8.0, as it caused stairs in newly generated worlds to be rotated incorrectly.

### Config Changes
- Fixed the positioning of buttons for *Inventory Profiles Next* in missed GUIs.
- Added support for additional missed plants in the shaders config.

### Cosmetic & UI Improvements
- Added 40+ custom tips that appear on menus such as loading or pause screens.
- Changed some of Minecraft's language files to add immersion!

† Chat Heads, Connectivity, Deeper and Darker, First-Person Model, Simple Voice Chat, Skin Layers 3D, Sophisticated Backpacks, Sophisticated Core, Sophisticated Storage

## §6[3.1.0] §7- §711/13/24

### General Adjustments & Fixes
- Fixed unidentified enchantments not being able to be identified at an enchanting table. This was caused by the custom enchanting mechanics added by *Quark: Oddities*. Disabled the enchantment module of *Iron's RPG Tweaks* to preserve functionality.
- Trying to destroy end crystals used to be impossible and would crash the client. This has been fixed by downgrading the versions of *InsaneLib* and *Enhanced AI*.
  
### Cosmetic & UI Improvements
- Repositioned *Quark’s* auto-walking HUD.
- Added a warning tooltip when changing the GUI’s scale to something other than 3x.
- Polished language files (e.g., the chat prompt to set up *Simple Voice Chat*, fixing grammar across mods, etc.) and improved several textures.
- Removed *Potato Shaders* and replaced them with *Complimentary Shaders*. Added compatibility with all modded ores and plants.
- Added a link to the modpack’s GitHub page to the main menu.

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


## §6[3.0.0] §7- §710/8/24

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
- Removed the *Physics* mod (3D particles).
- Removed some unobtainable blocks and redundant items/entities (e.g., multiple mods adding crabs).
- Removed *End's Delight* due to useless food buffs.
- Removed a few features from *Quark* mod.
- Removed extra weapons and effects from *Simply Swords.*
