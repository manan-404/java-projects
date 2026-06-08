# Tik-Tac-Move

A modern reimagination of the classic Tic-Tac-Toe game, built in Java using Swing for the GUI. The core twist — after each player places their 3 pieces, the game enters a **movement phase** where players can reposition their pieces strategically, eliminating draws and adding a layer of tactics not found in the original game.

---

## Features

- **Placement Phase** — Players alternate placing their 3 pieces on the board
- **Movement Phase** — Players move existing pieces to form a winning combination
- **Penalty System** — Penalizes illegal or invalid moves
- **Twice Turn Mechanic** — Rewards strategic play
- **Full GUI** — Built with Java Swing, includes title screen, player input, game board, and win screen
- **Win Detection** — Automatically detects and announces the winner

---

## Gameplay Flow

1. **Start Screen** — Displays the title and a Start Game button
2. **Player Input** — Enter Player 1 & Player 2 names and Player 1's mark (X or O)
3. **Placement Phase** — Players alternate placing their 3 pieces each
4. **Movement Phase** — Players move their pieces strategically to win
5. **Win Screen** — Displays the winner's name and mark

---

## How to Run

### Requirements
- Java JDK 23 or higher

### Steps
1. Clone or download the repository
2. Open the project in IntelliJ IDEA or any Java IDE
3. Run `Game.java` as the main class

### Using Command Line

javac Game.java GameWindow.java Player.java Board.java
java Game


---

## Project Structure

    01-tik-tac-move/
    ├── Game.java          # Entry point, controls screen transitions and game loop
    ├── GameWindow.java    # Full GUI system — all screens, layouts, and button interactions
    ├── Player.java        # Player data, coordinate system, movement and placement logic
    ├── Board.java         # Game state, move validation, win detection, penalty system
    └── README.md

---

## OOP Concepts Applied

- **Modularity** — Each class has a single, clear responsibility
- **Abstraction** — Internal logic hidden behind clean method interfaces
- **Aggregation** — Board aggregates Player objects without owning their lifecycle

---

## Team

| Name | Role |
|---|---|
| Tayyab Mangi | Core game logic, movement handling, win detection, penalty/twice-turn system |
| Abdul Manan | Player class structure, coordinate system, state tracking |
| Safiullah | Turn management, penalty handling, GUI message updates, intro & win screen design |
| Fahad Mustafa | Full GUI system, screen navigation, layout design, button interaction |

---

## Semester

**2nd Semester — BS Computer Science**
Sukkur IBA University
