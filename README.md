 # Snake-Game
### Console-Based Snake Game in C++

## Overview

This project is a console-based implementation of the classic Snake Game developed using C++. The game runs in the Windows command prompt and demonstrates object-oriented programming concepts, real-time keyboard input handling, collision detection, and dynamic snake movement.

The objective is to control the snake, collect food to increase the score, and avoid colliding with the walls or the snake's own body.

---

## Features

- Classic Snake Game Gameplay
- Real-time Keyboard Controls (W, A, S, D)
- Dynamic Snake Growth
- Random Food Generation
- Collision Detection
- Score Tracking
- High Score Tracking
- Console Cursor Optimization
- Smooth Game Loop

---

## Technologies Used

- C++
- Object-Oriented Programming (OOP)
- Windows Console API
- Standard Template Library (STL)
- Visual Studio Code / Code::Blocks

---

## Concepts Implemented

- Classes and Objects
- Encapsulation
- Vectors (Dynamic Arrays)
- Enumerations
- Game Loop
- Keyboard Event Handling
- Collision Detection
- Random Number Generation

---

## Controls

| Key | Action |
|------|--------|
| **W** | Move Up |
| **A** | Move Left |
| **S** | Move Down |
| **D** | Move Right |
| **X** | Exit Game |

---

## Gameplay

- The snake starts at the center of the board.
- Eat the food (`*`) to increase your score.
- Every food item increases the snake's length.
- Avoid hitting the walls.
- Avoid colliding with the snake's own body.
- The game ends when a collision occurs.

---

## Project Structure

```
Snake-Game/
│
├── SnakeGame.cpp
├── README.md
```

---

## How to Run

### Prerequisites

- Windows Operating System
- C++ Compiler (GCC/MSVC)
- Visual Studio Code, Code::Blocks, or Visual Studio

### Compile

```bash
g++ SnakeGame.cpp -o SnakeGame
```

### Run

```bash
SnakeGame.exe
```

---

## Game Components

- Snake Head
- Snake Body
- Food Generation
- Score System
- High Score System
- Collision Detection
- Game Over Screen

---

## Learning Outcomes

Through this project, I learned:

- Object-Oriented Programming in C++
- Working with Windows Console API
- Real-time user input handling
- Implementing game loops
- Collision detection algorithms
- Managing dynamic game objects using vectors
- Basic game development concepts

---

## Future Enhancements

- Pause and Resume Functionality
- Difficulty Levels
- Multiple Food Types
- Obstacles
- Sound Effects
- Colored Console Graphics
- Save High Score to File
- Cross-Platform Support using SDL or SFML

---

## Author

**Rashi Patel**
