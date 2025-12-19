# 🛰️ Asteroids – Pygame

A **creative arcade project** inspired by the classic *Asteroids*, built with **Python + Pygame**.  
Focused on real-time mechanics, clean architecture, and game physics.

---

## ✨ Highlights

- Framerate-independent movement (`dt`)
- Shooting system with cooldown
- Dynamic asteroid spawning and splitting
- Centralized collision logic
- Clean, object-oriented structure
- Event & state logging (`.jsonl`)

---

## 🧱 Tech Stack

![Python](https://img.shields.io/badge/Python-3.13-blue?style=flat-square&logo=python)
![Pygame](https://img.shields.io/badge/Pygame-2.6.1-green?style=flat-square)
![uv](https://img.shields.io/badge/uv-env%20manager-orange?style=flat-square)

---

## 🎮 Controls

| Key | Action |
|-----|--------|
| WASD  | Move / Rotate |
| Space | Shoot |

---

## 🚀 Run Locally

```bash
uv venv
source .venv/bin/activate
uv add pygame==2.6.1
uv run main.py
```

---

## 📂 Structure

```
main.py            # Game loop
player.py          # Player logic
asteroid.py        # Asteroids & split logic
asteroidfield.py   # Spawning system
shot.py            # Bullets
circleshape.py     # Collision base class
constants.py       # Configuration
logger.py          # Gameplay logs
```

---

## 🎨 Portfolio Note

This project was built as a **creative coding exercise** to explore:
- game loops & physics
- real-time input handling
- object-oriented design
- scalable entity systems

Designed for extension (sound, score, UI, effects).

---

## 👤 Author

**Gabriel Mariense**
