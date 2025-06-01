
# 🧩 Escape from the Maze

## 🎯 Project Overview

**Escape from the Maze** is a terminal-based, turn-based maze simulation game developed in Java.  
The goal is to guide agents through a randomly generated maze filled with traps, power-ups, walls, and rotating columns.  
The first agent to reach the goal wins.

This project demonstrates classical data structures such as **Stacks**, **Queues**, and **Circular Linked Lists** within a real-time, interactive scenario.

---

## 🕹️ Gameplay

- Two agents (**Agent 1** & **Agent 2**) navigate a **10x10 maze**.
- Users control agents turn-by-turn using:
  - `U`: Up  
  - `D`: Down  
  - `L`: Left  
  - `R`: Right

### Maze Elements:
- `W`: Wall (impassable)  
- `E`: Empty space  
- `T`: Trap (pushes agent back 2 steps)  
- `P`: Power-up (allows passing through walls for 3 moves)  
- `G`: Goal

✨ At certain turns, **one random column rotates** using a `CircularLinkedList`, adding dynamic challenges.

---

## ⚙️ How to Run

Make sure you have **Java 8+** installed.

**Compile the code:**
```bash
javac Main.java
````

**Run the game:**

```bash
java Main
```

---

## 🧱 Project Structure

| Component               | Description                                                        |
| ----------------------- | ------------------------------------------------------------------ |
| 🟥 `Agent`              | Represents the agent (position, score, movement stack, power-ups). |
| 🟧 `MazeManager`        | Handles maze generation, validation, and updates.                  |
| 🟨 `MazeTile`           | Represents a maze cell (wall, trap, goal, etc.).                   |
| 🟩 `GameController`     | Controls game loop, turns, and user inputs.                        |
| 🟦 `CircularLinkedList` | Rotates maze columns dynamically.                                  |
| 🟪 `MyStack`            | Custom stack used for agent movement history.                      |
| ⬛ `MyQueue`             | Custom queue (reserved for future enhancements).                   |
| ⬜ `TurnManager`         | Manages agent turns (circular fashion).                            |
| 🟫 `Main`               | Entry point of the program.                                        |

---

## 🧠 Educational Value

This project showcases:

➡️ Practical use of **fundamental data structures**
➡️ Turn-based **agent logic and simulation**
➡️ Emphasis on **modular, object-oriented design**
