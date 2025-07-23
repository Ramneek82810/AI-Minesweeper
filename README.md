# 🧠 AI Minesweeper

An intelligent agent that plays the classic game of **Minesweeper** using logical inference and probability-based decision-making — built using Python. Inspired by how humans play Minesweeper with partial information, this project simulates the agent's reasoning to uncover safe cells while avoiding mines.

---

## 📌 Overview

This project builds an AI that plays Minesweeper automatically by:

- Using logical rules to infer safe and dangerous cells
- Maintaining a **knowledge base**
- Making **safe moves** based on deduction
- Making **random moves** only when no inference is possible

This project is part of Harvard's **CS50 AI course**.

---

## 🧠 Tech Stack

| Component     | Technology |
|---------------|------------|
| Programming   | Python     |
| Game Logic    | OOP (Object-Oriented Programming) |
| AI Techniques | Constraint Satisfaction, Logic Inference |

---

## 📁 Project Structure

```
AI-Minesweeper/
├── __pycache__/        # Compiled Python cache files
├── assets/             # (Optional) Images/screenshots used in README
├── minesweeper.py      # Game logic and AI agent implementation
├── runner.py           # Main runner to play and visualize the game
├── README.md           # Documentation
```

---

## 📋 How It Works

1. **minesweeper.py**  
   - Contains `Minesweeper` class to initialize the game board  
   - Contains `Sentence` class that represents logical statements about the board  
   - Contains `MinesweeperAI` that updates knowledge base, makes inferences

2. **runner.py**  
   - Runs the game in the terminal and simulates gameplay with AI moves  
   - Logs the AI's decision-making process step-by-step

---

## ▶️ Getting Started

### ✅ Prerequisites
- Python 3.x

### 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ramneek82810/AI-Minesweeper.git
   cd AI-Minesweeper
   ```

2. Run the game:
   ```bash
   python runner.py
   ```

---

## 🎯 Features

- 🤖 Smart decision-making AI
- 🔁 Knowledge base updates dynamically
- 🧠 Inference engine to deduce known safe/mine cells
- 🧪 Visual output of game state and AI actions in console

---

## 🧪 Sample Output (Console)

```plaintext
AI Making Move: (0, 1)
Added Sentence: {(0, 2), (1, 1)} = 1
Marked (0, 2) as Safe
Marked (1, 1) as Mine
...
```

---

## 📈 Future Improvements

- Add graphical user interface (GUI)
- Improve probability estimation when guesses are needed
- Animate AI decision process for educational purpose

---

