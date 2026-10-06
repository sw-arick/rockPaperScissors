# Rock Paper Scissors

A simple **command-line Rock-Paper-Scissors game** built with Python.

The player chooses Rock, Paper, or Scissors, and the computer randomly selects its choice. The program compares both choices and determines whether the player wins, loses, or ties.

## Features

- Rock, Paper, and Scissors gameplay
- Random computer choices
- Automatic winner detection
- Play multiple rounds
- Invalid input handling
- Play-again functionality
- Runs directly in the terminal
- Uses Python's built-in `random` module

## Technologies Used

- **Python**
- **Random module** — Used to generate the computer's choice.

## How It Works

The game provides three choices:

```text
1 - Rock
2 - Paper
3 - Scissors
```

The player's number is converted into the corresponding choice.

The computer then randomly selects one of the three options using Python's `random` module.

```python
comp_choice = random.randint(1, 3)
```

The program compares both choices and determines the result.

### Winning Rules

```text
Rock vs Paper     → Paper wins
Rock vs Scissors  → Rock wins
Paper vs Scissors → Scissors wins
```

If both players choose the same option, the round is a tie.

## Play Again

After each round, the player is asked:

```text
Do you want to play again? (Y/N)
```

The program validates the response and continues until the player chooses `N`.

## Input Validation

The program handles invalid inputs so the game doesn't crash.

For example, if the user enters something that isn't a number:

```text
Please enter a valid number.
```

It also checks that the selected number is between `1` and `3`.

## Project Structure

```text
rock-paper-scissors/
│
└── rock_paper_scissors.py
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/rock-paper-scissors.git
```

### 2. Open the project folder

```bash
cd rock-paper-scissors
```

### 3. Run the game

```bash
python rock_paper_scissors.py
```

The game will start in your terminal.

## Concepts Practiced

This project was built to practice fundamental Python concepts such as:

- Variables
- Lists
- `if / elif / else`
- `while` loops
- `try / except`
- User input
- Random number generation
- Boolean logic
- Input validation

## Future Improvements

Possible improvements include:

- Score tracking
- Win/loss statistics
- Best-of-3 or Best-of-5 mode
- Different computer difficulty levels
- Colored terminal output
- Match history

## License

This project is open-source and available for learning and personal use.

---

### Built With

**Python**

A beginner-friendly project focused on **loops, conditionals, randomization, input validation, and building an interactive terminal game**.
