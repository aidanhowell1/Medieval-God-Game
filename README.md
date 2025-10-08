# Medieval God Game

A **top-down medieval strategy and settlement builder** where you command units, gather resources, construct buildings, expand territories, and defend against waves of enemies.  
Built entirely with **HTML5 Canvas + JavaScript**, this project explores real-time strategy mechanics in a lightweight browser environment.

---

## ⚠️ Disclaimer

This project is a **proof of concept** and currently a **work in progress**.  
Expect **bugs, unfinished mechanics, and placeholder systems**. Core features are still being tested and refined.

---

## 🏰 Gameplay Features

- **Resource Management**  
  Track and gather **wood, stone, food, and population** from resource nodes:contentReference[oaicite:0]{index=0}.  

- **Settlement Building**  
  Construct medieval structures such as:
  - Houses  
  - Farms  
  - Quarries  
  - Lumber Mills  
  - Barracks  
  - Towers  
  - Town Hall (to establish your settlement):contentReference[oaicite:1]{index=1}  

- **Units**  
  Recruit and control various units including settlers, workers, builders, warriors, archers, and knights.  

- **Territory System**  
  Expand your influence with each building constructed. Controlled areas are highlighted with glowing borders.  

- **Day/Night Cycle**  
  Time dynamically shifts between **day, dusk, night, and dawn**, altering atmosphere and strategy.  

- **Enemy Waves**  
  Survive periodic enemy attacks that test your settlement’s defenses.  

- **Particle & Screen Effects**  
  Dust, smoke, sparks, and blood effects bring battles and building actions to life. Screen shake emphasizes big impacts:contentReference[oaicite:2]{index=2}.  

- **Quests & Progression**  
  Receive quests such as “Build a Town Hall” to guide progression and unlock new phases of gameplay.  

---

## 🎮 Controls

- **Left Click** – Select units / Place buildings  
- **Right Click** – Command unit actions (move, attack, gather)  
- **WASD / Arrow Keys** – Scroll the camera view  
- **Hotkeys** – Building selection and unit commands (WIP)  
- **Sound Toggle** – Button in lower-right corner  

---

## 🛠️ Development Notes

- Entirely built in a **single `index.html` file**.  
- Uses **TailwindCSS** for UI styling.  
- Includes a **custom cursor system** with contextual icons (default, build, attack, gather).  
- Built-in **sound effects** via the Web Audio API (clicks, build, attack, quest complete, victory/defeat).  

---

## 🚀 Getting Started

Clone the repo and open in your browser:

```bash
git clone https://github.com/yourusername/medieval-god-game.git
cd medieval-god-game
open index.html
