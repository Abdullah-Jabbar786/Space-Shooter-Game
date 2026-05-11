# 🚀 Space Shooter Game

<div align="center">

**A high-octane 2D space shooter game built with professional OOP design in C++ using Raylib**

[![Language](https://img.shields.io/badge/Language-C%2B%2B-blue?style=flat-square)](https://cplusplus.com/)
[![Library](https://img.shields.io/badge/Library-Raylib-green?style=flat-square)](https://www.raylib.com/)
[![License](https://img.shields.io/badge/License-MIT-orange?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)]()

</div>

---

## 📋 Table of Contents
- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [OOP Design](#oop-design)
- [Documentation](#documentation)
- [Future Enhancements](#future-enhancements)
- [License](#license)

---

## 🎮 About

**Space Shooter Game** is an immersive 2D arcade-style shooter developed as a comprehensive second-semester Object-Oriented Programming (OOP) project. The game demonstrates real-world application of OOP principles, design patterns, and software engineering best practices.

Navigate through waves of enemies, manage your ammunition wisely, and achieve the highest score possible. The game features progressive difficulty, interactive UI, and dynamic gameplay mechanics built entirely with clean, maintainable C++ code.

---

## ✨ Features

### Gameplay
- 🎯 **Smooth Player Movement** - Responsive keyboard-based controls for precise navigation
- 🔫 **Weapon System** - Efficient bullet-based attack mechanics with collision detection
- 👾 **Enemy AI** - Intelligent enemy spawning with multiple behavior patterns
- 💥 **Collision Physics** - Robust collision detection between player, enemies, and bullets
- 🌊 **Progressive Waves** - Increasingly challenging enemy waves as you advance
- 🎵 **Sound & Visual Feedback** - Audio cues and animations for enhanced immersion

### User Interface
- 🏠 **Main Menu** - Interactive menu with button system
- 📊 **Live Score Display** - Real-time score tracking and statistics
- 💾 **Game States** - Menu, Playing, Game Over states with smooth transitions
- ⏸️ **Pause Functionality** - Pause and resume gameplay seamlessly

### Code Quality
- 🏗️ **Object-Oriented Design** - Well-structured classes with clear responsibilities
- 📐 **Design Patterns** - Implementation of proven software design patterns
- 🧹 **Clean Architecture** - Separation of concerns and modular code organization
- 📖 **Well-Documented** - Comprehensive SDA documentation and project report

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Language** | C++11/14 |
| **Graphics** | Raylib 4.x |
| **Architecture** | Object-Oriented Programming (OOP) |
| **Build System** | Makefile |
| **IDE Support** | VS Code (.vscode config included) |

---

## 📥 Installation

### Prerequisites
- **C++ Compiler** (GCC, Clang, or MSVC with C++11 support)
- **Raylib** installed on your system
- **Make** (for building with Makefile)

### Setup Instructions

#### 1. Clone the Repository
```bash
git clone https://github.com/Abdullah-Jabbar786/Space-Shooter-Game.git
cd Space-Shooter-Game
```

#### 2. Install Raylib

**On Linux (Ubuntu/Debian):**
```bash
sudo apt-get install raylib
```

**On macOS (using Homebrew):**
```bash
brew install raylib
```

**On Windows:**
- Download from [Raylib GitHub Releases](https://github.com/raysan5/raylib/releases)
- Follow the [Raylib Windows Setup Guide](https://github.com/raysan5/raylib/wiki/Working-on-Windows)

#### 3. Build the Project
```bash
make
```

The executable will be created in the build directory.

#### 4. Run the Game
```bash
./space_shooter  # On Linux/macOS
space_shooter.exe  # On Windows
```

---

## 🎮 How to Play

### Controls
| Action | Key |
|--------|-----|
| **Move Left** | `A` or `←` |
| **Move Right** | `D` or `→` |
| **Move Up** | `W` or `↑` |
| **Move Down** | `S` or `↓` |
| **Shoot** | `SPACE` |
| **Pause/Resume** | `P` |
| **Main Menu** | `ESC` |

### Objective
1. **Survive** - Dodge incoming enemy fire and collisions
2. **Eliminate** - Destroy waves of enemies with your weapons
3. **Score** - Earn points for each enemy destroyed
4. **Advance** - Progress through increasingly difficult waves
5. **Master** - Achieve the highest score possible!

### Gameplay Tips
- ⏱️ Time your shots for maximum accuracy
- 🏃 Keep moving to avoid enemy projectiles
- 🎯 Focus on one enemy at a time
- 🛡️ Learn enemy patterns for better prediction
- 📈 Chain kills to increase multipliers

---

## 📁 Project Structure

```
Space-Shooter-Game/
├── main.cpp                      # Entry point and game loop
├── Player.cpp / Player.hpp        # Player class (movement, shooting)
├── Enemy.cpp / Enemy.hpp          # Enemy class (AI behavior)
├── Bullet.cpp / Bullet.hpp        # Bullet class (projectiles)
├── Button.cpp / Button.hpp        # UI Button class
├── Graphics/                      # Game sprites and assets
├── Sounds/                        # Audio files
├── SDA-Project/                   # Software Design & Analysis documentation
│   ├── Class Diagram
│   ├── Use Case Diagram
│   ├── Sequence Diagram
│   ├── Activity Diagram
│   └── 4+1 View Model
├── Makefile                       # Build configuration
├── Project Proposal.pdf           # Initial project specification
├── Project Report.md              # Comprehensive development report
└── README.md                      # This file

```

---

## 🏗️ OOP Design

This project showcases professional OOP implementation:

### Core Classes

**Player Class**
- Encapsulation of player state (position, health, ammunition)
- Methods for movement and shooting mechanics
- Collision detection with enemies and boundaries

**Enemy Class**
- Polymorphic enemy types with different behaviors
- Inheritance for code reuse across enemy variations
- AI implementation for realistic movement patterns

**Bullet Class**
- Lightweight projectile management
- Efficient lifecycle handling (creation, movement, destruction)
- Collision detection logic

**Button Class**
- Reusable UI component
- Event handling for menu interactions
- State management (hovered, clicked, normal)

### Design Principles Applied
✅ **Single Responsibility Principle** - Each class has one core purpose  
✅ **Encapsulation** - Data hiding with public/private access control  
✅ **Inheritance** - Code reuse through parent-child relationships  
✅ **Polymorphism** - Different enemy types with shared interface  
✅ **Composition** - Game entities composed of smaller components  

---

## 📚 Documentation

### Included Documentation
- **SDA-Project/** - Complete software design and analysis artifacts
- **Project Report.md** - Detailed development report with design decisions
- **Project Proposal.pdf** - Initial project specification and scope

### Quick Links
- 🔗 [Raylib Documentation](https://www.raylib.com/docs/)
- 🔗 [C++ Standard Library Docs](https://en.cppreference.com/)
- 🔗 [Game Design Patterns](https://refactoring.guru/design-patterns)

---

## 🚀 Future Enhancements

Potential improvements and features for future versions:

- [ ] Power-ups system (shields, rapid fire, health recovery)
- [ ] Boss battles with unique attack patterns
- [ ] Leaderboard and high score persistence
- [ ] Multiple difficulty levels (Easy, Normal, Hard, Insane)
- [ ] Different weapon types with unique properties
- [ ] Particle effects for explosions and impacts
- [ ] Background music and enhanced sound effects
- [ ] Mobile/Touch screen support
- [ ] Network multiplayer gameplay
- [ ] Level editor for custom game creation

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs via GitHub Issues
- 💡 Suggest features and improvements
- 🔧 Submit pull requests with enhancements
- 📝 Improve documentation

---

## 👨‍💻 Authors

### Main Author
**Abdullah Jabbar**  
*Object-Oriented Programming Enthusiast | Game Development Learner*  
🔗 [GitHub](https://github.com/Abdullah-Jabbar786)

### Co-Authors
**Muhammad Hammad**  
*Software Developer | OOP Expert*  
🔗 [GitHub](https://github.com/MuhammadHammadCS)

**Abdul Majid**  
*Software Engineer | Game Development Contributor*  
🔗 [GitHub](https://github.com/AbdulMajid006)

### Connect
- 📧 Feel free to reach out for collaboration and feedback!

---

## 🙏 Acknowledgments

- **Raylib** - For the amazing graphics library
- **Academic Mentors** - For guidance on OOP principles and software design
- **Game Development Community** - For inspiration and resources

---

<div align="center">

### ⭐ If you found this project helpful, please consider giving it a star!

**Built with ❤️ and ☕**

</div>
