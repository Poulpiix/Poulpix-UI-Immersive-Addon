# Poulpix UI Immersive — What's new  (0.9.89)

Changes to the addon, day by day, newest first.

---

## October 23, 2026 (0.9.89)
**New**
- **Setup wizard**: the first time you play a character with the addon, a short tour in your game's language shows the main features page by page (profile, HUD, player and target, action bars, nameplates, group, combat tools, bags, windows and chat, minimap and quests, camera and world, tools). Each option is explained in a line and shows on screen as soon as you tick it, with sample data on every element; keep the page, undo it and move on, or skip the whole tour. It comes back where you left it after a /reload, waits for the end of combat, and never shows again on that character once done or skipped. Characters that already used the addon are not asked. Run it again with /ui setup (or /ui tutorial).
- **/ui**: the addon's commands also answer to /ui.

**Changed**
- **Your buffs and debuffs** are sorted by time left, in the same order in and out of combat: weapon enchants first, then the auras by time left, auras without a timer at the far end.
- **/ih report**: a "Combat auras" part tells how your buffs and debuffs are drawn during a fight (take the report in combat).

**Fixed**
- **Your buffs and debuffs** in the "Bars" style keep their look in combat: icon, name, bar and time left, in one column after your weapon enchants (they turned into bare icons with a timer).
- **Aura backgrounds during a fight** (your buffs and debuffs, target and focus auras): each aura gets its own background, which comes and goes with it, instead of one background stuck at its largest size.
- **Blizzard windows** opened during a fight (game menu, settings, pop-ups...) take the addon's theme straight away.
- **Distance to your target and focus**: no more blocked actions in combat when your target is friendly.
- **Chat and damage meter**: after a /reload or a login they show up at their place straight away (they waited a few seconds at the game's own place before moving).
- **Unlock and move**: while the game counts you in combat, one message every few seconds instead of one per click.
- **Lock button** (Unlock and move): in the addon's look instead of the game's red button.
- **Loot feed and junk items**: their sample lines go away when you lock the elements again (they stayed on screen until the next loot).
- **Worn-out gear**: the game's armour figure showing your broken pieces is hidden with the other replaced Blizzard frames (the data bar and the repair prompt already tell it).

**Removed**
- The **Totems** element and its options (your totems, timer, empty slots, icon size and spacing, hiding the game's totem buttons). The game's own totem buttons show again. The Shaman call totem bar stays.

## October 19, 2026 (0.9.88)
**Fixed**
- **Damage meter**: the settings gear lines up with the buttons beside it (it sat a little lower).
- **Data bar**: its background follows the general background opacity like the other elements (it was darker).

## October 19, 2026 (0.9.87)
**Fixed**
- **Group finder**: one painted background over the whole window, the Back and Sign up buttons included (a smaller one stopped above them); the "Who" search button in the addon's look with a small magnifier in your class colour; "Filter" written on the left like the other drop-downs; the refresh button of "Browse groups" as high as the drop-downs beside it.

## October 19, 2026 (0.9.86)
**Changed**
- **Group finder**: its three tabs sit in a row above the window, like the character sheet; one painted background only; on the "Who" tab the search box, the search button and "Filter" line up at the same height, with a small magnifier in your class colour.
- **Damage meter**: the settings gear has a single outline.

**Removed**
- The "More on the nameplates" options: faction badge, fainter plates out of reach, bar colour with your debuff, combo points under your target's plate.

## October 18, 2026 (0.9.85)
**New**
- **Loot feed**: what you loot, earn, reputation and skill ups, with an optional gold per hour line.
- **Junk items** window: the cheapest junk in your bags, delete with Ctrl + click; it can show only when your bags are nearly full (the free slots show in its title).
- **Automations**: repair and sell junk at vendors, fast looting, the only dialogue choice picked for you, DELETE typed for you, cinematics skipped, a "Train all" button, clams and boxes opened, your companion pet summoned again.
- **Frame rate** display and **coordinates** under the world map.
- **Bags**: a list view (name, count, price) and quick actions to disenchant or pick a lock in one click.
- **Click casting** on the group and raid frames: a spell (or target, or the member menu) on each mouse button with Shift, Ctrl or Alt, and keys that cast on the member under the mouse.
- **Missing buffs** on the group frames: an icon on each member who lacks a buff you can cast (Fortitude, Arcane Intellect, Mark of the Wild, your blessing...).
- **Distance** to your target and your focus beside their frames, with its own settings: position (left, right, above, below, on the frame), offsets and text size.
- **Nameplates**: fainter plates out of reach of your spells, a bar colour while your debuff is on the unit, a faction badge on player plates, your combo points under your target's plate.
- **Interrupt**: cast bars of the target, focus and nameplates coloured by whether your interrupt is ready, and an **interrupt bar** for your focus (or target) with your interrupt's cooldown, a bar shape like the other cast bars, and its icon, spell name and times as you like.
- **Quest tracker**: order by level, zone, progress or name, only the quests of your zone, completed quests hidden, level before the title, objectives coloured by progress, the quests of your zone watched for you.
- **Quest help**: sounds when an objective is done and a quest is complete, progress told to your group, quests accepted and turned in for you (Shift held: no).
- **World map**: dungeon and raid entrances on the continent maps and the map of Azeroth too.
- **Data bar**: gold, durability, frame rate, latency, zone (with coordinates), reputation, professions, free bag slots, experience and time in one line; click a part to open the matching window.
- **Combat text** above your character: damage and heals you take, dodges and misses.
- **Alerts** in the middle of the screen: low health, low mana, aggro in a group, a movement spell ready again.
- **Movement spells** (Sprint, Blink, Charge, Dash...) with their cooldown.
- **Crosshair** on your character.
- **Chat**: the chat comes back after a /reload or your next login, and tabs in the addon's look.
- **Key binding mode** for the action bars: hover a button, press a key (/ih kb).
- **Spellbook** in the old layout: two columns of spells a page, the spell lines on the side, your pet's spells, every rank if you want. Click to cast, drag to a bar; it opens in combat too.
- **Macro editor**: your general and character macros, name, icon picker, text with its letter count, new / save / delete, drag to a bar.
- The spellbook and the macro editor can replace the game's ones (page "Blizzard windows"; the talents stay in the game's window); also /ih spells and /ih macros.

## October 17, 2026 (0.9.84)
**New**
- **Flight timer**: route, bar and time left while you fly. It learns how long each flight lasts.
- **World map**: level range of the zones on the continent maps, places explored by your other characters, flight masters and dungeon entrances, map fading while you move, the game visible behind the full screen map.
- **Fishing**: one key equips your pole, puts on a lure, casts and reels in; double right click to cast; louder fishing sounds.
- **Tooltips**: the skill needed by herbs and ore veins, shorter stat lines on items.
- **Quests**: the reward that sells for most is marked with a coin.

## October 17, 2026 (0.9.83)
**New: Combat tools page**
- **Threat**: a list of everyone's threat on your target, with the line not to cross and a warning sound; your threat % beside the target and focus; a coloured edge round your health bar when you get aggro.
- **Swing timer** for main hand, off hand and ranged weapon.
- **Mana**: five second rule and mana ticks on the mana bar, mana of the spell being cast, and the druid's mana under the resource bar in cat or bear form.
- **Icon of your stance, form, aspect or aura.**
- **Hunter pet mood** beside the pet health bar.
- **New spell ranks** replace the old ones on your action bars.
- **Shaman imbues** (Rockbiter, Flametongue, Windfury...) show with your buffs.

**Fixes**
- The shaman call totem bar is back, and can be moved.

## October 17, 2026 (0.9.82)
**Behind the scenes**
- Maintenance of the tools that build the addon's textures. Nothing changes in game.

## October 17, 2026 (0.9.81)
**Installation**
- The addon's folders were renamed. When you update, delete the old `Poulpix_UI_Immersive` folder from `Interface\AddOns` first, then copy the new one.

## October 16, 2026 (0.9.80)
**Improvements**
- **Combo points and cast bars** take every health bar shape (gradient, brush strokes, orbs...). Each shape list now says which bar it is for.

**Fixes**
- Combo points show again.

## October 16, 2026 (0.9.79)
**New**
- **Cooldowns**: each group (essential cooldowns, utility cooldowns, tracked buffs) can be switched off.

**Improvements**
- **Cooldowns settings**: a general section, then one section per group.

## October 16, 2026 (0.9.78)
**New**
- **Combo points as their own element**: choose "Free element" and move them anywhere with "Unlock and move", with their own scale.
- **Action bars 6, 7 and 8** of the game can be shown, with the same settings as the other bars.

**Improvements**
- **Nameplate settings** are sorted into clear sections: health bar, name and level, health text, resource bar, elite decoration, cast bar, then each kind of unit.
- **Class colours on nameplates** (players in their class colour: blue shaman, purple warlock...) are now in the "Health bar" section, and they work in more cases.

## October 16, 2026 (0.9.77)
**New**
- **Combo points**: choose their shape (square, circle, hexagon…), width, height, spacing and place (below or above the resource bar), without touching the resource bar.
- **Elite decoration**: the game's dragon (elite, rare elite) or skull (boss) next to the target, focus and nameplate bars. Left, right or both sides, adjustable size.
- **Nameplates like the target frame**: adjustable width and height, level before the name.
- **Display conditions for every kind of unit**: health bar and buffs / debuffs of enemy players, monsters and friendly NPCs can be set to Never, In a group / dungeon / raid, In a dungeon or raid, or Always. Monsters and NPCs now have separate settings.
- **Loot rolls (dice) can be moved** with "Unlock and move", with their own scale.

**Fixes**
- Health and power numbers on nameplates are now drawn above the bar, not behind it.

## October 15, 2026 (0.9.76)
**Fixes**
- **Right-click on a buff in battlegrounds and dungeons**: it cancels the buff again.
- **Target, focus and nameplate auras in battlegrounds and dungeons**: they show again, drawn by the game the same way.
- **"Bars" look in those places**: the game gives neither the spell name nor anything to fill a bar with. The icon shows with the remaining time where the bar would be.

## October 15, 2026 (0.9.75)
**Fixes**
- **Cooldowns in battlegrounds and dungeons**: the action bars show the recharge swipe again, and the icon turns grey while the spell recharges. The global cooldown alone does not grey the buttons.
- **Your buffs in battlegrounds and dungeons**: when the game hides your auras from add-ons, the game itself draws them in the "Your buffs" row (spells, totems, with their duration), after your weapon enchant. Elsewhere nothing changes.
- **Buff reminders**: no more false "Missing" in dungeons either.
- **Target bar in the middle of the screen**: when your target is behind the camera, no bar shows in the middle of the screen any more. The big red band (the game's own health bar left visible) is gone too.

## October 14, 2026
**New**
- **Bank in the addon's style**: at the banker, a "Bank" window matching your bags opens, with your bags beside it. Categories, search, sorting, free slots. Right-click moves an item from your bags to the bank and back.
- **Bag slots**: a button shows your equipped bags (drag and drop to swap them) and, at the bank, your bank bag slots with the price to buy the next one.

**Fixes**
- When the interface hides (camera mode, walking), the chat background and the social button now hide too.
- **Battlegrounds**: action bar cooldowns show again (they stayed frozen), and your buffs (spells, totems) are back in the "Your buffs" row.
- **Buff reminders**: no more false "Missing: Lightning Shield" while you have it. In battlegrounds these reminders stay quiet when the game hides your buffs.
- **Resurrection box**: the painted background now fits its content in width too.
- **Enemy target bars**: a bar that popped up in the middle of the screen is no longer drawn while the game's plate is not placed yet. New `/ih plates` command to send us the details if it happens again.

## October 13, 2026
**New**
- **The addon's own bags** (turn them on in the "Bags" tab): all your bags in one window in the addon's style.
  - Items sorted into categories: new items, equipment, consumables, quest items, trade goods, recipes, gems, containers, keys, other, junk. You can also choose a single grid.
  - Empty slots are gathered into one slot that shows how many are free.
  - Search, sorting, item level on equipment, slot border in the item's quality colour, a coin on grey items and a "Sell junk" button at vendors.
  - Slot size, slots per row and spacing can be changed. The window can be moved.
- **Your characters**: the addon remembers each character's bags, bank and gold.
  - A button shows another character's bags.
  - Hover your money to see the gold of all your characters.
  - Item tooltips show how many each character owns.
- **Starting settings**: a new player now starts with the author's full setup (brush-stroke bars, health orb, element positions…).

**Fixes**
- Message boxes ("Logout in 19 seconds"…) now always have a background of the right size.
- Windows and bags stay on screen when you change resolution or play in windowed mode.
- The backpack icon in the game's bags is the right size.

## October 12, 2026
**New**
- **The game's damage meter** takes the addon's style: painted background, brush-stroke bars, matching font and buttons.
- **The chat and the damage meter** move like the other elements, with "Unlock and move".
- **Settings easier to find**:
  - the chat and the damage meter each have their own tab;
  - "Visibility and appearance" is split by family (Player, Target, Focus, Group, Action bars…).
- **When the interface hides**, the chat, the damage meter and the minimap icons hide too.

**Improvements**
- **Contacts window**: tabs in a row at the top left, hover in your class colour.
- **Quest log**: rewards scroll with the text and no longer cover it. The Abandon / Share / Track buttons stay inside the panel.
- **Calendar**: weekday names in white, close button in the right place.
- **Game options**: menu arrows in your class colour.
- **Much lighter character sheet**: no more small stutters while it is open.

**Fixes**
- The damage meter no longer shows Lua errors and displays its lines correctly.
- The target (or focus) health bar now disappears when the target dies or is cleared during combat.
- The sample cooldowns now disappear when you leave "Unlock and move".
- The game's message boxes have their text in the right place and buttons in the addon's style.

## October 9, 2026
**New**
- **Party and raid frames** in the addon's style: brush-stroke bars, class colours, adjustable backgrounds and borders.
  - They have their own "Group and raid" tab and move with "Unlock and move".
  - Simulation mode shows a sample party and raid.
- **Cast bar shapes**: for your cast bar, the target's, the focus's and the nameplates'.
- **Tooltip health bar** as a brush stroke.
- **Loot rolls** in the addon's style, with a sample you can show (`/ih roll`).

**Improvements**
- New "brush square" icon shape.
- Tooltip text has more room around it.
- Cooldown groups stay in place and keep their size.

## October 8, 2026
**New**
- **The addon's own focus frame**, with every option of the target frame, in its own tab.
- **Quick focus**: Shift + left click on a bar sets it as your focus.
- **New folder**: the addon now installs in the `Poulpix_UI_Immersive` folder. Your settings are carried over automatically.
- **Support report** (`/ih report`) to copy when reporting a problem, and `/ih help` for the list of commands.
- **More game windows in the addon's style**:
  - guild and communities window;
  - Legacy window;
  - professions (tracked recipes appear in the quest tracker);
  - map;
  - NPC dialogs, vendors, mail and friends.

**Improvements**
- Windows open much more smoothly: fewer stutters and less memory used.
- Right-click menus are in the addon's style.

**Fixes**
- No more "action blocked" message with right-click menus and focus.

## October 7, 2026
**New**
- **Cast bars**:
  - a special colour for spells that can't be interrupted;
  - tick marks on channelled spells;
  - a latency zone;
  - "Interrupted" stays on screen for a moment.
- **Screen**: edges pulse red when your health is low, big cursor in combat, repair reminder.
- **Class reminders** when a buff, pet, poison, stance or aura is missing.
- **Profiles**: export and import in one line of text, automatic profile by situation (solo, party, dungeon, raid, mounted…).
- **Search in the settings** to find an option by keywords.
- **Absorb shields and incoming heals** shown on health bars.
- **New elements (off by default)**: totems, raid group badge, target of target, pet.
- **Character sheet**: item level and durability on each slot (option).
- **Orb shapes** (octagon, hexagon, diamond, pentagon, brush) and 8 **brush-stroke bars**.
- **10 new painted backgrounds**.

**Improvements**
- Right-click an element in "Unlock and move" to open its settings.
- Settings reorganised by topic.
- Effects are no longer cut off in a square.

## October 6, 2026
**New**
- **Brush-painted backgrounds** behind the elements, the windows and the camera mode bands, with several styles to choose from, per element and per window.
- **The game's cooldown manager** in the addon's style:
  - several presentations (icons, column, icons and bars) and layouts;
  - each group can be moved.
- **Icon shapes everywhere**: square, circle, rectangle, octagon, hexagon, pentagon.
- **Animated effects with conditions** (low health, proc, target casting…), on any element or anywhere on screen.
- **Temporary weapon enchants** (poisons, Rockbiter Weapon…) shown with your buffs.
- **Tooltips follow the cursor**.
- **Game options, character sheet, reputation and skills** in the addon's style.
- **Pets**: nameplates with their own settings.

**Improvements**
- Quest tracker: every tracked quest, new ones added at the bottom, quest item buttons.
- Lighter friendly player nameplates (name only, except in a party or a dungeon).

**Fixes**
- No more "action blocked" message at login.
- The flight path map displays correctly.

## October 5, 2026
**New**
- **Three-column character sheet**: equipment, model, and every stat at once.
- **Game windows in the addon's style**: bags, spellbook, quests, friends, guild, vendors, auction house, professions…
  - Every window can be moved and keeps its place.
- **Game tooltips** in the addon's style.
- **Your class colour** used as the accent colour everywhere.
- **Your buffs and debuffs** in movable elements.
- **Adjustable action bars**: button size, number of buttons, grids, direction.
- **Bar shapes**: gradient, flat, zigzag, bubbles, segments, orb.
- **Rarity borders** on the target and nameplates (rare, elite, boss).
- **Experience fills your class icon**.
- **Display layers** to choose which element sits in front.
- **Minimap** round, square or rectangular.
- **The addon's own game menu and bag icons**.
- **Addon logo** on the AFK screen.
- **New name**: Immersive HUD becomes Poulpix UI Immersive.

**Fixes**
- Several Lua errors and stutters when changing settings.

## October 4, 2026
**New**
- **New settings window**: categories, sections, drop-down lists, settings greyed out when they have no effect.
- **Situational camera**: combat, mounted, dungeon, NPC dialog, AFK…
- **Waypoints and ping** on screen, on the minimap and on the world map.
- **Zone name** shown elegantly each time you enter a new zone.
- **Animated effects**: over 1,000 of the game's spell effects to place on your elements.
- **Class and race emblems** drawn for the addon.
- **Simulation mode** (`/ih sim`) to see and place everything without fighting.
- **Profiles** per character.
- **Class colours** on the bars.
- **Smooth bars** with a trail on lost health.
- **Value texts** (current, max, percent…) of your choice.
- **Buffs and debuffs** on the target and nameplates.
- **The addon's own nameplates** for every unit.
- **Game menu and bags** as icons, other addons' buttons tucked around the minimap.
- **9 languages**: English, French, German, Spanish, Chinese, Korean, Russian, Japanese, Arabic.

## October 3, 2026
**First version**
- Health and resource bars, combo points, clock, minimap, quest tracker, vignette.
- The interface fades out of combat.
- The addon's own action bars.
- Element move mode.
- Restyled target frame, cast bar and chat.
