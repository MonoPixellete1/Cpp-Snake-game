# 🐍 Snake Game in C++

A terminal-based Snake Game developed in **C++** featuring real-time keyboard controls, score tracking, a high score system, and special bonus fruits. The project demonstrates Object-Oriented Programming concepts, game-loop implementation, collision detection, and terminal manipulation for interactive gameplay.

---

## Features

- 🎮 Interactive terminal-based gameplay
- ⌨️ Real-time keyboard controls (W, A, S, D)
- 🍎 Regular fruit collection
- ⭐ Special bonus fruit worth extra points
- 📈 Live score tracking
- 🏆 High score tracking during execution
- 💀 Collision detection with walls and snake body
- 📋 Main menu with:
  - Start Game
  - View High Score
  - Exit

---

## Technologies Used

- C++
- Standard Template Library (STL)
- POSIX Libraries
  - `unistd.h`
  - `termios.h`
  - `fcntl.h`

---

## Project Structure

```
SnakeGame.cpp
README.md
LICENSE
.gitignore
```

---

## Controls

| Key | Action |
|-----|--------|
| W | Move Up |
| A | Move Left |
| S | Move Down |
| D | Move Right |
| X | Quit Current Game |

---

## Game Elements

| Symbol | Meaning |
|---------|---------|
| O | Snake Head |
| o | Snake Body |
| F | Regular Fruit (+10 Points) |
| S | Super Fruit (+50 Points & Snake Growth) |
| # | Border |

---

## Future Improvements

- Save high scores permanently using file handling
- Difficulty levels
- Pause and resume functionality
- Colored terminal graphics
- Sound effects
- Power-ups and obstacles
- Cross-platform support for Windows

## License

This project is licensed under the MIT License.
