# 🎮 Enemy Rusher

**Enemy Rusher** is a 2D action shooter game built in **Unity** using **C#**.  
The goal is simple — survive as long as possible while destroying waves of incoming enemies.  
The game challenges players with increasing difficulty, smooth movement controls, and real-time score tracking.

---

## 🧠 Motivation

Enemy Rusher was created as part of the **AVR 401: Unity Game Development** course.  
The project was designed to demonstrate understanding of **Agile development**, **2D physics**, and **core game programming concepts** such as:

- Enemy spawning using coroutines
- Collision detection and trigger events
- Health system and UI management
- Balancing difficulty for engaging gameplay

---

## 🕹️ Gameplay Overview

- The player controls a character that can **move**, **shoot projectiles**, and **destroy enemies**.
- Enemies spawn at regular intervals from random positions.
- Each enemy hit increases the player’s **score**.
- The game ends when the player’s **health** reaches zero.
- Power-ups (optional) can provide temporary boosts like faster shooting or shields.

---

## ✨ Features

✅ **Smooth Player Movement** – Controlled via Unity’s Input System.  
✅ **Projectile System** – Player fires bullets to destroy enemies.  
✅ **Dynamic Enemy Spawning** – Managed with a coroutine to control timing and difficulty.  
✅ **Health and Score UI** – Real-time updates using Unity’s Canvas and TextMeshPro.  
✅ **Particle & Sound Effects** – Feedback for hits, explosions, and shooting.  
✅ **Modular Scripts** – Player, Enemy, and Projectile logic separated for clarity and reuse.

---

## 🧩 Scripts Included

| Script Name           | Description                                                     |
| --------------------- | --------------------------------------------------------------- |
| `PlayerController.cs` | Handles movement, shooting, and input.                          |
| `EnemySpawner.cs`     | Spawns enemies periodically and increases difficulty over time. |
| `Projectile.cs`       | Controls bullet movement, collision, and damage.                |
| `Enemy.cs`            | Defines enemy behavior, health, and destruction.                |
| `HealthSystem.cs`     | Manages player and enemy health with real-time UI updates.      |
| `GameManager.cs`      | Tracks game state, score, and restarts.                         |

---

## 🧱 Assets Used

- **Sprites:** Unity Asset Store (Free 2D Character and Enemy Packs)
- **Audio:** [Freesound.org](https://freesound.org) (for shooting and explosion effects)
- **Fonts/UI:** TextMeshPro (Unity package)
- **Backgrounds:** Custom-created gradient or tiled textures

---

## ⚙️ Development Tools

- **Engine:** Unity 2022 or later
- **Language:** C#
- **IDE:** Visual Studio / VS Code
- **Platform:** Windows, macOS (Playable in Unity Editor or as a standalone build)

---
