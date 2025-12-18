# 🎮 Maze Race Game

![Game Banner](https://img.shields.io/badge/Game-Maze%20Race-purple?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

> 🏆 **Race against AI algorithms to escape the maze!** Choose between DFS and BFS strategies to compete against intelligent opponents.

---

## 🌟 Features

### 🎯 Dual AI Modes
- **🤖 DFS (Depth-First Search)** - Explores deeply, may take longer paths
- **🚀 BFS (Breadth-First Search)** - Finds the shortest path every time

### 🎨 Visual Path Tracking
- 🔵 **Blue Trail** - Your footsteps
- 🔴 **Pink Trail** - AI's path
- 🟢 **Green Path** - Where both you and AI walked
- 🟡 **Gold Circle** - The goal!

### 🎲 5 Difficulty Levels
```
Level 1: Easy    (11x11)  ⭐
Level 2: Medium  (15x15)  ⭐⭐
Level 3: Hard    (19x19)  ⭐⭐⭐
Level 4: Expert  (23x23)  ⭐⭐⭐⭐
Level 5: Master  (27x27)  ⭐⭐⭐⭐⭐
```

---

## 🚀 Quick Start

### 🌐 Play Online (Recommended)
**No installation needed!** Just visit:
```
https://YOUR_USERNAME.github.io/maze-race-game/
```

### 💻 Run Locally
1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/maze-race-game.git
   ```

2. **Open in browser**
   ```bash
   cd maze-race-game
   open index.html
   ```
   Or simply double-click `index.html`

---

## 🎮 How to Play

### Controls
| Key | Action |
|-----|--------|
| ⬆️ `W` or `↑` | Move Up |
| ⬇️ `S` or `↓` | Move Down |
| ⬅️ `A` or `←` | Move Left |
| ➡️ `D` or `→` | Move Right |

### Game Rules
1. 🎯 **Objective**: Reach the yellow goal before the AI
2. 🚫 **Avoid**: Black walls (you can't pass through)
3. ✅ **Safe**: You can cross the AI's path (no collision!)
4. 🏁 **Win**: First to reach the goal wins!

---

## 📊 Game Mechanics

### Maze Generation
```
Algorithm: Depth-First Search (DFS)
- Generates random unique mazes
- Ensures solvable paths
- Randomized each game
```

### AI Pathfinding

#### 🤖 DFS (Stack-Based)
```javascript
✓ Uses Stack data structure
✓ Explores one path deeply
✗ May not find shortest path
```

#### 🚀 BFS (Queue-Based)
```javascript
✓ Uses Queue data structure
✓ Explores level by level
✓ Always finds shortest path
```

---

## 🎨 Visual Legend

### In-Game Elements

| Symbol | Meaning | Color |
|--------|---------|-------|
| 🔵 | **You** (Player) | Blue Circle |
| 🔴 | **AI** (Computer) | Red Circle |
| 🟡 | **Goal** (Destination) | Gold Circle |
| ⬛ | **Wall** | Black Square |
| 💙 | **Your Trail** | Light Blue |
| 💗 | **AI Trail** | Light Pink |
| 💚 | **Shared Path** | Light Green |

---

## 🏗️ Project Structure

```
maze-race-game/
│
├── index.html          # Main game file (all-in-one)
├── README.md          # This file
└── assets/            # (Optional) Screenshots
    └── screenshot.png
```

---

## 📸 Screenshots

### Main Menu
```
╔════════════════════════════════╗
║   🎮 MAZE RACE GAME 🎮         ║
║                                ║
║  🤖 Compete Against DFS AI     ║
║  🚀 Compete Against BFS AI     ║
║  ℹ️  How to Play               ║
╚════════════════════════════════╝
```

### Game Screen
```
╔══════════════════════════════════════╗
║  Your Steps: 15  |  AI Steps: 12    ║
╠══════════════════════════════════════╣
║  ██████████████████████████████████  ║
║  ██    🔵           ██          ██  ║
║  ██  ██████████  ████  ██████  ██  ║
║  ██        ██        ██    🔴   ██  ║
║  ████████  ██  ██████████████  ██  ║
║  ██              ██          🟡 ██  ║
║  ██████████████████████████████████  ║
╚══════════════════════════════════════╝
```

---

## 🔧 Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure & Canvas |
| **CSS3** | Styling & Animations |
| **JavaScript** | Game Logic & AI |
| **Canvas API** | Graphics Rendering |

---

## 🎓 Educational Value

### Data Structures & Algorithms
- ✅ **Stack** - DFS Implementation
- ✅ **Queue** - BFS Implementation
- ✅ **Graph Theory** - Maze as a graph
- ✅ **Pathfinding** - Search algorithms

### Computer Science Concepts
```
1. Depth-First Search (DFS)
2. Breadth-First Search (BFS)
3. Maze Generation
4. Game State Management
5. Event-Driven Programming
```

---

## 🎯 Game Strategy Tips

### 🏆 How to Beat the AI

#### Against DFS:
- DFS may take inefficient paths
- Look for shortcuts
- DFS might backtrack

#### Against BFS:
- BFS takes optimal path
- You need to be fast
- Learn the maze quickly

---

## 🐛 Known Issues

✅ **Fixed**: ~~Collision detection removed~~ - Players can now safely cross paths!

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. Commit your changes
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. Push to the branch
   ```bash
   git push origin feature/amazing-feature
   ```
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Your Name**
- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)
- Project Link: [https://github.com/YOUR_USERNAME/maze-race-game](https://github.com/YOUR_USERNAME/maze-race-game)

---

## 🙏 Acknowledgments

- Inspired by classic maze games
- Built with ❤️ for learning algorithms
- Thanks to all contributors!

---

## 📈 Version History

- **v1.0.0** (2024-12-18)
  - ✨ Initial release
  - 🎮 DFS & BFS AI modes
  - 🎨 Visual path tracking
  - 🐛 Fixed collision issue

---

<div align="center">

### ⭐ Star this repository if you enjoyed the game!

**[Play Now](https://YOUR_USERNAME.github.io/maze-race-game/)** | **[Report Bug](https://github.com/YOUR_USERNAME/maze-race-game/issues)** | **[Request Feature](https://github.com/YOUR_USERNAME/maze-race-game/issues)**

Made with 💜 by **Your Name**

</div>
