# 🎮 AI Tic Tac Toe

A command-line Tic Tac Toe game where you play against an unbeatable AI powered by the **Minimax algorithm**.

---

## 📋 About

This is a simple Python implementation of the classic Tic Tac Toe game with an AI opponent. The AI uses the Minimax algorithm to evaluate every possible move and always plays optimally — meaning the best outcome you can achieve against it is a draw!

---

## ✨ Features

- Play against an AI that never loses
- Choose to go **first or second**
- Clean board display after every move
- Automatic win/draw detection

---

## 🧠 How It Works

The AI uses the **Minimax algorithm** — a recursive decision-making algorithm that:

1. Simulates all possible future moves for both players
2. Assigns a score to each outcome (+1 win, -1 loss, 0 draw)
3. Picks the move that **maximizes** its own score while **minimizing** yours

This guarantees the AI always plays the perfect move.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x

### Run the Game

```bash
python "AI Tic Tac Toe.py"
```

---

## 🕹️ How to Play

1. Run the script
2. Enter `1` to go first or `2` to go second
3. The board positions are numbered **1–9**, left to right, top to bottom:

```
 1  |  2  |  3
----|-----|----
 4  |  5  |  6
----|-----|----
 7  |  8  |  9
```

4. Enter a position when prompted to place your **X**
5. The AI will respond with its **O**
6. Game ends when someone wins or the board is full (draw)

---

## 📁 Project Structure

```
AI-Tic-Tac-Toe/
│
├── AI Tic Tac Toe.py   # Main game file
└── README.md           # Project documentation
```

---

## 📌 Functions Overview

| Function | Description |
|---|---|
| `main()` | Entry point; manages game loop and turn order |
| `ConstBoard(board)` | Prints the current board state |
| `User1turn(board)` | Handles the human player's move |
| `AIturn(board)` | Determines and plays the AI's best move |
| `minmax(board, player)` | Recursive Minimax algorithm |
| `analyseboard(board)` | Checks for a winner or draw |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
