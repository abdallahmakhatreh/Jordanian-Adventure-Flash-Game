# Jordanian Adventure - Flash Platformer Game

An interactive, cultural arcade-style side-scrolling platformer game engineered using Adobe Flash CS3 and scripted with ActionScript. Developed as an academic project for the Multimedia Systems and Technologies module, the game requires players to navigate custom-designed stages featuring historic Jordanian landmarks, collect coins, use interactive keys, and avoid hazardous obstacles.

---

## 🛠️ Tech Stack & Architecture
* **Development Environment:** Adobe Flash CS3 Professional
* **Scripting Language:** ActionScript (Event-Driven Game Logic & Collision Detection)
* **Design Pattern:** Frame-Based State Machine (`stage1`, `stage2`, `game over`, `end`)
* **Camera System:** Integrated virtual camera framework (`vcamfile.fla`) for smooth horizontal tracking.

---

## 🕹️ Gameplay Mechanics
* **Movement Matrix:** Responsive side-scroller physics using the keyboard Arrow Keys (Left/Right to move, Up arrow to jump).
* **Interactive Elements:** Closed door mechanisms requiring players to locate and harvest specific key items (`youneedakeytoenter111`) before advancing.
* **Score & Win Conditions:** Interactive item collection logic handling score counters (Gold coins) and terminal milestone detection triggers (`FINISH line`).

---

## 🎨 Cultural Multimedia Asset Pipeline
The game integrates specialized multi-format design components localized to showcase iconic landmarks within Jordan:
* **Visual Banners:** Specialized vector/raster backdrops featuring the Dead Sea and Petra (*Al-Khazneh*).
* **Graphic Sprites:** Animated environmental structures, asset collision obstacles, and Jordan's national flag asset markers.
* **Audio Engineering:** Embedded background ambient soundtracks driving thematic immersion during live execution.

---

## 📂 Project Structure Guide
* **`Abdallah's project.fla`:** The master authoring project source file containing timeline nodes, symbol sheets, and ActionScript code layers.
* **`Abdallah's project.swf`:** The compiled, playable Shockwave Flash container executable.
* **`vcamfile.fla`:** Custom workspace camera attachment handling tracking and perspective adjustments.
* **`Pictures/`:** Centralized asset ledger containing all interface maps, key vectors, background layers, and music files.

---

## 📺 Gameplay Demonstration Video

Click the image below to watch the live gameplay showcase of the project on YouTube:

[![Jordanian Adventure Gameplay](https://img.youtube.com/vi/0zdotpEJmEo/maxresdefault.jpg)](https://youtu.be/0zdotpEJmEo)
