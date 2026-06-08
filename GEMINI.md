# Project Instructions: Python Snake Game (Turtle Edition)

This project is a classic Snake game implemented in Python using the built-in `turtle` graphics library. It is designed to be lightweight, zero-dependency, and easy to run.

## Project Overview

*   **Purpose:** A simple, interactive Snake game for demonstration or casual play.
*   **Technologies:** Python 3.x, `turtle` library (standard library).
*   **Architecture:** Monolithic script (`Snake.py`) containing game logic, rendering, and event handling.

## Directory Structure

*   `Snake.py`: The entry point and complete source code for the game.
*   `README.md`: Basic user instructions and feature list.
*   `GEMINI.md`: This file, providing architectural and development context.

## Building and Running

### Prerequisites
*   Python 3 installed on the system.

### Running the Game
To start the game, run the following command from the root directory:
```powershell
python Snake.py
```

### Controls
*   **Arrow Keys (Up, Down, Left, Right):** Controls the direction of the snake.
*   The snake moves continuously in the current direction.
*   Hitting a wall or the snake's own tail resets the game.

## Development Conventions

*   **Logic:** The game loop uses `wn.update()` and `time.sleep()` for frame rate control.
*   **Rendering:** Uses `turtle` primitives (squares for segments, circles for food).
*   **State Management:** Global variables are used for score tracking and snake segments.
*   **No Dependencies:** All code should rely strictly on the Python Standard Library to maintain portability.

## Future Improvements (TODO)
*   Add a restart/quit menu instead of an automatic reset.
*   Implement variable difficulty levels (speed increases).
*   Refactor the monolithic script into a class-based structure for better maintainability.
