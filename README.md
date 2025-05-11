````markdown
# ♟️ Chess Game Variant

A custom-built Python-based chess variant with a unique win condition: **capture all of one type of your opponent's pieces to win the game**. This project includes complete game logic, a graphical user interface using Pygame, unit tests, and project documentation.

---

## 📁 Repository Contents

| File/Folder              | Description |
|--------------------------|-------------|
| `ChessVar.py`            | Core logic for piece movement, game rules, and win conditions. |
| `ChessGUI.py`            | Pygame-based graphical interface for playing the game. |
| `ChessVarUnitTests.py`   | Unit tests to validate game logic and functionality. |
| `images/`                | Piece images used in the GUI. |
| `Project_Proposal.pdf`   | Project goals, scope, and initial planning. |
| `Project_Report.pdf`     | Final report detailing implementation, design decisions, and evaluation. |
| `demo_video.mp4`         | Screen-recorded demo showing the game in action. |

---

## 🧠 Game Rules Overview

- The game starts with the standard chess setup.
- Each player takes turns as in regular chess.
- **Objective:** Win by capturing all of one type of opponent’s pieces (e.g., all knights, all pawns, etc.).
- **Differences from standard chess:**
  - No check or checkmate.
  - No castling, en passant, or pawn promotion.
  - The king is just a normal piece.

---

## 🚀 How to Run the Game

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/chess-game-variant.git
cd chess-game-variant
````

### 2. Install required package:

```bash
pip install pygame
```

### 3. Run the game:

```bash
python ChessGUI.py
```

---

## ✅ Features

* Full support for piece movement and capture
* Turn-based gameplay with win detection
* Intuitive GUI using Pygame
* Clean, testable code with unit tests

---

## 🧪 Running Unit Tests

```bash
python ChessVarUnitTests.py
```

Tests will verify legal moves, game state changes, and edge cases.

---

## 📹 Demo Video

[Watch the Demo Video](https://drive.google.com/file/d/1uB-XeYN2-O3k0vAruWftA0Dp04hQuKQ0/view?usp=sharing)

---

## 📄 Documents

* [📘 Project Proposal](https://docs.google.com/document/d/1tutY_TP0kAev4yc4-ioVgrXajFok9367/edit?usp=sharing&ouid=114981968576131609325&rtpof=true&sd=true)
* [📗 Final Project Report](https://docs.google.com/document/d/1mx0sKCFu7YdZQHXgzMp0DmX9c4P65lh1/edit?usp=sharing&ouid=114981968576131609325&rtpof=true&sd=true)

---

## 🛠️ Built With

* **Python 3**
* **Pygame** for GUI
* **unittest** module for testing

---

