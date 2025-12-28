# ⚒️ DungeonForge - Roguelike Dungeon Crawler

A procedurally generated roguelike dungeon crawler built with **HTML5, CSS, and vanilla JavaScript**. Explore endless dungeons, encounter procedurally generated monsters, collect loot, and survive the depths!

🎮 **[Play Now](https://gzeu.github.io/dungeonforge/)** | 📖 **[GitHub Repository](https://github.com/Gzeu/dungeonforge)** | 🔗 **[Pollinations.ai Generator](https://pollinations.ai.org/lbgw3gxd0m)**

---

## ✨ Features

### 🎲 Procedural Generation
- **Random Characters**: 4 character classes with rarity-based stat scaling
- **Infinite Dungeons**: Randomly generated rooms and encounters
- **Monster Variety**: 8+ enemy types with scaled difficulty
- **Dynamic Loot**: Procedural item drops with rarity tiers

### ⚔️ Gameplay Mechanics
- **Turn-Based Combat**: Strategic combat encounters
- **Character Stats**: Strength, Agility, Intelligence, and Health
- **Rarity System**: Common → Uncommon → Rare → Epic → Legendary
- **Floor Progression**: Difficulty increases with deeper dungeon floors
- **Game Log**: Real-time action feed with color-coded messages

### 🎨 User Interface
- **Cyberpunk Aesthetic**: Cyan-themed dark interface
- **Real-Time Updates**: Live character and enemy stats
- **Responsive Design**: Works seamlessly on desktop and mobile
- **Smooth Animations**: Hover effects and transitions

---

## 🚀 Quick Start

### Play the Game

Visit: [https://gzeu.github.io/dungeonforge/](https://gzeu.github.io/dungeonforge/)

- Click **"🎲 New Character"** to create your hero
- Click **"🚪 Enter Dungeon"** to start your adventure
- Click **"🗺️ Explore"** to encounter rooms and enemies
- Challenge yourself to go deeper!

### Run Locally

```bash
# Clone the repository
git clone https://github.com/Gzeu/dungeonforge.git
cd dungeonforge

# Open in your browser
open index.html
# or
firefox index.html
```

> **Note**: This is a single-file implementation for simplicity and ease of deployment!

---

## 🎮 CYBER DUNGEON: Enhanced Game Mode (game1.html)

### 🌐 What's New

**CYBER DUNGEON** is an advanced roguelike variant featuring a complete meta-progression system, tactical combat skills, and persistent upgrades. This cyberpunk-themed variant transforms DungeonForge into a strategic dungeon crawler with long-term progression mechanics.

#### 🔮 Meta-Progression System

Your progress persists across multiple runs through the **Black Market** upgrade system:

- **Credits Banking**: Accumulate "CR" (Credits) from defeated enemies that carry over between runs
- **Cyberware Implants**: Permanent stat upgrades purchased with Credits
  - Subdermal Armor: +2 Defense
  - Neural Link: +3 Agility  
  - Power Core: +3 Strength
  - Advanced variants unlock at higher credit thresholds
- **Tech Parts**: Specialized materials salvaged during runs used for weapon upgrades
- **Automatic Save**: All progress saves to `localStorage` for cross-session persistence

#### ⚡ Class System & Tactical Skills

Choose your operative class at the start. Each has unique stat distributions and signature skills:

| Class | HP | Mana | Str | Agi | Def | Signature Skill |
|-------|----|----|-----|-----|-----|------|
| **Netrunner** 🖥️ | 80 | 100 | 8 | 20 | 5 | Neural Spike (200% electrical damage) |
| **Street Samurai** ⚔️ | 150 | 30 | 18 | 12 | 12 | Blade Waltz (3 quick strikes) |
| **Techie** 🔧 | 110 | 60 | 12 | 10 | 18 | System Reboot (heal + cleanse) |

**Neural Deck** (Tactical Skills):
- **Neural Spike**: 15 MP - 200% weapon damage with electrical surge + guaranteed crit
- **Blade Waltz**: 10 MP - Execute 3 quick strikes with 50% crit chance each
- **System Reboot**: 25 MP - Restore 30% Max HP and clear all status effects
- **Overdrive Mode** (Ultimate): 40 MP - 5-second combat boost with increased agility + visual UI shift

#### 🔓 Interactive Exploration Events

Exploration is no longer linear. Each sector now includes multiple event types:

- **Data Terminals** 💾: Hack a terminal for bonus credits
  - Correct decryption code → +50-100 CR
  - Failed hack → Combat trigger (security trace)
- **Black Market (Mid-Run)** 🖤: Temporary shop to spend current run credits on consumables
  - Stim-Injector: +50 HP
  - Firewall Chip: +20% Defense for 3 turns
  - Overdrive Shard: Instant skill cooldown reset
- **Security Traces** 🚨: 50% chance after failed hacks to spawn elite "Corpo Enforcer" enemy
- **Sector Transitions** 🎨: Background and UI colors shift every 5 floors
  - Neon Slums (Floors 1-5): Cyan theme
  - Corporate Labs (Floors 6-10): Magenta theme
  - The Deep Web (Floors 11+): Glitch aesthetic

#### 🎖️ Status Effects & Synergies

Combat now features interconnected status mechanics:

- **System Shock** ⚡: Enemy is stunned for 1 turn; all electrical skills deal +50% damage
- **Neural Overload** 🔴: Defense reduced by 30%; takes additional damage from skill attacks
- **Firewall Active** 🛡️: Incoming damage reduced by 40% for 2 turns
- **Overdrive** 🚀: Agility +100%, attack speed doubled; skills cost 50% less MP

#### 🏆 Achievements & Lore Database

- **Lore Terminal**: Unlocks encyclopedia entries for each defeated boss
- **Achievement Chips**: Visual badges for milestones
  - "Netrunner Elite": Complete 10 runs as Netrunner
  - "Iron Will": Reach floor 20 without using consumables
  - "Glitch Master": Accumulate 1,000+ Credits in a single run

---

## 📋 Game Elements

### Character Classes

- **Warrior** ⚔️ - High Strength, balanced stats
- **Mage** 🔮 - High Intelligence, mana-based
- **Rogue** 🗡️ - High Agility, fast and evasive
- **Paladin** ⚡ - Balanced tank, all-rounder

### Rarity Tiers

| Rarity | Stat Multiplier | Probability |
|--------|-----------------|-------------|
| Common | 1.0x | 60% |
| Uncommon | 1.5x | 25% |
| Rare | 2.0x | 12% |
| Epic | 2.5x | 3% |
| Legendary | 3.0x | <1% |

### Room Types

- **Empty Chamber** 🏜️ - Safe passage
- **Treasure Room** 💎 - Find valuable loot
- **Monster Lair** 👹 - Combat encounter
- **Boss Chamber** 👿 - Dangerous boss fight
- **Trap Corridor** ⚠️ - Hazards and damage

### Enemies

Goblins, Orcs, Skeletons, Dark Knights, Demons, Dragons, Wraiths, Trolls, Drone Scrappers, Corpo Enforcers, Glitch Wraiths

### Loot

Iron Swords, Shields, Potions, Gold Coins, Enchanted Rings, Tech Parts, and more!

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Architecture**: Single-page application (SPA)
- **Storage**: LocalStorage for save data and meta-progression
- **Hosting**: GitHub Pages
- **Generator Integration**: Pollinations.ai procedural generation

---

## 📁 Project Structure

```
dungeonforge/
├── index.html          # Main game file (all-in-one)
├── game.html           # Alternative game mode
├── game1.html          # CYBER DUNGEON (enhanced variant)
├── README.md           # This file
└── .gitignore
```

> **Note**: This is a single-file implementation for simplicity and ease of deployment!

---

## 🎮 Gameplay Loop

```
1. Generate Character → 2. Enter Dungeon → 3. Explore Rooms
↓
4. Encounter Events (Combat/Treasure/Terminal/Shop)
↓
5. Manage Resources (HP/MP/Credits) → Defeat Enemies
↓
6. Collect Loot & Credits → Proceed to Next Floor
↓
7. Return to Main Menu → Spend Credits on Cyberware Upgrades
↓
8. New Run with Enhanced Stats ↻
```

---

## 🔮 Future Enhancements

- [ ] **Combat System**: Attack/Defend/Item usage
- [ ] **Player Inventory**: Equipment and consumables
- [ ] **Experience & Leveling**: Character progression
- [ ] **Skills & Abilities**: Class-specific powers
- [ ] **Bosses & Mini-bosses**: Unique encounters
- [ ] **Audio**: Sound effects and music
- [ ] **Animations**: Combat and UI animations
- [ ] **Leaderboard**: High score tracking
- [ ] **Multiplayer**: Co-op or PvP modes
- [ ] **Pollinations.ai Integration**: AI-generated descriptions and sector art
- [ ] **Branching Paths**: Player choice in dungeon navigation
- [ ] **NPC Encounters**: Merchants, lore-givers, questgivers

---

## 💾 Save & Load

Your progress is automatically saved to browser **LocalStorage**. Refresh the page to continue your adventure!

> **Note**: Clearing browser data will reset your save.

---

## 🤝 Contributing

Want to add features or fix bugs?

1. **Fork the repository**
2. **Create a feature branch**:
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit changes**:
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to branch**:
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

---

## 📄 License

This project is open source and available under the **MIT License**.

---

## 🎯 Roadmap

### Phase 1 ✅ Complete
- Basic dungeon generation
- Character creation system
- Room encounters
- Loot system
- GitHub Pages deployment

### Phase 2 🚧 In Progress
- Full combat mechanics
- Inventory system
- Equipment system
- **CYBER DUNGEON variant (game1.html)**
  - Meta-progression system
  - Tactical skill deck
  - Interactive exploration events
  - Status effect synergies

### Phase 3 📋 Planned
- Boss encounters
- Skill trees
- Prestige/New Game+
- Mobile optimization
- Branching narrative paths
- Faction reputation system

---

## 👨‍💻 Author

**George Gaze** - Full-stack developer passionate about Web3, gaming, and open-source projects.

**GitHub**: [@Gzeu](https://github.com/Gzeu)

**Projects**: [Cyclebound](https://github.com/Gzeu/cyclebound), [VorbaBuna](https://github.com/Gzeu/vorbabuna), [Guildmaster.io](https://github.com/Gzeu/guildmaster)

---

## 📞 Support

Found a bug? Have a suggestion?

🐛 **Open an** [Issue](https://github.com/Gzeu/dungeonforge/issues)
💬 **Start a** [Discussion](https://github.com/Gzeu/dungeonforge/discussions)
⭐ **Star the repository if you enjoy the game!**

---

## 🎮 Have Fun and Happy Dungeon Crawling! ⚒️

```
.___                             ___________
   /   |__  ___  _______  ___  ____  \_   _____/
  /   ..." | "/ ...________   .../ .../ .../ .../ .-""""""""""".-"
L.___.__.__/    " ....l..../ .../ .../ .../ .../ ../ """ " / "
  _____  .____                                  ___________
 _/ ____\|    |   ____  ____   ____   ____   / _____\__    ___/
 \   __  |    |  /  _ \ / \  \ / ___\ /  _ \ \   __  \|    |  
  |  |_| |    |_(  <_> )  Y Y / /_____  <_> ) |  |_|  )    |  
  |   __|    |____/\___/|__|_|/        \___/  |     ___/|____|  
  |__|    |_____________________             |__| \
```
