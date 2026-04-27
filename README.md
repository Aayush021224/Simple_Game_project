# Simple_Game_Project
# 🎮 Stone, Paper, Scissors Game (Python)

## 📌 Project Description

This is a simple command-line based **Stone, Paper, Scissors game** developed using Python. The game allows a user to play against the computer (robot), which makes random choices each round.

The program runs in a loop, enabling continuous gameplay until the user decides to exit.

## ⚙️ How It Works

* The user selects one of the following options:

  * `1` → Stone
  * `2` → Paper
  * `3` → Scissor
* The computer (robot) randomly selects a number between 1 and 3.
* The program compares both choices and determines the winner:

  * Stone beats Scissor
  * Scissor beats Paper
  * Paper beats Stone
* If both choices are the same, the result is a draw.

## 🚀 Features

* Interactive command-line interface
* Random choice generation using Python's `random` module
* Input validation for incorrect entries
* Continuous gameplay loop
* Option to exit the game anytime by entering `0`

## 🛠️ Technologies Used

* Python
* Random module

## ▶️ How to Run

1. Make sure Python is installed on your system.
2. Run the script using:

   ```bash
   python filename.py
   ```
3. Follow the on-screen instructions to play.

## ❌ Exit Condition

* Enter `0` to quit the game.

## 📷 Example Output

```
1.STONE
2.PAPER
3.SCISSOR

Enter the choice: 1
Robot choice is: 3
Result: Player is the Winner

* User input handling
* Random number generation in Python
