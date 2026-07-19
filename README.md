# Spell Thief — Foundry VTT Module

> *A weaver of stolen magic, a parasite in the arcane ecosystem.*

A homebrew D&D 5e (2024) class for Foundry VTT. Spell Thieves do not only study magic — they **steal it**. They siphon spells mid-cast, hijack curses meant for allies, and redirect devastating effects back at their enemies. Reactive, tactical, and dangerous to spellcasters, a Spell Thief turns arcane power into a liability.

---

## Installation

### Via Manifest URL (Recommended)
1. Open Foundry VTT and navigate to **Add-on Modules**
2. Click **Install Module**
3. Paste the manifest URL:
   ```
   https://raw.githubusercontent.com/Nispeter/Foundry-spell-thief/main/module.json
   ```
4. Click **Install**

### Manual Installation
1. Download the latest release zip from the [Releases page](https://github.com/Nispeter/Foundry-spell-thief/releases/latest)
2. Extract into your Foundry `Data/modules/` folder
3. Restart Foundry and enable the module in your world

---

## Requirements

| Dependency | Version |
|-----------|---------|
| Foundry VTT | 13+ |
| D&D 5e System | 5.0.0+ |

---

## Plutonium / 5etools Level-Up (Optional)

If you use the **Plutonium** module, the class is also shipped as a 5etools-format homebrew (`spell-thief.plutonium.json`) so that Plutonium's **Level Up** button and its spell-selection screens recognize the Spell Thief. (This is separate from the dnd5e compendium below: the compendium uses the native dnd5e advancement flow — drag the class onto a character — while the Plutonium homebrew powers Plutonium's own Level-Up flow. Use whichever you prefer; don't mix both on the same character.)

### Import by URL (works for any client, including remote players)
1. In Foundry (as GM), open **Game Settings → Configure Settings → Module Settings → Plutonium → Open Config Editor**.
2. Find **Additional Homebrew Files** and add this URL as an entry:
   ```
   https://raw.githubusercontent.com/Nispeter/Foundry-spell-thief/main/spell-thief.plutonium.json
   ```
3. **Save** and reload Foundry (F5). The **Spell Thief (SpTh)** source becomes available.

### Import from a local folder instead
1. Place `spell-thief.plutonium.json` in your Foundry `Data/assets/homebrew/` folder.
2. In the Plutonium **Config Editor**, enable **Load Local Homebrew** (and **Use `index.json`** if your players lack "Use File Browser" permission — an `index.json` of the form `{"toImport":["spell-thief.plutonium.json"]}` is required in that case).
3. Reload Foundry.

> After updating the homebrew, URL users just reload Foundry (no manual re-import); Plutonium re-reads the source on load.

---

## Contents

### Class Features (Items Compendium)
- **Spell Thief** — Base class item
- **Larceny Dice** — Core resource tracker
- **Arcane Pickpocket** — Reaction spell theft (1st level)
- **Cunning Action** — Bonus action mobility (1st level)
- **Redirect Magic** — Damage redirection (2nd level)
- **Fighting Style** — Martial feat (2nd level)
- **Spellcasting** — Half-caster progression (2nd level)
- **Larcenous Discipline** — Subclass choice (3rd level)
- **Extra Attack** (5th level)
- **Spell Interception** — Concentration theft + Arcane Sense (5th level)
- **Focus Specialization** — Status Transposition or Arcane Absorption (7th level)
- **Improved Arcane Larceny** (11th level)
- **Grand Theft Magic** (15th level)
- **Master Larcenist** (17th level)
- **Elusive** (18th level)
- **Epic Boon** (19th level)
- **Arcane Heist** (20th level)

### Disciplines (Subclasses)
- **Arcane Reaver** — Frontline anti-mage, blade and stolen sorcery
- **Hex Broker** — Curse collector and condition manipulator
- **Mirror Savant** — Illusion trickster, reflector of magical energy

### Journal Compendium
- Full class rules, feature descriptions, and design philosophy

### Plutonium Homebrew
- `spell-thief.plutonium.json` — 5etools-format homebrew for Plutonium's Level-Up flow (see [Plutonium / 5etools Level-Up](#plutonium--5etools-level-up-optional) above)

---

## Class Overview

| Level | Key Features |
|-------|-------------|
| 1 | Arcane Pickpocket, Cunning Action |
| 2 | Redirect Magic, Fighting Style, Spellcasting |
| 3 | Larcenous Discipline |
| 5 | Extra Attack, Spell Interception |
| 7 | Focus Specialization |
| 11 | Improved Arcane Larceny |
| 15 | Grand Theft Magic |
| 17 | Master Larcenist |
| 18 | Elusive |
| 19 | Epic Boon |
| 20 | Arcane Heist |

**Spellcasting:** Half-caster (Intelligence), prepared spells from a spellbook  
**Hit Die:** d8  
**Saves:** Dexterity, Intelligence  
**Armor:** Light, Medium  

---

## Multiclassing

**Requirements:** Intelligence 13, Dexterity 13  
**Proficiencies Gained:** Light armor, simple weapons, thieves' tools

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for full version history.

---

## Feedback & Bugs

- Open an [Issue](https://github.com/Nispeter/Foundry-spell-thief/issues) on GitHub
- DM **Nisp** on Discord

---

## Credits

**Design:** Nisp  
**System:** D&D 5e (2024 edition)

---

*Spell thieves don't borrow power — they harvest it.*