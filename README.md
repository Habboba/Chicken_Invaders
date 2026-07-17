# 🐔 Chicken Invaders

A C++/Qt recreation of the classic **Chicken Invaders** arcade game developed as part of **CSCE 1102** at **The American University in Cairo (AUC)**.

The player controls a spaceship, destroys incoming chickens with lasers, earns points, and survives as long as possible while avoiding enemy attacks.

---

# 🎮 Features

- 🚀 Player-controlled spaceship
- 🐔 Randomly spawning enemy chickens
- 🔫 Laser shooting
- 💥 Collision detection
- ❤️ Health system
- ⭐ Score tracking
- 🔊 Sound effects
- 🎨 Sprite-based graphics using Qt
- 🪟 Game Over message
- 🎯 Continuous gameplay

---

# 🛠 Technologies Used

- C++
- Qt Framework
- QGraphicsScene
- QGraphicsView
- Qt Multimedia
- Object-Oriented Programming (OOP)

---

# 📂 Project Structure

```
.
├── main.cpp
├── Game.cpp
├── Game.h
├── Player.cpp
├── Player.h
├── Enemy.cpp
├── Enemy.h
├── Bullet.cpp
├── Bullet.h
├── Score.cpp
├── Score.h
├── Health.cpp
├── Health.h
├── res.qrc
├── sound.qrc
├── GAME.pro
├── ship.png
├── chicken.png
├── evil.png
├── bulluppp.png
├── backback.jpg
└── README.md
```

---

# 🎯 Gameplay

The objective is to destroy as many invading chickens as possible before losing all health.

### Controls

| Key | Action |
|------|---------|
| ← | Move Left |
| → | Move Right |
| Space | Shoot |

---

# 🧩 Main Components

## 🚀 Player

- Controls the spaceship
- Moves horizontally
- Shoots bullets
- Detects keyboard input

---

## 🐔 Enemy

- Spawns randomly at the top of the screen
- Moves downward continuously
- Damages the player if it reaches the bottom

---

## 🔫 Bullet

- Fired from the player's spaceship
- Travels upward
- Detects collisions with enemies
- Removes enemies upon impact

---

## ❤️ Health

- Starts with 3 lives
- Decreases when an enemy escapes
- Ends the game when health reaches zero

---

## ⭐ Score

- Increases when an enemy is destroyed
- Displayed continuously during gameplay

---

# 🔊 Sound Effects

The game includes sound effects for:

- Laser firing
- Enemy destruction

Implemented using **Qt Multimedia**.

---

# 🖼 Graphics

The game uses sprite images for:

- Spaceship
- Chickens
- Background
- Bullets

instead of simple geometric shapes.

---

# 🏗 Object-Oriented Design

The project follows an object-oriented architecture with separate classes responsible for different game entities.

| Class | Responsibility |
|--------|---------------|
| Game | Creates and manages the game scene |
| Player | Controls player movement and shooting |
| Enemy | Enemy spawning and movement |
| Bullet | Bullet movement and collision detection |
| Score | Displays and updates score |
| Health | Tracks remaining lives |

---

# 🚀 How to Run

### Requirements

- Qt Creator
- Qt 5 or later
- C++ compiler (MinGW/MSVC)

### Steps

1. Clone the repository

```bash
git clone https://github.com/your-username/ChickenInvaders.git
```

2. Open

```
GAME.pro
```

using Qt Creator.

3. Build the project.

4. Run.

---

# 📚 Assignment Requirements

The project implements all required features from the assignment:

- ✔ Spaceship movement
- ✔ Chicken enemies
- ✔ Laser bullets
- ✔ Collision detection
- ✔ Health system
- ✔ Score system
- ✔ Game Over message

Bonus:

- ✔ Sound effects

---

# 👩‍💻 Authors

- **Habeba Saad**
- **Doha Nour El-Din**

American University in Cairo

CSCE 1102 — Object-Oriented Programming

---

# 📄 License

This project was developed for educational purposes as part of the CSCE 1102 course at AUC.
