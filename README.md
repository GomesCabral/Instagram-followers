# Instagram Follower Count Guessing Game

This Python script is a fun game where users compare two random Instagram accounts and guess which one has more followers. The game continues until the user makes an incorrect guess, and their score is displayed at the end.

## Features
- **Random Account Selection**: The game randomly selects two Instagram accounts.
- **Follower Comparison**: Players must guess which account has more followers.
- **Score Tracking**: The user's score is tracked and displayed after each correct guess.
- **Game Continuation**: The game continues until the player guesses incorrectly.
- **Art and Design**: Visual elements like logos and separators enhance the game experience.

## Technologies Used
- **Python**: The programming language used for this script.
- **Random Module**: The Python `random` module is used to select random accounts from a dataset.

## Requirements
No external libraries are required, but the game relies on a `dados` file (which contains account data) and logo files (`logo.py` and `vs.py`).

## Files
- `dados.py`: Contains the data of the accounts used in the game, including follower counts.
- `logo.py`: Contains the visual elements of the game (logos and separators).
- `main.py`: The script to run the Instagram Follower Count Guessing Game.

## How to Play

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/instagram-follower-guess-game.git
````

Ensure that you have the following files in your project directory:

dados.py: This file contains the Instagram account data (names, descriptions, follower counts, etc.).
logo.py: This file contains the logo images used in the game.
vs.py: This file contains the separator for the visual game interface.
Run the game:
  python main.py

The game will display two Instagram accounts, and you must guess which one has more followers by typing 'a' or 'b'. The game continues until you make a wrong guess.
Game Flow
The game will display two random Instagram accounts (A and B) along with their names, descriptions, and countries.
You will be asked to choose which account has more followers, by typing 'A' or 'B'.
If you guess correctly, your score will increase, and the game continues.
If you guess incorrectly, the game will end and display your final score.
Example
  Compare A: Kylie Jenner, a reality TV star, from USA.
VS
Against B: Cristiano Ronaldo, a footballer, from Portugal.

Who has more Instagram followers? Type 'A' or 'B': A
You're right! Current score: 1.

Compare A: Cristiano Ronaldo, a footballer, from Portugal.
VS
Against B: Dwayne Johnson, an actor, from USA.

Who has more Instagram followers? Type 'A' or 'B': B
Sorry, that's wrong. Final score: 1

How the Script Works
Account Selection: The get_random_account() function randomly selects two Instagram accounts from a pre-existing dataset.
Guessing: The user is prompted to guess which account has more followers by typing 'A' or 'B'.
Checking the Answer: The check_answer() function compares the follower count of the two accounts and checks if the user's guess is correct.
Score Keeping: The score is updated each time the user guesses correctly.
Game Continuation: If the user guesses wrong, the game ends and their final score is displayed.
