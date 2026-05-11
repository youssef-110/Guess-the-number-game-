# Number Guessing Game (Python CLI)

A fun terminal-based number guessing game built in Python with ASCII art and interactive gameplay. The player tries to guess a randomly generated number within a chosen range and limited attempts.

---

# Overview

This project is a beginner-friendly Python game that demonstrates:
- Random number generation
- User input handling
- Loops and conditionals
- Basic game logic
- ASCII art UI in the terminal

It also includes visual feedback and a counter tracking how many attempts were used.

---

# Features

- Custom range selection (min / max)
- Custom number of attempts
- Random number generation
- Hint system (higher / lower)
- Win / lose ASCII animations
- Attempt counter display using pyfiglet
- Fun terminal UI with styled text

---

# Tech Stack

- Python 3
- random module
- pyfiglet (for ASCII text styling)

---

# Installation

Install dependencies:

```bash
pip install pyfiglet
```

---

# How to Run

```bash
python main.py
```

---

# How It Works

1. User sets:
   - Number of tries
   - Minimum value
   - Maximum value

2. Program generates a random number

3. Player guesses until:
   - They find the correct number, OR
   - They run out of attempts

4. The game provides hints:
   - "HIGH" if guess is too big
   - "LOW" if guess is too small

5. Final screen shows number of attempts used

---

# Example Gameplay

```text
Enter the number of tries you want: 5
Enter the minimum number you want: 1
Enter the maximum number you want: 50

Try 1/5 - Enter your guess: 20
>>> The guess is HIGH

Try 2/5 - Enter your guess: 10
>>> The guess is LOW
```

---

# Concepts Covered

- Randomization
- Input validation
- Loops (`for`)
- Conditionals (`if/else`)
- Game state tracking
- Terminal UI design

---

# Future Improvements

- Difficulty levels (easy / medium / hard)
- Score system
- Replay option
- Time-based challenge mode
- GUI version using Tkinter
- Multiplayer mode

---

# License

Educational use project
