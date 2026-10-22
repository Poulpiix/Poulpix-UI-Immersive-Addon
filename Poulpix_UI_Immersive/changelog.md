# Poulpix UI Immersive — What's new  (0.9.76)

Changes to the addon, day by day, newest first.

---

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
