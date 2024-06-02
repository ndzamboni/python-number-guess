# Number Guesser

## Overview

**Number Guesser** is a simple command-line game written in Python where the player tries to guess a randomly generated number within a specified range. The game provides feedback on whether the guess is too low, too high, or correct, helping the player to narrow down their guesses.

## Features

- Random number generation within a user-specified range
- Feedback on each guess (too high, too low, correct)
- Count of the number of attempts taken to guess the number correctly

## Requirements

- Python 3.x

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ndzamboni/python-number-guess.git
    ```
2. Navigate to the project directory:
    ```bash
    cd number-guesser
    ```

## Usage

1. Run the script:
    ```bash
    python logic.py
    ```

2. Follow the on-screen prompts:
    - Enter the lower and upper bounds for the number range.
    - Enter your guesses until you correctly guess the number.

## Example

```plaintext
Welcome to Number Guesser!

Enter the lower bound of the range: 1
Enter the upper bound of the range: 100
Guess a number between 1 and 100: 50
Too high! Try again.
Guess a number between 1 and 100: 25
Too low! Try again.
Guess a number between 1 and 100: 37
Congratulations! You guessed the number in 3 attempts.
