🧩 Escape from the Maze

🎯 Project Overview

Escape from the Maze is a terminal-based, turn-based maze simulation game developed in Java. The goal is to guide agents through a randomly generated maze filled with traps, power-ups, walls, and rotating columns. The first agent to reach the goal wins.

This project was developed to apply and demonstrate classical data structures such as Stacks, Queues, and Circular Linked Lists within a real-time, interactive scenario.



🕹️ Gameplay

Two agents (Agent 1 & Agent 2) navigate a 10x10 maze.
User inputs move the agents turn-by-turn (U, D, L, R).
Maze elements:
W: Wall (impassable)
E: Empty space
T: Trap (forces agent back 2 steps)
P: Power-up (allows passing through walls for 3 moves)
G: Goal
One random maze column rotates at certain turns using a CircularLinkedList, impacting gameplay dynamically.


⚙️ How to Run

Ensure you have Java 8+ installed.
Compile the code:
```bash
javac Main.java
```

Run the game:
```bash
java Main
```



🧱 Project Structure

🟥Agent:	Represents the agent with position, score, history (Stack), and power-ups.

🟧MazeManager:	Manages maze generation, validation, and updates.

🟨MazeTile:	Represents a single maze cell (wall, trap, power-up, etc.).

🟩GameController:	Handles game flow, agent turns, and input processing.

🟦CircularLinkedList:	Used to rotate maze columns dynamically.

🟪MyStack:	Custom stack for agent movement history (backtracking).

⬛️MyQueue:	Custom queue for future enhancements (e.g., BFS).

⬜️TurnManager:	Manages agent turns using a circular structure.

🟫Main:	Entry point of the application.



🧠 Educational Value

This project demonstrates:
➡️Use of fundamental data structures in a practical scenario.
➡️Turn-based logic and agent simulation.
➡️Modularity and object-oriented design.
