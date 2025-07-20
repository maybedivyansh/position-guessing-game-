Mastermind Guessing Game
=======================

A command-line implementation of the classic Mastermind game in Python. The player must guess a secret code made up of colored pegs within a limited number of tries. This project demonstrates user input handling, randomization, validation, and feedback logic.

---

## Key Features

- **Random Code Generation:** The secret code is randomly generated from a set of colors for each game.
- **Customizable Colors and Code Length:** Easily change the set of colors and code length in the code.
- **Input Validation:** Ensures user guesses are valid in both length and color.
- **Feedback System:** After each guess, the player receives feedback on how many colors are in the correct position and how many are correct but in the wrong position.
- **Limited Attempts:** The player has a fixed number of tries (default: 10) to guess the code.
- **Replayable:** The game can be played multiple times by rerunning the script.

---

## How to Play

1. Make sure you have Python 3 installed.
2. Run the script:
   ```
   python guess_game.py
   ```
3. The game will display the valid colors and prompt you to guess the code by entering four color letters separated by spaces (e.g., `R G B Y`).
4. After each guess, you'll receive feedback:
   - **Correct positions:** Number of colors guessed in the correct position.
   - **Incorrect positions:** Number of correct colors but in the wrong position.
5. You have 10 tries to guess the code. If you guess all colors in the correct positions, you win!

---

## Example Session

```
welcome to mastermind, you have 10 to guess the code... 
the valid colors are  R G B Y W O
Guess: R G B Y
correct postions : 2 | incorrect position: 1
Guess: W O B Y
correct postions : 1 | incorrect position: 2
...
you guessed the code in 5 tries!
```

---

## Key Learnings

- **User Input Validation:** Ensuring user guesses are the correct length and use only valid colors.
- **Randomization:** Using Python's `random` module to generate unpredictable codes.
- **Feedback Logic:** Implementing logic to provide meaningful feedback on each guess, similar to the real Mastermind game.
- **Dictionaries and Counting:** Using dictionaries to count occurrences of colors for accurate feedback.
- **Loops and Control Flow:** Managing game state, attempts, and user interaction.
- **Function Decomposition:** Breaking the game into clear, reusable functions for maintainability.

---
