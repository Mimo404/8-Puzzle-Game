<img width="1354" height="720" alt="videoframe_42604" src="https://github.com/user-attachments/assets/09f9abfe-90d0-4b3b-a05f-0980017f7ed1" />
# 8-Puzzle Game Solver using A* Search

This project is an implementation of the classic 8-Puzzle Game using the A* (A-Star) Search algorithm in Python. It includes a graphical user interface built with Tkinter that allows users to interact with the puzzle manually or watch the algorithm solve it automatically.

The project demonstrates how heuristic search algorithms can efficiently solve state-space search problems by finding the shortest sequence of moves from an initial puzzle configuration to the goal state.

---

## Features

- Interactive graphical user interface built with Tkinter
- Random generation of solvable puzzle configurations
- A* Search algorithm implementation
- Manhattan Distance heuristic
- Manual tile movement
- Animated step-by-step solution
- Heuristic value display during gameplay

---

## Algorithm

The solver uses the A* Search algorithm with the Manhattan Distance heuristic.

The evaluation function is:

```
f(n) = g(n) + h(n)
```

where:

- **g(n)** is the cost from the initial state to the current state.
- **h(n)** is the estimated remaining cost to reach the goal state.

The Manhattan Distance heuristic calculates the total horizontal and vertical distance each tile is from its correct position.

---

## How It Works

1. A random solvable puzzle is generated.
2. The player may solve the puzzle manually by clicking adjacent tiles.
3. Press **Solve (A*)** to allow the algorithm to compute the optimal solution.
4. The solution is displayed through an animated sequence of moves.

---

## Project Structure

```
8-Puzzle-Game/
│
├── eight_puzzle.py
├── 8_Puzzle_Game_AStar.ipynb
└── README.md
```

---

## Requirements

- Python 3.x

No external libraries are required. The project only uses Python's standard library:

- tkinter
- random

---

## Running the Project

Clone the repository:

```bash
git clone https://github.com/Mimo404/8-Puzzle-Game.git
```

Navigate to the project directory:

```bash
cd 8-Puzzle-Game
```

Run the program:

```bash
python eight_puzzle.py
```

---

## Concepts Demonstrated

- Artificial Intelligence
- A* Search Algorithm
- Heuristic Search
- State Space Search
- Manhattan Distance Heuristic
- Graph Search
- Python GUI Development with Tkinter

---

## Educational Purpose

This project was developed as part of an Artificial Intelligence course to demonstrate how the A* Search algorithm can efficiently solve the classic 8-Puzzle problem using heuristic search techniques.
