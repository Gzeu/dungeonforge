# ⚒️ DungeonForge - Roguelike Dungeon Crawler

> A procedurally generated roguelike dungeon crawler built with **HTML5, CSS, and vanilla JavaScript**. Explore endless dungeons, encounter procedurally generated monsters, collect loot, and survive the depths!

🎮 **[Play Now](https://gzeu.github.io/dungeonforge/)** | 📖 **[GitHub Repository](https://github.com/Gzeu/dungeonforge)** | 🔗 **[Pollinations.ai Generator](https://Pollinations.ai.org/lbgw3gxd0m)**

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
1. Visit: **[https://gzeu.github.io/dungeonforge/](https://gzeu.github.io/dungeonforge/)**
2. Click **"🎲 New Character"** to create your hero
3. Click **"🚪 Enter Dungeon"** to start your adventure
4. Click **"🗺️ Explore"** to encounter rooms and enemies
5. **Challenge yourself** to go deeper!

### Run Locally
```bash
# Clone the repository
git clone https://github.com/Gzeu/dungeonforge.git
cd dungeonforge

# Open in your browser
open index.html
# or
fireox index.html
```

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
Goblins, Orcs, Skeletons, Dark Knights, Demons, Dragons, Wraiths, Trolls

### Loot
Iron Swords, Shields, Potions, Gold Coins, Enchanted Rings, and more!

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Architecture**: Single-page application (SPA)
- **Storage**: LocalStorage for save data
- **Hosting**: GitHub Pages
- **Generator Integration**: Pollinations.ai procedural generation

---

## 📁 Project Structure

```
dungeonforge/
├── index.html          # Main game file (all-in-one)
├── README.md           # This file
└── .gitignore         # Git ignore rules
```

**Note**: This is a single-file implementation for simplicity and ease of deployment!

---

## 🎮 Gameplay Loop

```
1. Generate Character → 2. Enter Dungeon → 3. Explore Rooms
↓
4. Encounter Events (Combat/Treasure/Traps) → 5. Gain Loot
↓
6. Progress Deeper (Difficulty Scales) → 7. Repeat until Death
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
- [ ] **Pollinations.ai Integration**: AI-generated descriptions

---

## 💾 Save & Load

Your progress is automatically saved to browser **LocalStorage**. Refresh the page to continue your adventure!

**Note**: Clearing browser data will reset your save.

---

## 🤝 Contributing

Want to add features or fix bugs?

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

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

### Phase 3 📋 Planned
- Boss encounters
- Skill trees
- Prestige/New Game+
- Mobile optimization

---

## 👨‍💻 Author

**George Gaze** - Full-stack developer passionate about Web3, gaming, and open-source projects.

- GitHub: [@Gzeu](https://github.com/Gzeu)
- Projects: [Cyclebound](https://github.com/Gzeu/cyclebound), [VorbaBuna](https://github.com/Gzeu/vorbabuna), [Guildmaster.io](https://github.com/Gzeu/guildmaster)

---

## 📞 Support

Found a bug? Have a suggestion?

- 🐛 Open an [Issue](https://github.com/Gzeu/dungeonforge/issues)
- 💬 Start a [Discussion](https://github.com/Gzeu/dungeonforge/discussions)
- ⭐ Star the repository if you enjoy the game!

---

## 🎮 Have Fun and Happy Dungeon Crawling! ⚒️

```
    .___                             ___________
   /   |__  ___  _______  ___  ____  \_   _____/
  /    |  \ \  \/ /  _ \ \  \/ /  \  |    __) 
 /     |  |_\   (  <_> ) \   /    \  |     \  
 \__   |____/\\_/ \____/   \_/ \__  /  \___  / 
    |__|                           \/       \/ 

    Welcome to DungeonForge!
    Can you reach the deepest level?
```
