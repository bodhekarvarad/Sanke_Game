# Sanke_Game


A simple Snake Game built in C++ using `<graphics.h>`. Inspired by the classic Nokia Snake, this project demonstrates the use of graphics programming in C to create an interactive game.

---

## 📌 Description

This game allows the player to control a yellow snake that moves across the screen to collect food and grow longer. The aim is to score as high as possible without hitting the wall or the snake's own body. If the snake collides with either, the game ends.

Each time the game starts, the snake appears at a random position. The player uses number keys to move the snake in four directions (up, down, left, right). The interface includes a menu screen with instructions, a score display, current level, and maze layout.

---

## 🎮 Game Features

- Snake appears in yellow and moves pixel-by-pixel
- Random starting position on every game launch
- Keyboard controls for snake movement
- Instruction panel for user guidance
- Score, level, and maze display
- Game-over screen with results

---

## ⚙️ Functions Used

| Function         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| `rectangle()`    | Draws a rectangle using top-left and bottom-right coordinates               |
| `setcolor()`     | Sets the current drawing color                                              |
| `settextstyle()` | Sets font style, direction, and size of text                                |
| `outtextxy()`    | Displays text at a specific coordinate                                      |
| `delay()`        | Pauses the game for a specific amount of time (used to control speed)       |
| `cleardevice()`  | Clears the screen and resets the graphics buffer                            |

---

## 🕰️ Brief History

The snake game originated in 1976 with a game called **Blockade**, developed by Gremlin Industries. It gained massive popularity in 1997 when Nokia included it in the Nokia 6110 phone, starting a global mobile gaming trend.

---

## ✅ Advantages

- Easy to build with basic C knowledge
- Fun and engaging gameplay
- Great beginner project for graphics programming

---

## ❌ Limitations

- Very basic graphics
- Lacks object-oriented structure
- No sound or animations

---

## 🔮 Future Scope

- Add better graphics and animations
- Include sound effects
- Implement a Top Scores and Player Profile system
- Add multiplayer support
- Refactor code using Object-Oriented Programming concepts

---


