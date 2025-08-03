# 🐍 Snake Game – Project

## 🎮 Project Description

This project implements a **multi-level Snake Game** on an **ILI9341 display** using a **joystick** for control. The game progresses in complexity across levels and includes interactive features such as sound effects, a scoring system, and a persistent high score menu.

The assignment is designed to test skills in **embedded programming**, **hardware interfacing**, and **real-time game logic development**.

---

## 🕹️ Features

### ✅ Basic Gameplay
- Snake moves using joystick input.
- Food appears at random positions on the screen.
- Eating food increases the snake's length and score by 1.
- Snake wraps around screen edges (no boundary collision).
- Game over occurs if the snake hits itself.
- Score is displayed on-screen.
- Level increases every 2 points.

---

### 🧩 Level Progression

#### 🔹 Level 1
- Basic gameplay with food and score.

#### 🔹 Level 2
- A digit (last digit of group number) appears as a **barrier**.
- Snake dies upon hitting the digit.
- Food avoids proximity to the digit.
- If digit spawns near snake's center, it moves to a corner.

#### 🔹 Level 3
- Food disappears after **5 seconds**.
- A **countdown timer** shows food expiration.

#### 🔹 Level 4
- Introduction of **red food** which **reduces score**.

#### 🔹 Level 5 and Onwards
- Snake speed increases by **20%** per level.
- More red (bad) foods appear as level increases.

---

### 🔊 Additional Features
- **Interactive buzzer sounds** for game events.
- **Main menu** with:
  - “New Game”
  - “High Score” (stored using EEPROM)
- Joystick-controlled menu navigation.

---

## 🧰 Development Setup

- **Platform:** Arduino / PlatformIO (Wokwi simulation or compatible board)
- **Display:** ILI9341
- **Input:** Joystick module
- **Sound:** Passive buzzer
- **Storage:** EEPROM (for high score saving)
- **Libraries:** External libraries allowed

---

## 📁 Folder Structure

