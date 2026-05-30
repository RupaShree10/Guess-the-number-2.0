# 🎮 Number Guessing Game 2.0

A console-based Number Guessing Game built with Python.

The game generates a random number within a selected difficulty range, and the player must guess the correct number. The game includes scoring, multiple difficulty levels, input validation, and a persistent leaderboard.

## Features

* 🎯 Three difficulty levels:

  * Easy (1–100)
  * Medium (1–500)
  * Hard (1–1000)
* 🏆 Score calculation based on number of attempts
* 📊 Persistent leaderboard stored in a text file
* 🔄 Play Again functionality
* ⚠️ Input validation and exception handling
* 🎲 Random number generation

## Technologies Used

* Python
* Random Module
* File Handling
* Exception Handling

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/RupaShree10/Guess-the-number-2.0.git
```

2. Navigate to the project directory:

```bash
cd Guess-the-number-2.0
```

3. Run the game:

```bash
python guessthenumber_2_0.py
```

## Game Rules

1. Enter your name.
2. Select a difficulty level.
3. Guess the randomly generated number.
4. Receive hints indicating whether your guess is too high or too low.
5. Earn a score based on the number of attempts taken.
6. Compete for a place on the leaderboard.

## Sample Gameplay

```text
Enter your name: Rupa

Choose difficulty:
1. Easy (1-100)
2. Medium (1-500)
3. Hard (1-1000)

Easy Mode selected (1-100)

I have picked a number between 1 and 100. Can you guess it?

Enter your guess: 50
Your guess is too high!

Enter your guess: 25
Your guess is too low!

Enter your guess: 37
Congratulations Rupa! You guessed the correct number in 3 attempts! Your score is 994.
```

## Future Improvements

* GUI version using Tkinter or PyQt
* Hint system (Hot/Cold)
* Multiplayer mode
* Difficulty-specific scoring
* Database-backed leaderboard
* Online leaderboard

## Screenshot

![Game Screenshot](screenshot.png)

## Author

**Rupa Shree**
