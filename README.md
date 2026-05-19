# Snake Game in C

This project is a classic Snake Game developed in C using Windows console.

The game features real-time keyboard control, random food generation, scoring system, and collision detection.

---

## Features

- Real-time keyboard control (Arrow keys)
- Snake growth system
- Random food generation
- Score tracking system
- High score saved to file
- Collision detection (wall & self)
- Pause and restart functionality

---

## Technical Highlights

- Written in C language
- Uses Windows Console API (Windows.h)
- Uses conio.h for real-time input
- Uses file I/O for high score saving
- Array-based map system

---

## Controls

- ↑ ↓ ← → Move
- SPACE Pause
- ESC Exit
- R Restart
---

## How to Run

1. Open the project in Code::Blocks or Dev-C++
2. Compile `main.c`
3. Run the program in Windows console

---

## Notes

- This project is developed for Windows environment due to the use of Windows Console API.
- Game speed is controlled by an internal loop timing mechanism.
- Some console features (cursor control, keyboard input) rely on Windows-specific libraries.
